# Unofficial YourMap

This is a little Babylon.js / MeshWriter first time experiment to generate a visual map of the many YourLand Minetest server Cities.
Datas has been collected by players other the years, and we recently updated it, reading books IG, and travelling IG world.

Cities datas Credits : alexandre2005, AliasAlreadyTaken, Bla, Boot, Chache, LichBerry, Mielle and probably many others (help makes this accurate please)

This project was really a test, and if it seems usefull then we'll see what to do with it.

I personnaly needed a visual representation of the world, this may be usefull for others, but we also have to be cautious to not spoil new players or those who strictly prefer to not have more help than the game offers.
Those games are also about exploration, so if you use this : use it with moderation !

OBVIOUSLY this in a WORK IN PROGRESS

Am already glad been able to put something so quickly with not too much hurddles, thx to Babylon.js

Let see if it grows.

https://dev777.github.io/YourMap/

CONTROLS
LMB Rotate view / RMB Pan view / WHEEL zoom to pointer

--- TO DO ---
* Many things, by priority :
- [ ] CODE: add timers
- [ ] CODE: check importing assets and functions times
- [ ] CODE: rewrite textCities infos with 3DGUI OR test with POVs generations
- [x] CODE : Mix own and server JSON, add : server_Owner, server_CityName, display, creationdate, position0ifNot...
- [x] CODE : Rewriting Json part
- [x] PERF : reassign txt materials, purge generated ones
- [x] UI / CODE : add a loading screen or something, mb credits until loaded
- [x] FEATURE : display cam x y z >> GUI2D stack panel, AfterRender babylon function
- [ ] FIX : Fix panning bug again (focuscam)
- [x] UI/PERF : make ressources heavy parameters deactivable
- [ ] CODE: improve underground cities handling
- [ ] CODE/FEATURE: seperate POVs from Cities, default is disabled
- [ ] UI: Change text size according to City size/activity
- [ ] UI/PERF: needs SSAO & Ambient
- [x] CODE : using Y value for cities
- [x] CONTENT : added landscape around, changed environment set by default
- [x] FEATURE : Academy list v1
- [x] UI : Put back help controls
- [x] FEATURE : add keyboard control to camera >> default for universal camera
- [x] CONTENT : add credits
- [x] TXT : rotate them >> City names rotated 90°
- [x] TXT : fix 'n' letter or use CAPS >> using caps for now
- [x] UI : add icons for mobility >> added 3D meshes : zep & boatMesh
- [x] CODE : js generate cities menu
- [ ] CODE, UI : improve side menu
- [x] CODE / UI: add mobility/mayor/biome/coords infos
- [x] change TXT material to diffuse
- [x] UI : add minecart meshes
- [x] FEATURE : Side pannel with cities that focus on selected city with a local ArcCam >> wup wup wup, choosed JS/HTML menu for now
- [x] FIX : reset cameras > now it loose panning > must fix >> ok must use target.position.clone() for it to works
- [ ] ORG :Parent city_infos to disc
- [ ] FEATURE : add possibility to enter coords (jump to, check closest city)
- [x] FEATURE : choose cameras : free / arc
- [ ] FEATURE : constrain camera's Y axis
- [x] CODE : separate Json file
- [x] PERF : replace circular grid with a 3D mesh instance
- [x] UI : Reorder buttons, make a bottom bar
- [ ] PERF : use LOD
- [x] PERF : check all shadows / collision / lights to disable  >> Those needs to be activated
- [ ] UI : display actual pointer position (projection invis plane ?)
- [ ] FEATURE / CONTENT : display more cities datas (shields, quick description, state, alliance, farms, portals, church)
- [ ] FEATURE : make city's discs or City name clickable too > then option list (travel, info...)
- [ ] FEATURE : add voice's attack spot and dates, add POVs category
- [ ] IDEA : add possibility to place grid origin at locations, with rotation
- [ ] IDEA : AND / OR add a ruler
- [ ] IDEA : Add registered path (with multilines)
- [x] UI : change lightning and colors
- [ ] FEATURE : add layers displaying mobility paths (boat; zep; rails)
- [ ] IDEA : test flythrough (city to city)
- [ ] IDEA / 3D : obtain a layer 0 of the world (only ocean, river) >> add water only (Global Blender Mesh)
- [x] CONTENT : try manual carto Haven Island > tedious
- [x] FIX : replace city names with Blender objects ? >> Nope, got text meshes finally
- [ ] FEATURE : add Tunnels / bridges
