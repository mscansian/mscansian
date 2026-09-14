# Odds and ends

Projects too niche for the front page — an audience of one, or close to it.
Some solved a problem I had once and never again, some were how I learned
whatever I was learning at the time. Newest first.

## 2026
- [Satisfactory-AI](https://github.com/mscansian/Satisfactory-AI) — two MCP servers that hand a model the game's recipe data, a production-chain solver that accounts for belt limits and overclocking, and read access to save files. A factory planner you argue with instead of a spreadsheet you fill in.

## 2025
- [dev-proxy](https://github.com/mscansian/dev-proxy) — two local proxies: HTTPS on a self-signed certificate, for the APIs that refuse to run without it, and one that delays every request so loading states are visible on a machine that's too fast to show them.

## 2019
- [AWS nodes for n8n](https://github.com/n8n-io/n8n/pull/32) — SNS publish and Lambda invoke, written against the AWS REST APIs so the nodes didn't have to carry the SDK.
- [alexa_metar](https://github.com/mscansian/alexa_metar) — an Alexa skill that reads the METAR for Brazilian airports, by name or ICAO code, with the codes spoken in the ICAO alphabet.

## 2018
- [Strava upload for antfs-cli](https://github.com/Tigge/antfs-cli/pull/173) — antfs-cli pulls activity files off old Garmin watches over ANT-FS. Garmin shipped a Windows app to get them off the watch and nothing else; I run, I use Linux, and I keep my runs in Strava rather than Garmin Connect. This uploads each file as it comes off the watch.

## 2014
- [SigmaWebPlus](https://github.com/mscansian/SigmaWebPlus) — an Android app that watched the university's academic system and said something when a grade appeared. Built because waiting for grades to be published made me anxious; it ended up on the Play Store with a good part of the university using it.
- [ahk-sap](https://github.com/mscansian/ahk-sap) — AutoHotkey macros for SAP, from a job at a large company that had me typing the same information into the same screens all day. People there called them die Geisterhände, after the mouse working through screens with nobody at the desk.

## 2000s
Blitz3D was what I made games in as a teenager. These four are the parts that outlived the games, published in 2014, years after they were written.

- [b3d-astar-pathfinding](https://github.com/mscansian/b3d-astar-pathfinding) — A\* pathfinding. Works on grids, waypoints or navmeshes, takes a custom heuristic and terrain cost, and can spread one path across several iterations instead of blocking a frame.
- [b3d-binaryheaps](https://github.com/mscansian/b3d-binaryheaps) — binary heaps, written to keep the pathfinder fast enough to be worth using.
- [b3d-pxGUI](https://github.com/mscansian/b3d-pxGUI) — a GUI toolkit: text and password inputs, buttons, checkboxes, dropdowns, labels. Restyled by swapping a bitmap.
- [b3d-pxMAP](https://github.com/mscansian/b3d-pxMAP) — loads Valve Hammer Editor `.map` files into Blitz3D primitives, textures and entities included.
