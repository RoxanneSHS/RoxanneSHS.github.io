<!DOCTYPE html>
<html>
<head>
<!-- Global Site Tag (gtag.js) - Google Analytics -->

<!--
body  {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 12px;
  text-align: left;
  color: #000;
  background-color: #f2f2fc;
  margin: 35px 50px 35px 50px;
  padding: 0px;
  }
img {border : 0;}
h1, h2, h3, h4, h5, h6 {
  font-size: 17px;
  font-weight: bold;
  color: #0000cd;
  font-variant: small-caps;
  position: relative;
  background-color: #fff;
  z-index:10;
  }
h1, h2 {
  margin-right: 20px;
  margin-left: 20px;
  padding: 5px;
  border:1px solid #888;
  z-index:10;
  }
h3, h4, h5, h6 {
  border-left:10px solid #0000cd;
  padding-left:5px;
  border-bottom:1px dotted #0000cd;
  }
h2 {font-size : 16px;}
h3 {font-size : 15px;}
h4 {font-size : 14px;}
h5 {font-size : 13px;}
h6 {font-size : 12px;}
p, ul, table {clear:left;}
a, a:link, a:visited, a:hover, a:active {
  color: #0012ff;
  margin: 0;
  padding: 0;
  border-width: 0;
  }
a:visited {color : #0000cd;}
table {
  table-layout: auto;
  width: 100%;
  padding: 20px;
  }
.grow { width: 100%; }?
td, th {
  text-align: center;
  vertical-align: baseline;
  padding: 5px;
  border: 1px outset #aaa;
  }
th {
  background-color: #0000cd;
  color: #fff;
  font-weight: bold;
  }
hr {
  display: block; 
  margin-top: 0.5em;
  margin-bottom: 0.5em;
  margin-left: auto;
  margin-right: auto;
  border-style: inset;
  border-width: 1px;
  }
.leftalign, table.leftalign tr th, table.leftalign tr td {text-align: left;}
.section {
  position: relative;
  border: 1px dotted #bbb;
  background-color: #fff;
  margin: -30px 0px 30px 0px;
  padding: 20px 20px 10px 20px;
  }
.kit_description {
  position: relative;
  display: block;
  background-color: #f0f0f0;
  border-left: 4px solid #ccc;
  border-top: 1px dotted #ccc;
  }
.portrait_thumb {
  float: left;
  width: 125px;
  height: 125px;
  padding: 5px;
  text-align: center;
  overflow: auto;
  }
a.spoiler, a:link.spoiler, a:active.spoiler, a:visited.spoiler, a:hover.spoiler {
  color: #ccc;
  background-color: #ccc;
  border: 1px dotted #888;
  text-decoration: none;
  }
a:hover.spoiler {
  color: #000;
  border: 1px dotted #ccc;
  }
.code {
  font-family: 'Courier New', Courier, mono; 
  border: 1px solid #555; 
  border-left: 10px solid #555; 
  background-color: #eee;
  padding: 5px;
  }
.deprecated {color:#666;}
.code p {
  text-align: left;
  font-size: 100%;
  text-indent: 0px;
  margin: 5px 0 10px 0;
}
.tg {
  border-collapse:collapse;
  border-spacing:0;
  margin:0px auto;
}
.tg td{
  color: #333;
  text-align:justify;
  padding:10px 5px;
  border-style:solid;
  border-width:1px;
  overflow:hidden;
  word-break:normal;
}
.tg th{
  text-align:center;
  font-weight:normal;
  padding:10px 5px;
  border-style:solid;
  border-width:1px;
  overflow:hidden;
  word-break:normal;
}
-->

</head>
<body>
<h1>Mod Compatibility List for EET</h1>
<div class="section">

<p>Last Updated: <strong>07.02.2023</strong></p>
<p>This compatibility list is frequently updated. </p>

 
<p>Installation tips and notes on compatibility:</p>
<ul>
	<li>Automated tools like <a href="https://github.com/EE-Mod-Setup/EE-Mod-Setup">EE Mod Install Tool [1]</a> are the preferable ways to install mods for Windows users. They can automatically install huge selections of mods and you do not need to worry about install order and technical stuff.</li>
	<li>if you want to play with mods and do not use any tool support, it is highly recommended to check out the installation order and compatibility between mods. Just keep in mind that in EET game some BG1 mods need to be installed on BG:EE previous to installing EET on BG2:EE.</li>
	<li>current compatibility between EET and other modifications are listed below.</li>
	<li>note that versions of modifications below those stated are not compatible.</li>
	<li>the compatibility list does not imply that the other modifications mentioned are compatible with each other. Make sure you understand the specific requirements of each modification by looking at their readmes before you go into hardcore mixing and matching.</li>
	<li>modifications listed below support both EET Worldmap (unless stated otherwise) and BP-BGT Worldmap. It is up to you which worldmap you will use.</li>
<p>EET requires your base games to be v2.5 or later. For <strong>BG2:EE Patch 2.6 Compatibility</strong> Use EET V13 or later.</a></p>

<p>This list represents mods tested and supported by the install tool [1]. Other mods with EET compatibility may have been published that we do not know of or are in languages or code not supported. Some mods require small patches or special handling during the install procedure and therefore will fail in manual installations - they are specifically indicated in the list.</p>
</ul>
</div>

<!-- ================== T a b l e ================== --><a id="table" name="Table of Contents"></a>
<h2>Table of Contents</h2>
<div class="section">
	<ol>
		<li><a href="#bgee">Mods installed on BG:EE previous to installing EET on BG2:EE</a></li>
		<li><a href="#native">Mods installed after EET main component on BG2:EE</a></li>
	</ol> 
</div>

<!-- ================== BGEE ================== --><a id="bgee" name="bgee"></a>
<h2>Mods installed on BG:EE previous to installing EET on BG2:EE</h2>
<div class="section">

<p>EET provides limited support for mods installed on BG:EE previous to installing EET on BG2:EE. The mod resources are treated like vanilla content and patched "on the fly" during EET installation if needed. To ensure that BG:EE mods do not intervene with BG2:EE portion of the game EET prevents starting the installation when unrecognised mod is detected.</p>

<p>This section can be treated as a temporary solution. Hopefully more and more mods will receive updates to support EET natively down the line, so they could be installed after EET on BG2:EE.</p>

<p>Here is a list of supported mods installed on BG:EE</p>
<ul>
	<li><a href="https://github.com/Sampsca/BGEE-Classic-Movies">BG:EE Classic Movies</a> v1.0 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/bg1npc/">BG1 NPC Project</a> v24 or above (May be installed after EET but with deficiencies)</li>
	<li><a href="http://forum.baldursgate.com/discussion/39422/bg1npc-v21-and-bg1npc-music-pack-v6/p1">BG1 NPC Project Music Pack</a> v6 or above</li>
	<li><a href="http://forums.beamdog.com/discussion/38254/bg1-unfinished-business-v14-beta-with-bgee-compatibility-updated-2015-02-28">BG1 Unfinished Business</a> v14 [BETA] or above</li>
	<li><a href="http://forum.baldursgate.com/discussion/18833/bg-ee-dark-horizons-released/p1">Dark Horizons BG:EE</a> v2.12 or above</li>
	<li><a href="https://github.com/ArtemiusI/Drake/releases">Drake NPC</a> v0.1 BETA</li>
	<li><a href="https://github.com/MattyGroove/DrizztSaga/archive/V3.02.zip">Drizzt Saga</a> v3.02 or above (select default option during installation - despite the name it's compatible with both EET Worldmap and BP-BGT Worldmap)</li>
	<li><a href="http://mirandir.baldursgateworld.fr/garrick-tt/">Garrick: Tales of a troubadour</a> v1.24 or above</li>
	<li><a href="http://www.gibberlings3.net/garrick/">Garrick's Infatuation</a> vb0925 or above</li>
	<li><a href="https://github.com/SpellholdStudios/Isra_NPC">Isra NPC Mod</a> v3.4 or above (May be installed after EET but with less crossmod)</li>
	<li><a href="http://forum.baldursgate.com/discussion/15867/mod-npc-margarita-zelleod/p1">Margarita NPC</a> v1.0 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/59889/rough-world-beta/p1">Rough World</a> vBeta or above</li>
	<li><a href="http://forum.baldursgate.com/discussion/23861/bg-ee-mod-saradas-magic-released/p1">Saradas Magic</a> v1.1 or above</li>
	<li><a href="https://www.dropbox.com/s/tjyghy37av8gw5a/k9SharteelNPC%20-%201.4.rar?dl=1">Sharteel NPC mod for SoD</a> 1.4 beta or above</li>
	<li><a href="https://forums.beamdog.com/discussion/42721/npc-mod-sirene-npc-for-bg-ee-v1-0/p1">Sirene NPC</a> v1.0 or above</li>
	<li><a href="http://www.users.totalise.co.uk/~bluerift/#Downloads">The Stone of Askavar</a> v2.2 or above (select default option during installation - despite the name it's compatible with both EET Worldmap and BP-BGT Worldmap)</li>
	<li><a href="http://forum.baldursgate.com/discussion/15959/mod-twas-a-slow-boat-from-kara-tur-queststorenew-items-release-90/p1">T'was a Slow Boat from Kara-Tur</a> v.90 or above</li>
	<li><a href="http://forum.baldursgate.com/discussion/14092/mod-valerie-npc-for-bgee-bgt-tutu/p1">Valerie NPC Mod</a> v1.2 or above (May be installed after EET but with less crossmod)</li>
	<li><a href="http://lavas-scriptorium.weebly.com/npcs.html">Verr'Sza NPC</a> v2.4 or above</li>
		
</ul>

<p>Compatibility with EET does not mean that mods are fully compatible with each other - refer to original readme files and forum discussions for compatibility details. For example Garrick : tales of a troubadour readme file states that it conflicts with Garrick's Infatuation and Tenya NPC and it is not recommended to install them together. Same readme file also mentions that the mod requires BG1 NPC Project installed before it. The recommended install tool [1] takes care of such dependencies and conflicts.</p>

</div>

<!-- ================== NATIVE ================== --><a id="native" name="native"></a>
<h2>Mods installed after EET main component on BG2:EE</h2>
<div class="section">

<p>This list, sorted in alphabetical order, contains BG2:EE and BG:EE mods that have native EET support. Some of them are only available as a beta for now, so keep that in mind. This list states technical feasibilities but is no recommendation.</p>
<ul>
	<li><a href="https://www.baldurs-gate.de/index.php?resources/adalons-blood-silberdrachenblutmod.5/">Adalon's Blood</a> v1.4 or above</li>
	<li><a href="https://github.com/SpellholdStudios/Adrian_NPC">Adrian NPC</a> V5</li>
	<li><a href="https://www.dropbox.com/s/7obd7oopktkl5jv/BG1AerieV12.zip?dl=1">Aerie for BG:EE</a> v1.2 or above</li>
	<li><a href="https://github.com/Argent77/DjinniCompanion/releases/">Afaaq, the Djinni Companion</a> v2.2 or above</li>
	<li><a href="https://www.baldurs-gate.de/index.php?resources/jasteys-ajantis-bg1-expansion.2/">Ajantis BG1 Expansion</a> v17 or above</li>
	<li><a href="https://www.baldurs-gate.de/index.php?resources/jasteys-sir-ajantis-für-bgii-npc.9/">Sir Ajantis BG2</a> v20 or above</li>
	<li><a href="https://github.com/RoxanneSHS/AjocMod">Loron's Return (Ajoc's minimod restored)</a> v1.8 </li>
	<li><a href="https://www.dropbox.com/s/bw66infn2czuelv/MCAlcool.zip?dl=1">Alcool</a> v2 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/71473/playable-clara-all-things-mazzy-version-1-037/p1?new=1">All Things Mazzy</a> v2.21 or above</li>
	<li><a href="https://github.com/ShaktiExceso/arestorationp">Almateria's Restoration Project</a> v8.4 or above</li>
	<li><a href="https://www.dropbox.com/s/kt9u12x8qagq8lu/AloraEE.zip?dl=0">Alora NPC</a> v1.7</li>
	<li><a href="http://www.gibberlings3.net/alternatives/">Alternatives</a> v15 or above</li>
	<li><a href="https://github.com/MattyGroove/Amber/archive/master.zip">Amber NPC</a> v5.05 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/angelo/">Angelo NPC</a> v8</li>
	<li><a href="https://github.com/thisisulb/AnimalCompanions">Animal Companions</a> v1.3 or above</li>
	<li><a href="https://www.gibberlings3.net/files/file/687-anishai-one-day-npc/">Anishai One Day NPC</a> v2 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/quests/g3a/">Anniversary (G3 mini mod)</a> v9.1</li>
	<li><a href="https://github.com/RoxanneSHS/ArathEET">Arath NPC</a> v4.2</li>
	<li><a href="https://www.dropbox.com/s/v6et6uxv5tuyntp/ArcaneTreasury.zip?dl=0">Arcane Treasury</a> v1.5</li>
	<li><a href="https://github.com/RoxanneSHS/ArienaEE">Ariena the Half Orc</a> v3.0 or above</li>
	<li><a href="https://github.com/ArtemiusI/The-Artisan-s-Kitpack">Artisans Kitpack</a> v2</li>
	<li><a href="https://github.com/Gitjas/AC_QUEST/releases/latest">Ascalon's Questpack</a> v2.02 or above</li>
	<li><a href="https://github.com/InfinityMods/Ascension">Ascension</a> v2.0.8 or above</li>
	<li><a href="https://www.dropbox.com/s/drz9nmwzet8kylx/AsharNPC_v13.rar?dl=1">Ashar</a> v1.13</li>
	<li><a href="http://www.pocketplane.net/assassinations">Assassinations</a> v17</li>
	<li><a href="https://www.dropbox.com/s/hs3besqzichlru0/atweaks-v453.zip?dl=1">aTweaks</a> v4.53 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/auren/">Auren Aseph NPC</a> v11</li>
	<li><a href="https://github.com/RoxanneSHS/AzengaardEE">Azengaard</a> v7.1</li>
	<li><a href="http://www.pocketplane.net/brynnlaw">Back to Brynnlaw</a> v7</li>
	<li><a href="https://www.gibberlings3.net/forums/topic/27768-baldurs-gate-graphics-overhaul-for-eet/">Baldur's Gate Graphics Overhaul for EET</a> v beta 2.0 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/quests/bgqe/">Baldur's Gate Mini Quests and Encounters</a> v24 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/bg-romantic-encounters/">Baldur's Gate Romantic Encounters Modification</a> v7 or above</li>
	<li><a href="https://github.com/RoxanneSHS/Balduran-s-Sea-Tower">Balduran's Sea Tower</a> v1.2</li>
	<li><a href="https://www.dropbox.com/s/hje2hytqwq2lt4o/Bank_of_Baldurs_Gate_v0.2.zip?dl=0">Bank of Baldur's Gate</a></li>
	<li><a href="https://github.com/Argent77/A7-BanterAccelerator/releases">Banter Accelerator for Enhanced Edition games</a> v1.0 or later</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=com_content&task=blogcategory&id=95&Itemid=78">Banter Packs</a> v15 or above</li>
	<li><a href="http://github.com/ArtemiusI/Bardic-Wonders">Bardic-Wonders</a></li>
	<li><a href="https://github.com/thisisulb/BearWalkerKit">Bear Walker - a Werebear / Ranger Kit</a> v3.0 or above</li>
	<li><a href="http://www.baldursgatemods.com/forums/index.php?topic=8355.0">BG1 NPCs in SoA</a> v11 (it is better to use dedicated NPC mods if available for a specific NPC)</li>
	<li><a href="https://github.com/thisisulb/NoSoDSound">BG1 Sounds in SoD</a></li>
	<li><a href="https://github.com/AstroBryGuy/BGEESpawn">BGEE Leveled Spawns Mod</a> v0.4 or above</li>
	<li><a href="https://forums.bgforge.net/viewforum.php?f=31">BG Forge Tweaks and Tricks</a> V8 - (selected components only)</li>
	<li><a href="https://www.dropbox.com/s/gjj3dlc1k8muywv/BoM_V3EE.zip?dl=1">Boards o' Magick Item Pack</a> v3</li>
	<li><a href="https://github.com/Pocket-Plane-Group/Branwen_for_BGII/archive/refs/tags/v7.zip">Branwen SoA</a> v7</li>
	<li><a href="https://github.com/Gitjas/ACBre/releases/latest">Ascalon's Breagar</a> v7.0 or above (Note that the mod is not yet fully translated from German)</li>
	<li><a href="https://github.com/GwendolyneFreddy/butchery">BuTcHeRy</a> v4.0 or above</li>
	<li><a href="https://github.com/RoxanneSHS/CandlekeepMemories/">Candlekeep Memories</a></li>
	<li><a href="https://www.gibberlings3.net/mods/spells/celestials/">Celestials (P&P)</a> v7 or above (check for compatibility with other mods)</li>
	<li><a href="https://github.com/SpellholdStudios/CerndFriendship">Cernd Friendship</a> v1.2 or above</li>
	<li><a href="https://github.com/Argent77/A7-ChaosSorcerer">Chaos Sorcerer Kit</a> v1.0 or above</li>
	<li><a href="https://github.com/Raduziel/Charlatan-Kit/archive/master.zip">Charlatan (Bard Kit for PC or Eldoth)</a> v2.0 or above</li>
	<li><a href="https://github.com/AstroBryGuy/ChattyImoen">Chatty Imoen</a> v1.3 or above</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Check the Bodies</a></li>
	<li><a href="https://github.com/RoxanneSHS/ChloeEET">Chloe</a> v1.7 EE or above</li>
	<li><a href="https://www.gibberlings3.net/mods/other/cirerrek/">Cirerrek's AI Scripts aka eseries</a> v3</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Civil Disobedience</a></li>
	<li><a href="https://github.com/Gibberlings3/Continuous_NPC_Portraits">Continuous NPC Portraits</a> v1</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/coran/">Coran's BG Extended Friendship Talks</a> v5 or above</li>
	<li><a href="http://mods.pocketplane.net/kulyok/Coran_v6.zip">Coran for BG2</a> v6</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/corthala/">Corthala Romantique</a> v2 or above</li>
	<li><a href="https://github.com/RoxanneSHS/Corwin">Corwin NPC</a> v1.1 or above</li>
	<li><a href="https://github.com/Maltodaxtrin/CowledMenace">Cowled Menace</a> v0.2 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/crossmod/">Crossmod Banter Pack for Baldur's Gate II</a> v16</li>
	<li><a href="https://www.dropbox.com/s/gpxkd39wcqf6ew3/A7-Spellsword-v1.5.zip?dl=1">Custom Kits: The Spellsword</a> v1.4.1 or above</li>
	<li><a href="https://github.com/RoxanneSHS/DaceEET/archive/master.zip">Dace Linton NPC</a> (EET version)</li>
	<li><a href="https://github.com/RoxanneSHS/DarkHorizonsTweaks">Dark Horizons Tweaks</a> v1.0 or above (Balancing the Dark Horizons Mod)</li>	
	<li><a href="https://github.com/SpellholdStudios/DSotSC">Dark Side of the Sword Coast BGT/EET edition</a> (this is NOT the version released for BG:EE)</li>
	<li><a href="https://github.com/PaulaMigrate/NaliaEE">de'Arnise Romance</a> v6.2</li>
	<li><a href="https://github.com/RoxanneSHS/DeepgnomesEET">Deep Gnomes on the Sword Coast</a> v0.4 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/69241/kit-pack-deities-of-faerun-v-1-8-4-35-cleric-kits-for-iwd-bg-2-ee-and-eet">Deities Of Faerun (Cleric Kits)</a> v1.8.4 or above, experimental, requires manual installation</li>
	<li><a href="https://github.com/trinit2/Bg2Dorn/archive/master.zip">Dorn Romance (SoA+ToB)</a> v3.2 or above</li>
	<li><a href="https://github.com/thisisulb/DreamWalkerShamanKit">Dream Walker - a Shaman Kit</a> v1.2 or above</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Drow Library</a></li>
	<li><a href="https://forums.beamdog.com/discussion/62981/mod-druid-grove-makeover">Druid Grove Makeover</a> v1 or above</li>
	<li><a href="http://www.pocketplane.net/dc">Dungeon Crawl</a> v11</li>
	<li><a href="https://github.com/SpellholdStudios/Edwin_Romance">Edwin Romance</a> v2.10</li>
	<li><a href="https://github.com/EE-Mod-Setup/EET_Fixpack">EET Fixpack</a> v1, (interim fixes for EET, chapter changes)</li>	
	<li><a href="https://github.com/K4thos/EET_Tweaks/releases">EET Tweaks</a> v1.12 or above</li>
	<li><a href="https://github.com/RoxanneSHS/EET-Tweaks-and-Fixes">EETMoveItemsSoA</a> v1.0 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/60717/mod-eeuitweaks-mod-collection-all-ee-platforms">EEUITweaks User Interface Mods Collection</a> v1.5 or above (can be installed even after setup-EET_end)</li>
	<li><a href="https://github.com/RoxanneSHS/Ehlastra/">Ehlastra</a> v0.1</li>
	<li><a href="http://lavas-scriptorium.weebly.com/quests.html">Eilistraee's Song</a> v6.0 or above</li>
	<li><a href="https://github.com/Skitia/Emily-BG1">Emily</a> v1.59 or above</li>
	<li><a href="https://github.com/Gibberlings3/Enhanced-Powergaming-Scripts">Enhanced Powergaming Scripts</a> v5 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/74158/mod-epic-thieving-more-benefits-from-high-thieving-skills">Epic Thieving</a> v2.6 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/evandra/">Evandra</a> v1.0 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/quests/cliffette/">Every Mod and Dog (Mini-quests)</a> v11</li>
	<li><a href="https://github.com/RoxanneSHS/Magestronghold">Expanded Mage Stronghold</a> (tuned down and balanced extract from the abandoned Planar Sphere mod)</li>
	<li><a href="https://github.com/RoxanneSHS/EET_Expanded_Thief_Stronghold">Expanded Thief Stronghold</a> v2.3 or above</li>
	<li><a href="http://www.spellholdstudios.net/ie/fade">Fade</a> v5.2 or above</li>
	<li><a href="https://www.dropbox.com/s/7a0e5pwcz9i370w/Fadingpromises-master.zip?dl=1">Fading Promises</a> v8.1</li>
	<li><a href="https://github.com/UnearthedArcana/Faiths_and_Powers/releases">Faiths and Powers (kitpack and divine caster/spell tweaks)</a> v0.79 or above</li>
	<li><a href="https://www.dropbox.com/s/ad1hfx89v768h27/Faren_V4.zip?dl=1">Faren</a> v4.0</li>
	<li><a href="https://github.com/RoxanneSHS/Finch">Finch NPC mod</a> v5.3 or above</li>
	<li><a href="https://github.com/RoxanneSHS/FishingForTrouble">Fishing For Trouble</a> v3.2.8 or above</li>
	<li><a href="https://github.com/CrevsDaak/m7multikit">FlameWing's Multikit mod</a> v0.27.3</li>
	<li><a href="https://github.com/flamewing/m7tweaks/tree/master/m7tweaks">FlameWing's Tweaks</a> v1.1 master</li>
	<li><a href="http://lavas-scriptorium.weebly.com">Foundling: Between the Shades</a> v3 or above</li>
	<li><a href="https://www.dropbox.com/s/j88fh19lb2b0xyp/FR_ROV_V9.zip?dl=1">Freedom's Reign & Reign of Virtue</a> v9</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/gavin/">Gavin BG1 NPC</a> v12 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/gavin-bg2/">Gavin BG2 NPC</a> v22 or above</li>
	<li><a href="https://github.com/Argent77/A7-GolemConstruction">Golem Construction for Spellcasters</a> v2.0 or above</li>
	<li><a href="https://github.com/TotalMilk90/gorgon">Gorgon's Eye</a> v3.2 or above</li>
	<li><a href="https://github.com/RoxanneSHS/Gorion-s-Dream">Gorion's Dream Restored</a> v0.9</li>
	<li><a href="https://github.com/SpellholdStudios/HaerdalisFriendship">Haer'Dalis Friendship</a> v1.1</li>
	<li><a href="https://github.com/MattyGroove/haerdalisromance">Haer'Dalis Romance</a> v2.2</li>
	<li><a href="https://www.dropbox.com/s/uar6aljrv7yl1lj/HaerDalisSwords_v2.zip?dl=1">Haer'Dalis Swords</a> v2 or above</li>
	<li><a href="https://github.com/Gibberlings3/Haldamir">Haldamir NPC</a> v4</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Have Ice?</a></li>
	<li><a href="https://github.com/SpellholdStudios/HeartOfTheWood">Heart of the Wood</a> v7</li>
	<li><a href="https://github.com/Skitia/Helga-BG1">Helga</a> v1.48 or above</li>
	<li><a href="https://github.com/Austin-BG/HTaM">Heroes, Thieves and Moneylenders</a> v3.0 or above</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Holly the Elf</a></li>
	<li><a href="https://github.com/SpellholdStudios/Hubelpot_the_Vegetable_Merchant_NPC">Hubelpot NPC</a> v2.0 or above</li>
	<li><a href="https://github.com/Raduziel/I-Hate-Undead-Kitpack/archive/master.zip">I Hate Undead Kitpack</a> v2.4 or later</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">I Shall Never Forget</a> v5.2 or above</li>
	<li><a href="https://github.com/SpellholdStudios/IEP_Extended_Banter">IEP Extended Banters</a> v5.4</li>
	<li><a href="https://github.com/RoxanneSHS/ImnesvaleEE">Imnesvale Invasion</a> v2</li>
	<li><a href="https://github.com/SpellholdStudios/ImoenFriendship">Imoen Friendship</a> v3.4 or above</li>
	<li><a href="http://imoen.blindmonkey.org/">Imoen Romance</a> v3.9 or above (updated recently, may need some testing)</li>
	<li><a href="https://github.com/Argent77/A7-ImprovedArcher">Improved Archer Kit</a> v2.2 or above</li>
	<li><a href="https://github.com/RoxanneSHS/Asylum">Improved Asylum</a> v201 or above</li>
	<li><a href="https://github.com/Argent77/A7-ImprovedShamanicDance">Improved Shamanic Dance</a> v4.2 or above</li>
	<li><a href="https://www.dropbox.com/s/vrplwuj5gz0cahu/ThOghma_v1.8.zip?dl=1">In Oghma's Service</a> v1.8</li>
	<li><a href="https://github.com/RoxanneSHS/Indira">Indira NPC</a> v13 or above</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">Innershade</a> v9.0 or above</li>
	<li><a href="https://github.com/RoxanneSHS/IronmodsEET">Iron Modders Collection</a> v1.2 or above</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">Isandir's Portrait Pack</a> v1.3 or above</li>
	<li><a href="https://github.com/SpellholdStudios/Isra_NPC_BG2">Isra BG2</a> v3</li>
	<li><a href="https://www.gibberlings3.net/forums/topic/25430-version-7-dev-release/">Item Randomiser</a> v7 or above</li>
	<li><a href="https://github.com/Gibberlings3/ItemRevisions">Item Revisions</a> v4 Beta or above (Caution: makes short bows and axes unuseable for Shamans)</li>
	<li><a href="https://www.gibberlings3.net/mods/spells/iwdification/">IWDification</a> vBeta3</li>
	<li><a href="https://github.com/RoxanneSHS/IylosEET">Iylos NPC for ToB</a> (EET version)</li>
	<li><a href="https://github.com/AstroBryGuy/JaheiraRecast">Jaheira Recast</a> v2.0 or above</li>
	<li><a href="https://github.com/SpellholdStudios/JansAlchemy/">Jan's Alchemy</a> v8.1 or above</li>
	<li><a href="http://akadis.baldursgateworld.fr/Jan/JansQuestEn.html">Jan's Extended Quest</a> v1.5 or above</li>
	<li><a href="http://forums.blackwyrmlair.net/index.php?showtopic=5365">Jini Romance</a> v3.0 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/18607/jkits-v7-kenshei-undead-eliminator-amazon-3-20-18">JKits (Kenshei, Undead Eliminator, Amazon)</a> v7 or above</li>
	<li><a href="https://github.com/Skitia/Kale-BG1">Kale</a> v1.6 or above</li>
	<li><a href="https://github.com/CrevsDaak/7C-Yoshi">Keeping Yoshimo</a> v0.98</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/keldorn/">Keldorn Romance</a> v1.0 or above</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=content&task=blogcategory&id=81&Itemid=66">Kelsey NPC</a> v5</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=com_content&task=blogcategory&id=140&Itemid=107">Keto NPC</a> v5</li>
	<li><a href="https://github.com/RoxanneSHS/EET-Tweaks-and-Fixes">Keyring</a> (formerly "mod for the orderly")</li>
	<li><a href="https://github.com/RoxanneSHS/KidoEE">Kido the Jester NPC</a> V8.0 or above</li>
	<li><a href="https://github.com/RoxanneSHS/Kim_Pirate">Kim the Pirate</a> v2.0</li>
	<li><a href="https://www.dropbox.com/s/vrs3nf6dzumujyu/Kindrek_V28.zip?dl=1">Kindrek</a> V2</li>
	<li><a href="https://github.com/PaulaMigrate/Kitanya-Resurrected">Kitanya NPC</a> V7.0 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/kivan/">Kivan and Deheriana Companions for BG2</a> v16</li>
	<li><a href="https://github.com/SpellholdStudios/KorganFriendship">Korgan Friendship</a> V1.4 or above</li>	
	<li><a href="https://forums.beamdog.com/discussion/61571/mod-lefreuts-enhanced-ui-for-bg1ee-bg1ee-sod-bg2ee-and-eet/p1">Lefreut's enhanced UI</a> v4.41 or above (can be installed even after setup-EET_end) Note: requires game version 2.6</li>
	<li><a href="https://forums.beamdog.com/discussion/66353/mod-lefreuts-enhanced-ui-sod-skin-for-bg1ee-sod-bg2ee-and-eet">Lefreut's enhanced UI SoD Skin design</a> v4.41 or above (can be installed even after setup-EET_end) Note: requires game version 2.6</li>
	<li><a href="https://github.com/r-e-d/LeUI-BG1EE">Lefreut's enhanced UI BG1 Skin design</a> v4.41 or above (can be installed even after setup-EET_end) Note: requires game version 2.6</li>
	<li><a href="https://www.gibberlings3.net/forums/topic/25048-new-bg2-npc-lena/">Lena, tiefling NPC</a> v0.8 or above</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Liberation of Hlondeth</a></li>
	<li><a href="https://github.com/Argent77/A7-LightingPackEE">Lighting Pack: Shader Scripts for the Enhanced Edition</a> v2.3 or above</li>
	<li><a href="https://github.com/RoxanneSHS/EET-Tweaks-and-Fixes">Limited Resting</a></li>
	<li><a href="https://github.com/RoxanneSHS/LongerRoadEE">Longer Road EE</a> v1.9 or above</li>
	<li><a href="https://github.com/Gibberlings3/Lore_From_Learning">Lore From Learning</a> v3 or above</li>
	<li><a href="https://www.dropbox.com/s/clpqqtr5jskv5er/Lucy4.1.zip?dl=1">Lucy the Wyvern</a> v4.1 or above</li>
	<li><a href="https://www.gibberlings3.net/forums/topic/29992-my-new-made-in-heaven-mods/">Made In Heaven Item Pack</a> v1</li>
	<li><a href="https://github.com/subtledoctor/mana_sorcerer">Mana Sorcerer</a> v0.2 or above</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Master Vampire</a></li>
	<li><a href="https://github.com/SpellholdStudios/MazzyFriendship">Mazzy Friendship</a> v3.3</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Melynda the Mute</a></li>
	<li><a href="https://github.com/Raduziel/Mercenary-Kit/archive/master.zip">Mercenary (Fighter Kit for PC or Kagain)</a> v2.4 or above</li>
	<li><a href="https://github.com/UnearthedArcana/Might_and_Guile/releases">Might and Guile (a tweak mod and kit pack for warriors and rogues)</a> v2.1 or above</li>
	<li><a href="https://github.com/Raduziel/MilitiaOfficer-Kit.git">Militia Officer (Kit for PC or Khalid)</a> v1.3 or above</li>
	<li><a href="https://github.com/SpellholdStudios/MinscFriendship">Minsc Friendship</a></li>
	<li><a href="http://forums.beamdog.com/discussion/18108/item-mod-more-style-for-mages-ranged-wizards-staffs-circlets-robe-visual-tweaks-now-in-iwd-ee">More Styles for Mages</a> v1.55 or above</li>
	<li><a href="https://github.com/CrevsDaak/m7multikit">Multiclassed Multikit Builder Mod</a> v0.27.3 or above</li>
	<li><a href="https://github.com/RoxanneSHS/Murneth">Mur'Neth NPC mod</a> v14 or above</li>
	<li><a href="http://github.com/ArtemiusI/Mystic-Fire">Mystic Fire Paladin Kit</a></li>
	<li><a href="https://www.dropbox.com/s/cbs4de7mespuge4/Nathaniel_V5.zip?dl=1">Nathaniel</a> v5</li>
	<li><a href="https://github.com/AstroBryGuy/NeeraBanters">Neera Banters (BG:EE)</a> v0.9 or above</li>
	<li><a href="https://github.com/SpellholdStudios/Neera_Expansion/tree/v1.3.0">Neera Expansion</a> v1.3 or above</li>
	<li><a href="https://github.com/SpellholdStudios/Nephele_NPC">Nephele NPC</a> v2.6</li>
	<li><a href="https://www.dropbox.com/s/lnwu2b90ymdp6ro/Nehtaniel_V7.zip?dl=1">Neh'taniel</a> v7</li>
	<li><a href="http://athkatla.cob-bg.pl/download.php?id=1595">New travel system between Baldur's Gate City areas</a> v2.1 or above</li>
	<li><a href="https://github.com/RoxanneSHS/NindeEET">Ninde Amblecrown</a> (EET version)</li>
	<li><a href="https://www.dropbox.com/s/whwctp4ussj87an/EENinja.zip?dl=1">Ninja Kit</a> v1.1</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=com_content&task=blogcategory&id=104&Itemid=81">NPC Flirt Packs</a> v1.04 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/tweaks/npckit/">NPC Kitpack</a> v5</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/glam-npc-pack/">NPC Pack (Glam's NPCs)</a> v1.0 or above</li>
	<li><a href="https://www.dropbox.com/s/sugrp1m42yda24f/NPCStrongholds_V15.zip?dl=1">NPC Strongholds</a> v15</li>
	<li><a href="https://www.gibberlings3.net/mods/tweaks/npctweak/">NPC Tweak</a> v6</li>
	<li><a href="https://github.com/subtledoctor/NPC_EE/releases">NPC_EE</a> v2.3 or above</li>
	<li><a href="https://github.com/thisisulb/NoSoDSound">NPCs keep BG1 sound sets during SoD</a> v1 or above</li>
	<li><a href="https://github.com/SpellholdStudios/NTotSC/releases/latest">NTotSC v2.1</a></li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Of Elves and Artefacts</a></li>
	<li><a href="https://github.com/OlvynChuru/METweaks/">Olvyn Tweaks</a>v1.2 or above</li>
	<li><a href="https://www.dropbox.com/s/39t9vthot7530ni/OreliosNPC.zip?dl=0">Orelios NPC</a> v2.0</li>
	<li><a href="https://github.com/ArtemiusI/Pai-Na-NPC-mod-for-BG2-EE/releases">Pai'Na NPC for BG2:EE</a> v1.2 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/76592/mod-paintbg-ee-portrait-pack">PaintBG for BG:EE</a> v2.1</li>
	<li><a href="https://github.com/K4thos/Portraits-Portraits-Everywhere/archive/master.zip">Portraits Portraits Everywhere</a> v1.01 or above</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=com_content&task=blogcategory&id=128&Itemid=100">Quest Pack</a> v3.3</li>
	<li><a href="https://github.com/Argent77/A7-recoloredbuttons">Recolored toolbar buttons for BG:EE & BG2:EE</a> v4.1 or above</li>
	<li><a href="https://github.com/Skitia/Recorder-BG1">Recorder</a> v1.36 or above</li>
	<li><a href="https://github.com/UnearthedArcana/refinements">Refinements</a> v4.24</li>
	<li><a href="https://github.com/RoxanneSHS/RoT">Region of Terror</a> v5.05 or above (EET Version)</li>
	<li><a href="https://github.com/Raduziel/Relieve-Wizard-Slayer/archive/master.zip">Relieve Wizard Slayer</a> (must be installed after Wizard Slayer Rebalancing)</li>	
	<li><a href="https://www.dropbox.com/s/mogovd9x99niham/RestoreSound_V1.zip?dl=1">Restore Original Casting Sounds</a> v1</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=com_content&task=blogcategory&id=189&Itemid=127">Reunion</a> V4 or above)</li>
	<li><a href="https://github.com/Argent77/A7-HiddenGameplayOptions/releases">Reveal Hidden Gameplay Options</a> v1.0 or above</li>
	<li><a href="https://www.dropbox.com/s/8irrveuglmlxjkf/RGenie_30.zip?dl=1">Ribald's Genie</a> v3.0 or above</li>
	<li><a href="https://github.com/FredrikLindgren/rr">Rogue Rebalancing</a> v4.91 or above</li>
	<li><a href="https://github.com/SpellholdStudios/Rolles">Rolles Safyer</a> v5 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/romantic-encounters/">Romantic Encounters for BGII</a> v12 or above</li>
	<li><a href="https://github.com/RoxanneSHS/RoseRE">Rose NPC resurrected</a> v07</li>
	<li><a href="=https://github.com/RoxanneSHS/RuadEE">Ruad the Blacksmith</a> v30</li>
	<li><a href="https://github.com/MarkVadasz/Rupert">Rupert the Dye Merchant</a> v2.2A</li>	
	<li><a href="https://github.com/PaulaMigrate/Saerileth">Saerileth NPC</a> V20</li>
	<li><a href="https://github.com/RoxanneSHS/SafanaBG2">Safana in Amn</a> v0.4</li>
	<li><a href="https://github.com/RoxanneSHS/SandrahEET">Sandrah Saga</a> v2.05 (requires BP-BGT Worldmap), The Saga is composed of three parts: <a href="https://github.com/RoxanneSHS/SandrahEET">Sandrah Appears</a>, <a href="https://github.com/RoxanneSHS/SandrahRtF">Sandrah Return to Faerun</a>, and  <a href="https://github.com/RoxanneSHS/SandrahToT">Sandrah Time of Troubles Revisited</a>.</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/sarah/">Sarah NPC</a> v6</li>
	<li><a href="https://github.com/SpellholdStudios/SarevokFriendship>">Sarevok Friendship</a> v2.5</li>
	<li><a href="https://www.dropbox.com/s/pifofoz21t15zph/Sarevok%20Romance%20v1.4.zip?dl=0">Sarevok Romance</a> v1.3</li>
	<li><a href="https://www.dropbox.com/s/ryw4tn3r1vuohkn/7c%23sartweak_v1.2.zip?dl=0">Sarevok related tweaks</a> v1.2 or above</li>
	<li><a href="https://github.com/subtledoctor/Scales_of_Balance/releases">Scales of Balance</a> v5.1 or above, use with caution  </li>
	<li><a href="https://github.com/subtledoctor/d5_Random_Tweaks">SD's Random Tweaks</a> v1.1 or above</li>
	<li><a href="https://github.com/RoxanneSHS/BoneHill">Secret of Bone Hill</a> v33</li>
	<li><a href="https://github.com/ArtemiusI/Shadow-Magic/archive/master.zip">Shadow Magic</a> v1.85 or later</li>
	<li><a href="https://github.com/RoxanneSHS/SoS-EE">Shadows Over Soubar</a> v3 or later</li>
	<li><a href="https://www.gibberlings3.net/mods/other/shards/">Shards Of Ice</a> v6</li>
	<li><a href="https://github.com/RoxanneSHS/SheenaHD">Sheena the Half Dragon</a> v3.1</li>
	<li><a href="https://github.com/RoxanneSHS/Caelar">Shine On Caelar</a> v1.3</li>
	<li><a href="https://www.dropbox.com/s/ut17uf5rt27m7en/Silverstar.zip?dl=0">Silver Star</a> v2.0</li>
	<li><a href="https://github.com/RoxanneSHS/Sime">Sime</a> v0.4</li>
	<li><a href="https://forums.beamdog.com/discussion/62163/npc-mod-sirene-npc-for-bg2-ee-v1-3-eet-compatibility-added/p1">Sirene NPC for BG2:EE</a> v1.3 or later (should have full continuity if BG:EE version is present)</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">Skie - The Cost of One Girl's Soul</a> v1.2 or above (The mod may not be compatible (story-wise) with other mods that add Soultaker and/or Skie plots)</li>
	<li><a href="https://skitias-stories.com">SkitiaNPCs</a> continues some mod NPCs in Amn</li>
	<li><a href="http://www.shsforums.net/topic/24421-the-slithering-menace-tob-only-v400/">Slithering Menace</a> v4.0</li>
	<li><a href="https://github.com/RoxanneSHS/SoDBanterEET">SoD Banter Restauration</a> v0.6 or above</li>
	<li><a href="https://github.com/Gibberlings3/SoD-to-BG2EE-Item-Upgrade">SoD to SoA Item Upgrade</a> v1.0.1 or above</li>
	<li><a href="https://github.com/RoxanneSHS/Solaufein">Solaufein NPC + Romance</a> v2.04 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/kits/sns/">Song and Silence</a> v8 or above</li>
	<li><a href="https://github.com/D2-mods/D2-WEAPON">Souls-inspired Weapon Pack</a> v1.0 or above</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">Southern Edge</a> v1.0 or above</li>
	<li><a href="https://github.com/RoxanneSHS/SpeakDead/">Speak to the Dead</a></li>
	<li><a href="https://github.com/Gibberlings3/SpellRevisions">Spell Revisions</a> vBeta or above</li>
	<li><a href="https://github.com/thisisulb/SpiritHunterShamanKit">Spirit Hunter - a Shaman Kit</a> v0.3 or above</li>
	<li><a href="https://github.com/thisisulb/SpiritwalkerKit">Spirit Walker - a Shaman Kit</a> v1.3 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/29604/mod-spontaneous-casting-for-clerics-and-druids-v1-32/p1">Spontaneous Casting For Clerics and Druids</a> v1.3 or above</li>
	<li><a href="https://github.com/thisisulb/StormCallerKit">Storm Caller - a Shaman Kit</a> v3.0 or above</li>
	<li><a href="https://www.dropbox.com/s/a9c1l5b9mdy86cw/subrace_mod.zip?dl=1">Subraces</a> v0.2 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/kits/swordandfist/">Sword and Fist</a> (Monk kits) v8 or above</li>
	<li><a href="https://github.com/Gibberlings3/SwordCoastStratagems/releases">Sword Coast Stratagems</a> v34 or above</li>
	<li><a href="https://github.com/RoxanneSHS/ToA">Tales of Anegh</a> v3.1 or above</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">Tales of the Deep Gardens</a> v12 or above</li>
	<li><a href="https://github.com/RoxanneSHS/TashiaEE">Tashia</a> v1.6 or above</li>
	<li><a href="https://www.dropbox.com/s/htby4vqo0bgwphk/TeamBGAeWe.zip?dl=0">TeamBG's Armours and Weapons for EET</a> </li>
	<li><a href="https://github.com/RoxanneSHS/Tenya">Tenya Thermidor</a> v2.2 or above</li>
	<li><a href="https://github.com/Argent77/A7-TestYourMettle/releases">Test Your Mettle!</a> v0.1-beta or above</li>
	<li><a href="https://github.com/CrevsDaak/thalan">Thalantyr - Item Upgrade</a> v4.2.1 or above</li>
	<li><a href="https://www.gibberlings3.net/forums/topic/30074-g3-the-beaurin-legacy-v30-now-available/">The Beaurin Legacy</a> v4.0 or above (Needs Install Tool fixes for EET)</li>
	<li><a href="https://github.com/RoxanneSHS/LensHunt">The Broken Lanthorn</a> </li>
	<li><a href="https://www.gibberlings3.net/mods/quests/thecalling/">The Calling</a> IMPORTANT install after SCS or Tweaks Anthology but prior Sandrah, this way all mods automatically skip redundant components.</li>
	<li><a href="https://github.com/RoxanneSHS/TDDz">The Darkest Day EE edition (TDDz)</a> v1.2.9 or above (please refer to the TDDz readme - this mod needs external resources from <a href="https://github.com/EE-Mod-Setup/TDD/archive/V1.14.zip">original TDD</a>)</li>
	<li><a href="https://github.com/K4thos/TGC1e">The Grey Clan Episode I: In Candlelight</a> v1.9 beta or above</li>
	<li><a href="https://www.dropbox.com/s/dcs9dgiy0vcvgby/TheHorde_1.2.zip?dl=1">The Horde</a> v1.2 beta or above NOTE requires java to install the mod</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=com_content&task=blogcategory&id=134&Itemid=94">The Lure of the Sirine's Call</a> v15 or above</li>
	<li><a href="https://www.dropbox.com/s/hh1buau5xpz3kat/slandor.1.6.zip?dl=1">The Minotaur and Lilacor</a> v1.6</li>
	<li><a href="http://www.pocketplane.net/sellswords">The Sellswords</a> v7</li>
	<li><a href="https://github.com/RoxanneSHS/Tamoko">The Sword of Chaos (Tamoko mod)</a> v0.7 or above</li>
	<li><a href="https://github.com/SpellholdStudios/TheSwordofNoober">The Sword of Noober</a> v2 or above</li>
	<li><a href="https://github.com/RoxanneSHS/VaultEE/">The Vault EE</a> v7.3 or above</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">The White Queen</a> v6.0 or above</li>
	<li><a href="https://github.com/Sampsca/ThrownHammers/releases">ThrownHammers</a> v6.0.1 or above</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=content&task=blogcategory&id=113&Itemid=84">Tiax for BG2</a> v5</li>
	<li><a href="http://lynxlynx.info/ie/modhub.php?aquadrizzt/TomeAndBlood">Tome and Blood</a> v0.9 or above</li>	
	<li><a href="https://github.com/RoxanneSHS/TowerOfDeception">Tower of Deception</a> v5.0.1 or above</li>
	<li><a href="https://www.dropbox.com/s/eolau4r9cq60jjn/Touchstone.zip?dl=1">Touchstone NPC</a> v2.0</li>
	<li><a href="https://forums.beamdog.com/discussion/73701/mod-trials-of-the-luremaster-for-bg2-ee-announcement">Trials of the Luremaster</a> v1.0 or above</li>
	<li><a href="https://github.com/RoxanneSHS/Travellers">Travellers in Faerun</a> v0.8 or above </li>
	<li><a href="https://github.com/RoxanneSHS/Tsujatha">Tsujatha</a> v17 or above </li>
	<li><a href="https://github.com/RoxanneSHS/The-Rune">Twisting with the Rune</a> </li>
	<li><a href="http://mods.pocketplane.net/TurnaboutV13EE.zip">Turnabout</a> v1.3 (Requires Ascension mod)</li>
	<li><a href="https://www.gibberlings3.net/mods/tweaks/tweaks/">Tweaks Anthology</a> v8</li>
	<li><a href="https://github.com/RoxanneSHS/TyrisEE">Tyris Flare</a> v10.2</li>
	<li><a href="https://www.dropbox.com/s/lu3ymv2j8l1w2dh/UldarNPC.zip?dl=0">Uldar the Babarian</a> v1.0</li>
	<li><a href="http://forums.blackwyrmlair.net/index.php?showtopic=3074">Ulrien Of Cormyr, Saga Master</a> v1.0</li>
	<li><a href="https://www.gibberlings3.net/forums/topic/29667-release-candidate-for-unfinished-business-v27/">Unfinished Business</a> v27 RC1</li>
	<li><a href="https://www.dropbox.com/s/5g43s13138wkpgc/Demon%20Summon%20Ritual_v7.zip?dl=1">Unholy Gate Opening Ritual Book</a> v7</li>
	<li><a href="https://github.com/BGforgeNet/bg2-uniqueartifacts">Unique Artifacts</a> v7</li>
	<li><a href="https://github.com/Raduziel/Raduziels-Universal-Wizard-Spells/archive/master.zip">Universal Wizard Spells</a> v2.5 or later</li>
	<li><a href="https://forums.beamdog.com/discussion/56567/mod-bgii-ee-unofficial-item-pack">Unofficial Item Pack</a> v2.7b CAUTION: do not install "SoD items import" component in EET to avoid duplication!</li>
	<li><a href="https://github.com/RoxanneSHS/ValenEE">Valen NPC</a> v52</li>
	<li><a href="https://github.com/SpellholdStudios/ValygarFriendship">Valygar Friendship</a> v1.4</li>
	<li><a href="https://github.com/RoxanneSHS/Miriam">Vampire Tales (Miriam NPC)</a> v2.0</li>
	<li><a href="http://www.shsforums.net/files/file/1195-vampire-world-for-eet/">Vampire World</a> v0.42 or above CAUTION mod is still experimental according to author</li>
	<li><a href="https://github.com/RoxanneSHS/CtB-EE-Modules">Velvetfoot</a></li>
	<li><a href="https://github.com/SpellholdStudios/ViconiaFriendship">Viconia Friendship</a> v4.4</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">Viconia Revamped</a> v6.0</li>
	<li><a href="https://github.com/Skitia/Vienxay-BG1">Vienxay</a> v1.57 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/vynd/">Vynd NPC Mod (stand-alone)</a> v2 (also included in NPC Pack for Baldur's Gate Enhanced Edition)</li>
	<li><a href="https://forums.beamdog.com/discussion/69177/v0-1-warlock-mod">Warlock kit</a></li>
	<li><a href="https://forums.beamdog.com/discussion/64119/kit-rework-way-of-the-assassin-v1-1">Way of the Assassin</a></li>
	<li><a href="https://github.com/Gibberlings3/Item_Upgrade/releases">Weimer's Item Upgrade</a> v42 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/quests/wheels/">Wheels of Prophecy</a> v6 or above</li>
	<li><a href="http://lavas-scriptorium.weebly.com">Will of the Wisps</a> v1.2 or above</li>
	<li><a href="https://www.dropbox.com/s/4dqo1xl6bhhrq8j/Wings_EET.zip?dl=1">Wings (for Aerie)</a> v0.94 or above</li>
	<li><a href="https://www.dropbox.com/s/pt2gpnqi8dmp4ux/wsr_v114.zip?dl=1">Wizard Slayer Rebalancing</a> v1.14</li>
	<li><a href="https://github.com/SpellholdStudios/BP-BGT-Worldmap/archive/v10.2.4.zip">Worldmap</a> v10.2.4</li>
	<li><a href="https://github.com/flamewing/WTPFamiliars">WTP Familiars</a> v2.2</li>
	<li><a href="http://www.pocketplane.net/mambo/index.php?option=content&task=blogcategory&id=134&Itemid=94">Xan's friendship path</a> v10 or above</li>
	<li><a href="http://www.pocketplane.net/xan">Xan BG2/ToB</a> v17 or above</li>
	<li><a href="https://github.com/RoxanneSHS/XulayeEet">Xulaye NPC</a> v2.2 or above</li>
	<li><a href="https://github.com/RoxanneSHS/YasraenaEET">Yasraena</a> v19</li>
	<li><a href="https://www.dropbox.com/s/8aytola4gat6ac7/Yeslick%20BG2%20v2.0.zip?dl=1">Yeslick SoA/ToB</a> v2.0 or above</li>	
	<li><a href="https://github.com/SpellholdStudios/YoshimoFriendship">Yoshimo Friendship</a> v4.4 or above</li>
	<li><a href="https://www.gibberlings3.net/mods/npcs/yoshimos-remorse/">Yoshimo's Remorse</a> v1.3 or above</li>
	<li><a href="https://forums.beamdog.com/discussion/65500/mod-yoshimo-romance">Yoshimo Romance</a> v4.0 or above</li>
	<li><a href="http://lavas-scriptorium.weebly.com/">Yvette Romance</a> v4.0 or above</li>
</ul>
</div>

<!--
	
</ul>
</div>

</body>
</html>
