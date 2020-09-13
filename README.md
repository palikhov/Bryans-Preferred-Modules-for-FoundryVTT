

<!-- + Bryan's Preferred FoundryVTT Modules + -->

<img src="https://raw.githubusercontent.com/bryancasler/Bryans-Preferred-Modules-For-FoundryVTT/master/assets/Bryan's%20Preferred%20Modules%20for%20Foundry%20VTT%20-%20Full%20-%20Social%20-%20On%20Dark.png" width="0" height="0">

![Bryan's Preferred FoundryVTT Modules](https://raw.githubusercontent.com/bryancasler/Bryans-Preferred-Modules-For-FoundryVTT/master/assets/Bryan's%20Preferred%20Modules%20for%20Foundry%20VTT%20-%20Title%20-%20On%20White.png)

My personally cultivated list of FoundryVTT Modules that play nicely together without creating an overwhelming amount of UI options or causing noticeable FPS drops; not everyone has a new computer. Collectively they set up a solid foundation for any D&D 5e and Pathfinder 2e campaign.

# Video Walkthrough
This walkthrough shows the initial set up for creating a D&D 5e world. On FoundryVTT, the modules have already been added and it starts with us creating a new world and enabling the desired modules and then configuring them.

- [D&D 5e FoundryVTT Set Up Walkthrough](https://d.pr/v/lwg9Xk) - There is no sound, play your own music :)
  - 00:00 - 05:00 - Enabling and Configuring Modules

# Preferred FoundryVTT Modules

## Quality of Life Improvements For Everyone
- [Autocomplete Whisper](https://foundryvtt.com/packages/autocomplete-whisper/) - Foundry VTT module to enhance chat whisper targeting with typeahead suggestions and popup menu of available targets.
- [Chat Portrait](https://foundryvtt.com/packages/ChatPortrait/) - Show Actor’s portrait in chat.
  - Game Settings (Tab) > Module Settings > Chat Portrait > Portrait Border Shape > Change to "Circle"
  - Game Settings (Tab) > Module Settings > Chat Portrait > Use Token Image: Checked
- [Combat Ready!](https://github.com/smilligan93/combatready) - Shows a graphic + sound for players a round just before a player's turn (Next Up) and during their turn.
  - Configure Settings (tab) > Module Settings > Disable ‘Next Up’ notification: Unchecked
  - Configure Settings (tab) > Module Settings > Disable Timer: Checked
  - Configure Settings (tab) > Module Settings > Show End Turn Dialog: Checked
  - Configure Settings (tab) > Module Settings > Ticking Sound: Unchecked
- [Cursor Zoom](https://foundryvtt.com/packages/cursor-zoom/) - Mouse scroll zooming will center around the cursor instead of around the center of the screen.
- [Custom CSS](https://foundryvtt.com/packages/custom-css/) - OPTIONAL: Allows a user to setup custom CSS rules in a world.
  - My [custom.css](https://github.com/bryancasler/Bryans-Preferred-Modules-for-FoundryVTT/blob/master/custom.css) is part of this repo.
- [Deselection](https://github.com/Sky-Captain-13/foundry/tree/master/deselection) - Allows you to deselect a token or tokens by clicking any empty spot on the map.
- [Dice So Nice](https://gitlab.com/riccisi/foundryvtt-dice-so-nice) - Adds the ability to show a 3D dice simulation when a roll is made.
  - Configure Settings (tab) > Module Settings > Hide FX: None
  - Configure Settings (tab) > Module Settings > Sound Effects: Unchecked
  - Configure Settings (tab) > Module Settings > Shadows Quality: None
  - Configure Settings (tab) > Module Settings > Advanced Lighting: Unchecked
- [Illandril's Chat Enhancements](https://foundryvtt.com/packages/illandril-chat-enhancements/) - Enhances the chat by showing player names in IC messages, replacing actor names with token names, and showing who you are currently speaking as. It also simulates hovering over a token when hovering over a chat message associated with a token.
- [Polyglot](https://foundryvtt.com/packages/polyglot/) - Talk to others using a language your selected character can understand and scrambles in-character text you can't understand. - Suggested by jniezink on the FoundryVTT Subreddit
- [One Journal](https://foundryvtt.com/packages/one-journal/) - Provides a unified view for authoring journals
   - Configure Settings (tab) > Module Settings > Button in journal directory: Checked
- [Quick Insert](https://foundryvtt.com/packages/quick-insert) - Quick Insert (control + space) provides a context-aware search/autocomplete tool that can be used
in most parts of FoundryVTT. Find actors, items, spells etc. and insert them wherever you need them right now - the map, character sheets, roll tables, journals, you name it. - Suggested by LorduFreeman on The Foundry Discord
- [Show Drag Distance](https://github.com/wsaunders1014/showdragdistance) - Shows distance you've dragged the token as if you used the Ruler tool.
  - Currently has an annoying bug where when a token is dragged through a wall an error is shown after the token is dropped. The error disappears but the drag distance indicator does not until you drag the token a second time.
  - [Show Notes](https://github.com/shawndibble/foundryvtt-show-notes) - Automatically flag journal notes to show on the map without having to have your players turn it on themselves.
- [Token Action HUD](https://github.com/espositos/fvtt-tokenactionhud) - Floating HUD, showing common actions for a controllable token.

## Quality of Life Improvements For GameMasters
- [Adventure Importer / Exporter](https://foundryvtt.com/packages/adventure-import-export/) - OPTIONAL: Allows content creators to package multiple assets within Foundy VTT into a single distributable file that can be shared.
- [Actually Private Rolls](https://github.com/syl3r86/Actually-Private-Rolls) - Hides Private GM Rolls completely rather than just obfuscating the result. This can be toggled on or off in the Settings Menu.
- [Background Volume](https://github.com/mtvjr/background-volume) - Allows the DM to configure the volume of a scene's background
- [Combat Enhancements](https://gitlab.com/asacolips-projects/foundry-mods/combat-enhancements) - Improved initiatives tab with health tracking and drag and drop reordering.
- [VTT FPS Meter](https://github.com/ardittristan/VTTFPSMeter) - OPTIONAL: Adds an FPS meter, used for testing and performance debugging.
  - There is also [FPS Meter](https://foundryvtt.com/packages/fpsmeter/) which is similar.
- [GM Notes](https://foundryvtt.com/packages/gm-notes/) - Add GM-Only notes to entities (Actor, Items (including owned items), RollTable, and JournalEntry).
- [GM Token-Drag Visibility](https://github.com/SteffanPoulsen/token-drag-visibility) - Module that disables the vision limitation when dragging a token as a GM. Useful for moving players between floors on the same map.
- [Laptop Form Fix](https://foundryvtt.com/packages/laptop-fix/) - Fixes issues where the some Form Applications put the submit button off screen.
- [Lock View](https://github.com/CDeenen/LockView) - IN PERSON ONLY: Makes playing using a digital playmat, such as a horizontally mounted TV, easier.
- [Music Assistant](https://github.com/temportalflux/MusicAssist) ([module.json](https://raw.githubusercontent.com/temportalflux/MusicAssist/master/module.json))- Adds support for youtube tracks in audio playlists.
  - Note: I've had issues with music not playing and having to stop/start tracks. Still worth it.
- [QuickSceneView](https://gitlab.com/reichler/quicksceneview) Foundry VTT module that adds a Scene Directory context menu to directly view a scene. - Suggested by jniezink on the FoundryVTT Subreddit
- [Token Info Icons](https://github.com/jopeek/fvtt-token-info-icons) - Displays Speed, AC, and Passive Perception on Tokens for the GM.
- [Virtual Tabletop Assets - Tokenizer](https://www.vttassets.com/assets/vtta-tokenizer) - A tool to help generate token “token” images and their avatars.
  - NOTE: If you try to edit an actor who is in already placed in a scene, it will edit their Compendium entry but not the version of them already placed into the scene.

## Dungeon and Dragons 5e (D&D 5e) Specific
- [Darker Vision for 5e](https://foundryvtt.com/packages/darker-vision-for-5e/) - Adjust's Foundry's handling of Darker Vision to match D&D 5e's rules as written. - Suggested by LorduFreeman on The Foundry Discord
- [Not Enough NPCs](https://github.com/ardittristan/VTTNPCGen) - NPC Generator
- [Tidy 5e Sheet](https://github.com/sdenec/tidy5e-sheet) - D&D 5e Only. An alternative Character Sheet
- [Torch](https://foundryvtt.com/packages/torch/) - Adds a HUD button to toggle light of a specific radius.
  - Configure Settings (tab) > Module Settings > GM Uses Inventory
  
## Pathfinder 2e (P2E) Specific
- [Pathfinder 2e Quick Rolls](https://gitlab.com/mcarthur.alford/pf2qr) - Adds features to speed up rolling in chat.
- [Pathfinder Ui](https://gitlab.com/sasmira/pathfinder-ui) - Theme for Pathfinder 1e and 2e.
- [PF2e GM Screen](https://gitlab.com/atakanaltiner6/pf2e-gm-screen/) - A GM Screen for PF2e Game System.
- [Virtual Tabletop Assets - Iconizer](https://www.vttassets.com/assets/vtta-iconizer) - Whenever an item is created or updated, Iconizer looks up its name in its dictionaries. If it finds an entry, it will use the icon references there to update the image of that item.
  - Could be helpful for Pathfinder 2e, but not needed for D&D 5e as I have imagery for nearly every entry in its database.

## FoundryVTT Core Settings
- Configure Audio / Video > Audio / Video Conference Mode: Disabled
  - Even having this enabled and not using it will cause idle FPS to drop 30-50%. Use Discord for now.
- Configure Settings (tab) > Configure frame rate: 30fps - OPTIONAL. This drops max framerate, but can help create a more consistent gaming experience

# Quick References
Once the above settings are put in place, the following will help you up your GM game.
- Control + Space - This universal search will index ALL contents in FoundryVTT
- Double click on window title bar - This will cause the title window to collapse
  
## Modules In Testing  
None at the moment!

## Modules Pending Review
- [Dr. Mapzo free maps (unofficial)](https://foundryvtt.com/packages/foundry-drmapzo-free/) - Unofficial preparation of Dr. Mapzo's free maps for use as Scenes. Most/all of these have built-in support for the Dancing Lights and Wall Height modules.
- [Scene Transitions](https://foundryvtt.com/packages/scene-transitions/) - Adds the ability to create transitions to play before activating scene.

## Modules Scheduled for a Re-Review at a Later Date
- [Chat Images](https://github.com/bmarian/chat-images) - Copy and Paste, Drag and Drop images into chat. - Retired 2020 Sep 06 - See issue linked below
  - This Module inserts images as base64 encoded data which can grow the chat log to the point it can start to impact gameplay (https://github.com/bmarian/chat-images/issues/7). This could cause large base64 encoded images to be inserted (e.g. 24mb) every time a chat message is posted. Whereas normal images will be resized, compressed, and cached by the browser. - Flagged by an Anonymous user on The Forge Discord
- [Compendium Browser](https://foundryvtt.com/packages/compendium-browser/) - Easily browse and filter spells as well as NPCs loaded from the compendium. - Review 2020 Sep 06 - Seems incredibly useful but there is currently an issue with Shared compendiums that can crash a game (https://github.com/syl3r86/compendium-browser/issues/13). Will revisit once it's had time to stew some more.
- [Cozy Player](https://foundryvtt.com/packages/cozy-player/) - Token toolstips and Quality of Life enhancements - Suggested by azath0ught on the FoundryVTT Subreddit - Review 2020 Sep 06 - Tons of usefull enhancements but a bit overkill. Some of the tooltip options that it can show seem unique to this module and I haven't seeen them elsewhere. There is an open issue to split the module so it's more granular, hopefully that happens.
- [Drag Upload](https://foundryvtt.com/packages/dragupload/) - Suggested by azath0ught on the FoundryVTT Subreddit - Review 2020 Sep 06 - In concept I like it, but has the potential for too many mistakes.
- [Group Initiative](https://foundryvtt.com/packages/group-initiative/) - Suggested by LorduFreeman on The Foundry Discord - Review 2020 Sep 06 - Great idea but seems to be broken (https://github.com/tonifisler/foundry-group-initiative/issues/4).
- [Group Roll](https://github.com/trdischat/grouproll) - Facilitates D&D 5e and Pathfinder 2e Group Roll Checks and Saves. - Retired 2020 Sep 12 - Had no problems with this but decided having everyone roll individually was more fun. 
- [Forien's Quest Log](https://foundryvtt.com/packages/forien-quest-log/) Provides comprehensive Quest Log system for players and Game Masters - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Looks awesome for a big epic game, but seems like overkill for the ones I'm running. Will revisit at a later date.
- [Forien's Unidentified Items](https://github.com/Forien/foundryvtt-forien-unidentified-items) - Handle unidentified items and their identification. - Review 2020 Sep 06 - Love everything about this but don't have a need for it. Going to place this for re-review at a later time.
- [Foundry VTT Macros Repository](https://github.com/foundry-vtt-community/macros) - Foundry community-contributed macros. - Review 2020 Sep 06 - Was looking into this to help out with thing like "Barbarian Rage" but I'd rather just wait at the moment and see if these start to sneak their way in without the need for Macro's.
- [FXMaster](https://gitlab.com/mesfoliesludiques/foundryvtt-fxmaster) - Adds various special effects. - Review 2020 Sep 06 - Seems like an incredible module, but there are 20+ outstanding issues on the repository. Too risky an interuption to regular gameplay in its current state.
- [Grid Scaler](https://github.com/UberV/scaleGrid) - Adds tool to help to set the Foundry grid on the background image - Review 2020 Sep 06 - Seems super helpful, but a number of issues exist. Defintely going to revisit.
- [Journal Links](https://foundryvtt.com/packages/journal-links/) - Links entities (journal entries, actors and items) that reference each other. - Review 2020 Sep 07
  - Currently permissions are not respected which could cause unintended spoilers. Waiting for this issue to resolve before adding it as a daily driver. https://github.com/Sigafoos/journal-links/issues/6
  - Additionally some entities are not being cross linked. https://github.com/Sigafoos/journal-links/issues/7
- [Loot Sheet NPC 5E](https://github.com/jopeek/fvtt-loot-sheet-npc-5e) - Adds an additional NPC sheet which can be used for loot containers such as chests. - Review 2020 Sep 06 - This looks incredible but a number of outstanding issues has me putting this aside to revisit at a later date.
- [Permission Viewer](https://foundryvtt.com/packages/permission_viewer/) - Quickly see which entities (Journal entries, Actors, etc..) are visible to all players or visible to a specific player. - Suggested by KaKaRoTo on The Forge Discord and jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Love it, but the UI is so obtuse, I can't remember what each shape means and so it's not actually helpful.
- [Popout Resizer](https://github.com/Cardagon/popout-resizer) - Give the users the ability to resize their pop-out windows from the side toolbar. - Retired 2020 Sep 06 - Haven't needed this, but might as things continue to get more complicated. Setting this for Re-Review.
- [Sheet To Token](https://foundryvtt.com/packages/sheet-to-token/) - Automatically updates an actor's Prototype Token to match its actor image when updated. - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Fantastic idea, but haven't actually needed it in practice so far.
- [Virtual Tabletop Assets - Party Overview](https://www.vttassets.com/assets/vtta-party) - Adds a party overview window, granting you information about some vital stats quickly and without hassle. - Retired 2020 Sep 06 - I don't like to know everything about the part, but I'm willing to revisit at a later date.
  - Grant Players access to the overview?: Off
  - Enable tooltips?: Off - Similar information is already provided by Token Info Icons

## Modules Reviewed or Retired
These modules are no longer used as they’ve become redundant to features provided by other modules, they caused other issues (e.g. lag), or there was nothing wrong with them but I just didn't find their use out weighed creating a more complex buildout.
- [Ambient Doors](https://github.com/EndlesNights/ambientdoors) - Customized sounds effects that trigger for all users when interacting with doors. - Retired 2020 Sep 12 - Worked great but I wanted to reduce the number of modules I was dependent on.
- [Batch Permission Change By Folder](https://foundryvtt.com/packages/BatchPermissionsByFolder/) - Adds a context option to folders in Items, Journals, and Roll to change the permission of each entity(Foundry's codeword for Item, Journal Entry, or Roll Table) inside the folder. - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Not a bad idea, but haven't had the need for it.
- [Better NPC Sheet 5e](https://github.com/syl3r86/BetterNPCSheet5e) - Review 2020 Sep 06 - Nice for what it does but superseded by Tidy 5e Sheet
- [Better Rolls for 5e](https://foundryvtt.com/packages/betterrolls5e/) - Overhauls most rolls on the 5th edition character sheet, and provides a way to customize roll messages per-item. - Review 2020 Sep 06 - This is a well thought out module but much of what it can do is more quickly done with "Token Bar". If you often have compound rolls (e.g. higher levels with multiple attacks) then you might want to consider this. I personally don't mind just clicking the attack roll multiple times.
- [Chat Scrolling](https://foundryvtt.com/packages/chat-scrolling/) - Makes FoundryVTT's chat log not jump to the bottom for a new message if you have scrolled up to read the log. - Review 2020 Sep 12 - Nice quality of life improvement. Don't need it now, but one day I might revisit.
- [Community Tables](https://foundryvtt.com/packages/foundry_community_tables/) - A collection of Tables added by the FoundryVTT Community. - Review 2020 Sep 06 - Cool idea, but not enough content to warrant installing it.
- [Compendium Image Mapper](https://gitlab.com/Wilco7302/compendium-image-mapper) - select a folder containing images, and then automatically search for compendium entries that best match your images. - Review 2020 Sep 06 - Fantastic module if you have a huge library of well named images you want mapped to compendium entries. I do not.
- [Compendium Folders](https://foundryvtt.com/packages/compendium-folders/) - Adds a nested folder structure, and option for hiding entries, for your compendiums. - Retired 2020 Sep 12 - Loved this, but it's more than I need and I want to keep the Module stack as tight as possible.
- [ConditionIconHoverZoom](https://github.com/Sparkasaurusmex/ConditionIconHoverZoom) - Makes condition icons more legible by increasing their size. Also enlarges and makes them opaque on hover. - Review 2020 Sep 06 - I thought I wanted this when I first saw it, but I don't really need it.
- [Dancing Lights v2](https://github.com/BlitzKraig/fvtt-DancingLights) - Better ambient lighting & Token light toolkit - Suggested by jniezink on the FoundryVTT Subreddit - Retired 2020 Sep 12 - Worked great but I wanted to reduce the number of modules I was dependent on.
  - This feature will be coming soon to FoundryVTT 7 core. Once it is, this module can be removed.
- [Dice Tray](https://gitlab.com/asacolips-projects/foundry-mods/foundry-vtt-dice-calculator) - Adds a Dice Tray below the chat. - Retired 2020 Sep 06 - Nothing wrong with this, just felt like overkill. Everything has an option to autoroll, or a user can type "/roll 1d20+2" if they need to. Wasn't saving any time.
- [DNDBeyond Character Sheet](https://foundryvtt.com/packages/dndbeyond-character-sheet/) - Replacement of a character sheet with a version more similar in style to that of D&D Beyond's. - Review 2020 Sep 06 - Great work, but superseded by Tidy 5e Sheet. The module also has outstanding issues with its responsiveness and content being cut off. 
- [D&D 5e Conditions](https://github.com/trdischat/conditions5e) - Review 2020 Sep 06 - Great idea, but not needed with everything else we have running.
- [D&D5E Dark Mode](https://github.com/Stryxin/dnd5edark-foundryvtt) - Review 2020 Sep 06 - Cool! I just have no need for dark mode.
- [Easy Target](https://bitbucket.org/Fyorl/easy-target/) - Toggles the targeting tool while holding option key (alt on Windows). Also allows for option+clicking inside an AoE to target all tokens within that AoE. Holding the option key while placing a template will also target all tokens within that template when placed. - Retired 2020 Sep 06 - Nothing wrong with this, but I found myself just manually selecting the targets after the AOE was placed.
- [Encounter Builder for 5e](https://foundryvtt.com/packages/encounter-builder-5e/) - D&D 5e Only. Aid in building D&D5E combat encounters. - Review 2020 Sep 06 - Great idea and well executed, but I don't have the need. If you you need help balancing an enounter, give this a try.
- [Escape Window](https://foundryvtt.com/packages/escape-window/) - Suggested by azath0ught on the FoundryVTT Subreddit - Review 2020 Sep 06 - Not neccisary. I can double click on the title bar of a sheet / pop-up to minimize it.
- [Expander](https://github.com/Sky-Captain-13/foundry/tree/master/expander) - Expands the chat window when you click on the chat icon instead of only by clicking on the arrow at the bottom. - Review 2020 Sep 06 - I love everything about this, but I'm not going install a whole module just for this small change. Hopefully it makes its way into FoundryVTT core one day.
- [Follow Me](https://github.com/Brunhine/FollowMe) - Allows tokens to follow other tokens. - Retired 2020 Sep 06 - Nothing wrong with this, just felt like overkill.
- [Forien's Copy Environment](https://foundryvtt.com/packages/forien-copy-environment/) - Allows for copying TXT/JSON list of installed and enabled system/modules and their versions. - Review 2020 Sep 12 - Great idea but I'm using Adventure Importer / Exporter and it's fulfilling all my needs.
- [FoundryVTT Image Drop](https://gitlab.com/mesfoliesludiques/foundryvtt-image-drop) - Allows dropping Journal Entry to the canvas as Tile - Review 2020 Sep 12 - Cool idea but I have no need of this.
- [Foundry VTT Modules for DnD 5E](https://github.com/foundry-vtt-community/modules/tree/master/Foundry%20VTT%20Modules%20for%20DnD%205E) - Marked for review, seems outdated. - Review 2020 Sep 06 - This was a list of modules with many of them that seem to be in FoundryVTT core now and other just outdated for problems that no longer exist.
- [GM Scene Background](https://github.com/death-save/gm-bg) - Allows GMs to set a GM-only background image. - Retired 2020 Sep 12 - Loved this but just reducing the number of modules I have installed and this one I thought I would use but never ended up needing. 
- [Health Estimate](https://gitlab.com/tsuki.no.mai/healthestimate) - Shows estimated health level of an enemy on mouseover. - Retired 2020 Sep 06 - Nothing wrong this, just felt like overkill given all the other info that can be so quickly gleaned.
  - GM Only: On
- [Haste](https://gitlab.com/jesusafier/haste) ([module.json](https://gitlab.com/jesusafier/haste/-/raw/master/module.json)) - Performance enhancement and tweaks. - Suggested by jniezink on the FoundryVTT Subreddit - Retired 2020 Sep 06 - Loved this, but ended up not really needing it. Also hopefully many of these issue will be resolved with the 7x release.
  - Configure Settings (tab) > Module Settings > Fix CPU on token movement: Checked
  - Configure Settings (tab) > Module Settings > Experimental Adaptive GPU fps tweak: Checked - This will cause Dancing Lights and other animations to stop when the player goes idle. You may not want to use this if you have lots of animations. You may want to use this if most players have slower computers.
- [Kobold Press OGL](http://kpogl.wikidot.com/) - All the 5e OGL Content Kobold Press has released - Review 2020 Sep 06 - This is awesome if you want Kobold Press content.
- [Layer Hotkeys](https://github.com/Moerill/Layer-Hotkeys) - Review 2020 Sep 06 - The last thing I want is more hotkeys, nice if you do though.
- [Lazy Money](https://github.com/DeVelox/lazymoney) - Easily add or remove currency with automatic conversion and no overdraft. - Review 2020 Sep 12 - Nice quality of life improvement, but not worth adding a whole module for.
- [Less Fog](https://github.com/trdischat/lessfog) - Tweaks fog of war visibility for GM and Players. - Retired 2020 Sep 11 - Really loved this, but trying to cut as many modules as possible. Especially those that alter the rendering of the scene.
- [Maestro](https://github.com/death-save/maestro) - Adds player hype tracks, item tracks, combat tracks, and more. - Retired 2020 Sep 12 - Loved it, but wanted to reduce the number of modules I was dependent on
  - Configure Settings (tab) > Module Settings > Enable Hype Track: Checked
  - Configure Settings (tab) > Module Settings > Enable Combat Track: Checked
  - Configure Settings (tab) > Module Settings > Create Combat Tracks Playlist: Checked
  - Configure Settings (tab) > Module Settings > Disable Dice Sounds: Checked
  - Configure Settings (tab) > Module Settings > Enable Critical Success / Failure Tracks: Checked 
 - [Master Mirror](https://foundryvtt.com/packages/master-mirror/) - A simple CSS module that rearranges the Foundry UI elements. Sidebar on left, scene controls on right, etc. - Review 2020 Sep 12 - Cool idea but I'm just using the Custom CSS module to put in my own changes, don't need this.
- [Mess - Moerills enhancing super-suit(e)](https://github.com/Moerill/mess) - Many features, possible compatibility issues. - Review 2020 Sep 06 - So much work clearly went into this module, but it's stated not caring about creating potential conflicts is too big a risk to have this be a daily driver. Nice work though.
- [MiniMap](https://gitlab.com/jesusafier/minimap) - Shows a minimap - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - This is such a cool idea but it's so easy to quickly Zoom out that it's not actually that helpful in practice.
- [Monster Blocks](https://foundryvtt.com/packages/monsterblock/) - An NPC sheet for FoundryVTT designed to faithfully reproduce the appearance of D&D 5e monster statblocks. - Review 2020 Sep 12 - I love it but I'm sticking with just Tidy 5e Sheet for now.
- [Multilevel Tokens](https://foundryvtt.com/packages/multilevel-tokens/) - Allows you to mark out linked regions on the map. Tokens present in the source region will be automatically cloned to the target region, and kept up-to-date with the original, mirroring movement and other changes. - Reviewed 2020 Sep 12 - Cool idea, I just have no use for it.
- [Pick-Up-Stix](https://foundryvtt.com/packages/pick-up-stix/) - Create items as Tokens that players can pick up. It will automatically add the items to the player's inventory. - Retired 2020 Sep 12 - Great idea but I want to reduce the number of modules I'm dependent on. And this one was nice, but not something I used regularly. 
- [PopOut!](https://github.com/kakaroto/fvtt-module-popout) - Lets you pop out actor sheets and journal entries into their own windows. - Retired 2020 Sep 06 - Nothing wrong with this but it wasn't actually needed in the end.
- [Search Anywhere](https://gitlab.com/riccisi/foundryvtt-search-anywhere) - Press (control + space) to quickly search for any entity by name via a handy auto-complete widget. - Retired 2020 Sep 11 - Replaced by [Quick Insert](https://foundryvtt.com/packages/quick-insert/)
- [Show Art](https://foundryvtt.com/packages/token-hud-art-button/) - Adds a button to the token or tile HUD that opens the target actor's artwork, or their token artwork on right-click. - Review 2020 Sep 12 - Great idea but not worth having another module for.
- [Teleport](https://foundryvtt.com/packages/teleport/) - Moves (teleports) one or more tokens from one point to another on the same or different scenes. - Retired 2020 Sep 12 - Great idea but requires just as much effort to set up as it does to do it manually.
- [The Furnace](https://foundryvtt.com/packages/furnace/) - Many features to improve the Quality of Life of the DM/Players. - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - Lot's of rich features, but nothing not already being provided elsewhere.
  - Advanced Macros: Off
  - Advanced Drawing Tools: Off
  - Improve the Playlists UI: Off
- [Tidy UI - Game Settings](https://github.com/sdenec/tidy-ui_game-settings) - A module to make the game settings menu a bit more comfortable to use. - Retired 2020 Sep 06 - Nothing wrong with this, just felt unnecessary since I'm not messing around the the game settings that often after the instance has been set up. Still nice to have during your first build out but unnecessary.
- [Token Bar](https://github.com/Kekilla0/TokenBar) - It populates an action bar for the token you have selected. - Retired 2020 Sep 07 - Replaced by [Token Action HUD](https://github.com/espositos/fvtt-tokenactionhud).
  - My pending pull request that makes the Token Bar use a more native UI https://github.com/Kekilla0/TokenBar/pull/20
- [Token Health](https://github.com/tonifisler/foundry-token-health) - Apply damage/healing to all selected tokens. - Review 2020 Sep 06 - Great idea but overkill and one more keyboard shortcut I would need to remember.
- [Token Mold](https://github.com/Moerill/token-mold) - For minting tokens that auto append a counter or descriptor to the tokens name. Also can handle automatic token scaling. - Retired 2020 Aug 09 - Great concept but limited utility at the moment. Retiring to reduce UI clutter, will revisit in the future.
- [Token Owner Selection Tweak](https://foundryvtt.com/packages/token-owner-selection-tweak/) - Prevents player selection (and therefore vision) from changing if a new token they are the owner of is created. [More here](https://www.reddit.com/r/FoundryVTT/comments/iq4kv4/module_fix_vision_going_dark_when_utility_tokens/). - Review 2020 Sep 12 - If your game has a lot of familiars or similar instances, you may want this. Mine does not.
- [Token Vision Tweaks](https://foundryvtt.com/packages/token-vision-tweaks/) - Provides some tweaks for Token Vision, to allow trading quality for performance, or vice-versa. Also provides a fix for a vision issue present in large open maps which may cause tokens to be able to see through distant walls, as well as a Fog-of-War memory leak. - Review 2020 Sep 12 - Decided I'm trying to avoid as much as possible, modules that change the scene.
- [Trigger Happy](https://foundryvtt.com/packages/trigger-happy/) - Create triggers for your players to spring traps or anything you can think of. - Retired 2020 Sep 12 - Nothing wrong with this just wanted to reduce the number of modules needed and I can handle this as DM.
- [Turn Alert](https://github.com/schultzcole/FVTT-Turn-Alert) - Set alerts to trigger on a particular round of combat or on a particular token's turn. - Retired 2020 Aug 09 - Turn altering is handled by Combat Ready
- [Turn Marker](https://github.com/Brunhine/TurnMarker) - Adds an image under a token who is currently active in the combat tracker. - Retired 2020 Aug 09 - Turn marking is handled by Combat Ready
- [Tweak Playlist](https://foundryvtt.com/packages/tweakplaylist/) - Make playlists visible only to the GM. Allow for random loop delays and random volume adjustments between repeated plays of a sound. Also adds color to Play and Stop buttons in playlists. - Review 2020 Sep 12 - Love the visual tweaks but not worth having another module.
- [Vance's Sidebar Resizer](https://github.com/VanceCole/vance-sidebar-resizer) - Allows the sidebar to be resized. - Retired 2020 Sep 06 - Nothing wrong with this, just ended up never needing it.
- [VTT Modbox](https://gitlab.com/mesfoliesludiques/foundryvtt-modbox) - Creates an input field to add a modifier to the next roll - Review 2020 Sep 06 - I see the value, I just don't need it.
- [VTT ReturnToSetup](https://github.com/ardittristan/VTTReturnToSetup) - Adds a return to set up button on the main login screen. - Retired 2020 Sep 12 - Cool idea, but the visual interaction that happens when you select this option was a hot mess.
- [WhisperBox](https://github.com/Sk1mble/WhisperBox) - Create a dedicated box for whispering to a specific player - Suggested by jniezink on the FoundryVTT Subreddit - Review 2020 Sep 06 - This is an excellent idea, but some UX leaves me wanting. Hopefully something similar gets built out in FoundryVTT core.

# Additional Resources
- [All D&D 5e Monster Tokens](https://www.reddit.com/r/dndnext/comments/ij8ljk/i_made_monster_tokens_for_every_monster_in_the/)
- [Foundry VTT Community](https://foundry-vtt-community.github.io/)
- [Inkarnate](https://inkarnate.com/) - Map and Dungeon Generator that works well with FoundryVTT (Free or $25yr)
- [Intro to Dynamic (Character Stat) Effects](https://www.reddit.com/r/FoundryVTT/comments/ibfphc/a_very_simple_intro_to_dynamic_effects/)
- [Module usage statistics from The Forge - July 2020](https://i.imgur.com/xRVVed1.png)
- [Official FoundryVTT Sub-Reddit Module Wiki](https://www.reddit.com/r/FoundryVTT/wiki/index/modules)

# Bryan's Repositories
- [Bryan's AWS Setup Guide for FoundryVTT](https://github.com/bryancasler/Bryans-AWS-Setup-Guide-for-FoundryVTT)
- [Bryan's FoundryVTT Assets and Resources](https://github.com/bryancasler/Bryans-FoundryVTT-Assets-And-Resources)
- [Bryan's Preferred Modules for FoundryVTT](https://github.com/bryancasler/Bryans-Preferred-Modules-for-FoundryVTT)
