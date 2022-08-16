# Unofficial YourMap

This is a little Babylon.js / MeshWriter first time experiment to generate a visual map of the many YourLand Minetest server Cities.
Datas has been collected by players other the years, and we recently updated it, reading books IG, and travelling IG world.

Credits are waiting approvals.
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
* Many things...
- [ ] add possibility to enter coords (jump to, check closest city)
- [ ] display actual pointer position (projection invis plane ?)
- [ ] separate Json file
- [x] TXT : rotate them >> City names rotated 90°
- [x] TXT : fix 'n' letter or use CAPS >> using caps for now
- [x] PERF : replace circular grid with a 3D mesh instance
- [ ] add possibility to place grid origin at locations, with rotation
- [ ] AND / OR add a ruler
- [ ] Add registered path (with multilines)
- [x] UI : Side pannel with cities that focus on selected city with a local ArcCam >> wup wup wup, choosed JS/HTML menu for now
- [ ] UI : choose cameras : free / top
- [x] reset cameras > now it loose panning > must fix >> ok must use target.position.clone() for it to works
- [x] change lightning and colors
- [ ] test flythrough (city to city)
- [x] add icons for mobility >> added 3D meshes : zep & boatMesh
- [ ] add minecart meshes
- [ ] UI : add layers displaying mobility paths (boat; zep; rails)
- [ ] UI : display more cities datas (shields, quick description, state, alliance, farms, portals, church)
- [ ] obtain a layer 0 of the world (only ocean, river) >> add water only (Global Blender Mesh)
- [x] replace city names with Blender objects ? >> Nope, got text meshes finally
- [ ] EVENT : make city's discs clickable too > then option list (travel, info...)
- [ ] add voice's attack spot and dates, add POVs category
- [ ] add Tunnels / bridges
