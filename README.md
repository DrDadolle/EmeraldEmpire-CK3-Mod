# What is RokuganModCK3 ?
CK3 Mod of the Emerald Empire Rokugan from the TTRPG L5R.
It is a WIP, not even alpha state

## Map reference 
Atlas of Rokugan L5R 4e
https://www.reddit.com/r/rokugan/comments/jdcb7e/photoshopped_full_rokugan_map_w_provinces_families/#lightbox
Old Map of 1ed for unaligned lands
https://i.pinimg.com/originals/95/bc/75/95bc7582314663071bf04a08d022dffb.jpg
L5R 5e map 
https://cdn.svc.asmodee.net/production-l5r/uploads/2023/06/03_Map_Background-Rokugan-1900x2755.jpg
Some recap :
https://cdn.discordapp.com/attachments/739793880010063893/1159210531832479815/MAP_PARTAGE_BASE_V4.png?ex=662022ef&is=660dadef&hm=419084cf70964e46659eb64fc07a20c3dd79c694952ad321db07dbcb972925cb&



## How to install
Copy paste everything in your mod folder. Don't forget to update the path in RokuganWIP.mod.

## Changes compared to Vanilla
Those changes are made as the map is smaller and all samourai shares the same language.
- Cultural Acceptance is lower, as all Clans share the same language (-15 -> -20 & -30 -> -40 for same realm)
- Maximum 1 held duchy (if you are king or higher) before opinion loss
- Stewardship grants less bonus domains (from /6 to /7)

## short term goals 
- fix republic county
- fix title for tribal leader & Theocracy leader of countries/+++
-Fix river width
- Have a not-so-ugly heightmap
	- Fix river & coast 
- Paint the map with materials
- Rework provinces, so looks better
- provinces terrain (plains, etc...)
- Climates
- Last name added to names BUT, need to use spouse name if maried ? Add "of Lands" too ?
- Add river map
- check Kizoku title

# Fixes to do
- How to prevent random mariage & children in existing character ? => change game_rule.1001 ??? gamerule_1001 force generate descendance
- Fix the "Family Lands of Daidoji lands"; "Clan of Crane Clan", etc...
- clean up of traits (like removing Hajji  from pilgrim traits)
- Change color of some textured emblmes (very low priority)
- update holy_order decisions & dynasty decisions (taken from shogunate)

## Futures Features & Nice to have
- rename months / Date / etc... to L5R one (change localization, but not calendar itself) 
- Remove AI Cadet branches => Working ?
- Seppuku as  part of "Bushido tradition". Special decision if "dishonored"
- Special protection against conquest for un-aligned/minor/imperial lands => Casus belli way more costly + lose of prestige ?
	- How to distinuing between imperial families (based on dynasty ?) and minor clan ? (when not King & liege is the emperor directly ?)
	- What are the rules ??? Protected by imperial law if :
		- Target as smaller rank => gains trait "broke imperial peace" ?
		- or Target is imperial Dynasty => gains trait excommunicated-like "attacked imperial family" (so others can attack you for it)
		- is "Major Clan" and Target is not "Major Clan" => gains trait "broke imperial peace" ?
			- Major clan is if liege or liege of liege is KING.
		- It is "add_trait = broke_imperial_peace" "on_declaration" !
		- Add it as a crime into the religion ?
- Prevent imperial family from doing wars against other clans...? Dunno
- Painting Hair White decision for crane cultures
- Genetic Trait "Natural white hair" for Crane ???
- Right/Left/UnderHand special trait for clan champion of crane/lion/scorpion ??
- Blood feud (like Matsu vs Kakita)
- add trial by combat + choosing champion (AGOT mod does it ?)
- Add ancestral clan & family founders
- Special decisions
	-Become Great Clan : Requires X Duchy or Y counties. Emperor positive relation. Emperor MUST be direct liege. Name of Duchy Title => Name of Kingdom title. Duchy titles become "[DYNASTY] lands"
		- No other ways to create a kingdom title. Basically rework existing mechanics
	- Retake Yasuki Lands as Crane Clan
 	- Become Great Clan (Kingdom) as (Mantis ?) Minor Clan 
	- reclaim ancestral hiruma lands as Hiruma familly
	- if emperor : get a doji bride
	- if emperor : all siblings goes to "Otomo" once there is an heir + The revert decision

- Special Phoenix champion succession
- Phoenix Council of 5 special government
- Togashi special succession ?
- Special weapon & artifacts
- Black scrolls, cursed artifacts
- Shindoshi stuff (very low priority)
- Maho stuff (very low priority)
- Shadowlands stuff (very low priority)
- Change calendar to lunar calendar (cf Lotr "Gwaeron" month or other TC mod does)

## Credit
