<p align="center"><img src="http://i61.tinypic.com/291dm49.png"></p>
<p align="center"><strong>The most used authentication plugin for CraftBukkit/Spigot!</strong></p>
<hr>
#####Development tools:

- Developers ChatRoom: [![Join the chat at https://gitter.im/Xephi/AuthMeReloaded](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Xephi/AuthMeReloaded?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

- Build status: [![Build Status](https://travis-ci.org/Xephi/AuthMeReloaded.svg?branch=master)](https://travis-ci.org/Xephi/AuthMeReloaded) [![Dependency Status](https://www.versioneye.com/user/projects/55bab9e8653762002000190a/badge.svg?style=flat)](https://www.versioneye.com/user/projects/55bab9e8653762002000190a)

- Build status (CircleCI): [![Circle CI](https://circleci.com/gh/Xephi/AuthMeReloaded.svg?style=svg)](https://circleci.com/gh/Xephi/AuthMeReloaded)

- Build Server (<strong>DEVELOPMENT BUILDS</strong>): <a href="http://ci.xephi.fr/job/AuthMeReloaded">Xephi's Jenkins</a>

- JavaDocs: <a href="http://xephi.github.io/AuthMeReloaded/index.html">AuthMe Javadoc</a>

- Maven Repo: <a href="http://ci.xephi.fr/plugin/repository/everything/">AuthMe Repo</a>

#####Statistics:

McStats: http://mcstats.org/plugin/AuthMe

<img src="http://i.mcstats.org/AuthMe/Global+Statistics.borderless.png">

<img src="http://i.mcstats.org/AuthMe/Rank.borderless.png">

<img src="http://i.mcstats.org/AuthMe/Version+Demographics.borderless.png">

<hr>

#####Compiling Requirements:
>- JDK 1.7
>- Maven
>- Git/Github (Optional)

#####How to compile the project:
>- Clone the project with Git/Github
>- Execute command "mvn clean install"

#####Running Requirements:
>- Java 1.7 (should work also with Java 1.8)
>- Spigot or CraftBukkit (1.7.10 or 1.8.X)

<hr>
###Plugin Description:

#####"The best authentication plugin for the Bukkit/Spigot API!"

<p>Prevent username stealing on your server! Full compatible with UUIDs and Craftbukkit/Spigot 1.8.X!<br>
Use it to secure your Offline mode server or to incrase your Online mode server's protection!</p>

<p>AuthMeReloaded disallows players who aren't authenticated to do actions like placing blocks, moving,<br>
typing commands or use the inventory. It can also kick players with uncommon long or short player names or kick players from banned countries.</p>
<p>With the Session Login feature you don't have to execute the authentication command everytime you connect to the server! Each command and every feature can be enabled or disabled from our well structured configuration file.</p>
<p>You can also create your own translation file and, if you want, you can share it with us! :)</p>

####Features:
<ul>
  <li><strong>E-Mail Recovery System !!!</strong></li>
  <li>Username spoofing protection.</li>
  <li>Countries Whitelist/Blacklist! <a href="http://dev.bukkit.org/bukkit-plugins/authme-reloaded/pages/countries-codes/">(countries codes)</a></li>
  <li><strong>Built-in AntiBot System!</strong></li>
  <li><strong>ForceLogin Feature: Admins can login with all account via console command!</strong></li>
  <li><strong>Avoid the "Logged in from another location" message!</strong></li>
  <li>Session Login!</li>
  <li>Editable translations and messages!</li>
  <li><strong>MySQL and SQLite Backend support!</strong></li>
  <li>Supported password encryption algorithms: MD5, SHA1, SHA256, <a href="https://github.com/CypherX/xAuth/wiki/Password-Hashing">xAuth</a>, <a href="http://en.wikipedia.org/wiki/Whirlpool_(cryptography)">Whirlpool</a></li>
  <li>Supported alternative registration methods:<br>
  <ul>
    <li>PHPBB, VBullettin: MD5VB - PHPBB</li>
    <li>MyBB: MYBB</li>
    <li>IPB3: IPB3</li>
    <li>PhpFusion: PHPFUSION</li>
    <li><del>Xenforo SHA1: XFSHA1</del> <strong>(Deprecated)</strong></li>
    <li><del>Xenforo SHA256: XFSHA256</del> <strong>(Deprecated)</strong></li>
    <li>Joomla: JOOMLA</li>
    <li>WBB3: WBB3*</li>
    <li>SHA512: SHA512</li>
    <li>DoubleSaltedMD5: SALTED2MD5</li>
    <li>WordPress: WORDPRESS</li>
  </ul></li>
  <li>Custom MySQL tables/columns names (useful with forums databases)</li>
  <li><strong>Cached database queries!</strong></li>
  <li><strong>Full compatible with Citizens2, CombatTag, CombatTagPlus and ChestShop!</strong></li>
  <li>Compatible with Minecraft mods like <strong>BuildCraft or RedstoneCraft</strong></li>
  <li>Restricted users (associate a Username with an IP)</li>
  <li>Protect player's inventory until a correct Authentication</li>
  <li>Saves the quit location of the player</li>
  <li>Automatic database Backup</li>
  <li>Avariable languages: en, de, br, cz, pl, fr, uk, ru, hu, sk, es, fi, zhtw, zhhk, zhcn, lt, it, ko, pt, nl, gl, bg, eu, tr (feel free to send new translations)</li>
  <li>Built-in Deprecated FlatFile (auths.db) to SQL (authme.sql) converter!</li>
  <li><strong>Import your old database from other plugins like Rakamak, xAuth, CrazyLogin, RoyalAuth and vAuth!</strong></li>
</ul>

####Configuration
<a href="http://dev.bukkit.org/server-mods/authme-reloaded/pages/configure-auth-me/">How to Configure Authme</a>
####Email Recovery Dependency
<a href="http://dev.bukkit.org/server-mods/authme-reloaded/pages/how-to-configure-email-recovery-system/">How to configure email recovery system?</a>
####Commands
<a href="http://dev.bukkit.org/server-mods/authme-reloaded/pages/command/">Command list and usage</a>
####Permissions
<ul><li>authme.player.* - for all user command
</li><li>authme.admin.* - for all admin command
</li><li>authme.* - for all user and admin command
</li><li><a href="http://dev.bukkit.org/server-mods/authme-reloaded/pages/permissions/">List of all single permissions</a>
</li></ul>
####How To
<ul><li><a href="http://dev.bukkit.org/server-mods/authme-reloaded/pages/how-to-install-and-initial-configuration/">How to Install and Setup</a>
</li><li><a href="http://dev.bukkit.org/server-mods/authme-reloaded/pages/how-to-import-database-from-xauth/">How to import database from xAuth</a>
</li><li><a href="http://dev.bukkit.org/server-mods/authme-reloaded/pages/web-site-integration/">WebSite Integration</a>
</li><li><a href="https://raw.githubusercontent.com/Xephi/AuthMeReloaded/master/src/main/resources/config.yml">Click here for an example of the Config file</a>
</li><li><a href="http://dev.bukkit.org/server-mods/authme-reloaded/pages/how-to-import-database-from-rakamak/">How to convert from Rakamak</a>
</li><li>Convert from FlatFile (auths.db but not the sqlite one ) to MySQL: /converter
</li></ul>
<hr>

#####GeoIP
<p>This product uses data from the GeoLite API created by MaxMind, available at <a href="http://www.maxmind.com">http://www.maxmind.com</a></p>
<hr>

#####Donate
<p>Do you like my work? Do you want to buy me a coffee? :)<br>
EUR: <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=QLMM9SNCX825Y"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif"></a>
USD: <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&amp;hosted_button_id=PWQMYCP2SAH6L"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif"></a></p>

#####Credits
<p>Team members: Xephi(Main Developer, Author), Maxetto(Contributor) and sgdc3(Contributor)
<p>Credit for old version of the plugin to: d4rkwarriors, fabe1337 , Whoami2 and pomo4ka</p>
<p>Thanks also to: AS1LV3RN1NJA, Hoeze and eprimex</p>
