[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![Downloads](https://img.shields.io/github/downloads/caxanga334/cvreduxmodified/latest/total.svg?style=flat-square)

**Custom Votes Redux - Modified**
=================================


This is a modified version of
[ReFlexPoison](https://forums.alliedmods.net/member.php?u=149090)‘s [custom
votes redux](https://forums.alliedmods.net/showthread.php?t=235115) plugin.

Fixes and Features:
* Added vote logging.
* Added KZTimer support.
* Now utilizes Multi-Colors to support more game chat colors.
* Fixed default mapcycle resulting in an empty map list.
* Increased the map limit to 1024.
* Fixed call_notify not working and errors when a 'simple' vote is used without a convar as command.
* Added option to reset max vote passes on wave failure (TF2-MVM only).
* Fixed incorrectly adding quotes to vote results, making {VOTER_ID}, {VOTER_INDEX}, {TARGET_ID}, and {TARGET_INDEX} pretty much unusable.
* Added vote evasion detection and logging.
* Auto ban on vote evasion.


Examples logs from my server:

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Vote Type: List

L 04/28/2018 - 13:21:12: [Custom Votes] Vote Give Cash to RED started by
andycaleb ( STEAM_ID ). Selected Option: 4000

L 04/28/2018 - 13:33:39: [Custom Votes] Vote Give Cash to RED started by Shadow
Mario \| blw.tf ( STEAM_ID ). Selected Option: 3000

L 04/28/2018 - 13:34:00: [Custom Votes] Last vote ( Give Cash to RED ) passed. (
Option: 3000 ).

Vote Type: Map  


L 04/29/2018 - 00:11:33: [Custom Votes] Vote Change the map started by
andrewdasher673 ( STEAM_ID ). To change map from mvm_coaltown to
mvm_tunnels_a9fix1.

L 04/29/2018 - 00:11:35: [Custom Votes] Last vote ( Change the map ) passed. Map
was changed from mvm_coaltown to mvm_tunnels_a9fix1.

  
Vote Type: Players

L 04/28/2018 - 14:30:43: [Custom Votes] Vote Ban player started by TF2 GAMER (
STEAM_ID ) targeting rees123 ( STEAM_ID ).
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**Download**
=================================
For stable version, check the [releases](https://github.com/caxanga334/cvreduxmodified/releases) tab.
For development version, download the repository.

You can also download the latest development version from the [automated builds](https://github.com/caxanga334/cvreduxmodified/actions).

Feel free to report bugs/give suggestions.

For contributions, please use pull requests.

**Compiling**
=================================
* Download the plugin source from the reposity
* Get the latest version of kztimer.inc from [here](https://bitbucket.org/kztimerglobalteam/kztimerglobal/src/master/scripting/include/kztimer.inc).
* Get the latest version of afk_manager.inc from [here](https://forums.alliedmods.net/showthread.php?p=708265).
* Get the latest version of multicolors from [here](https://github.com/Bara/Multi-Colors).
* Get the latest version of sourcebanspp.inc from [here](https://github.com/sbpp/sourcebans-pp/).
