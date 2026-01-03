# HappyMinecraft – Server Resourcepack (Sounds)

Dieses Repository enthält die Releases für das **Server-Resourcepack** meines Paper-Servers.
Es wird genutzt, um **eigene Ambient-Sounds** (OGG) in der RPG-Stadt abzuspielen (z.B. Markt, Taverne, Hafen).

## Download (für server.properties)
Latest:
https://github.com/harisjade-bambelbie/HappyMinecraft/releases/latest/download/rpg_sounds_custom.zip

## Installation (Server)
In `server.properties` eintragen:

resource-pack=https://github.com/harisjade-bambelbie/HappyMinecraft/releases/latest/download/rpg_sounds_custom.zip
resource-pack-sha1=22c0b5fc90ab4096c092a41daff7e80cd46e868b
require-resource-pack=true

## Sound-Keys (Beispiele)
- rpg:market
- rpg:taverne
- rpg:harbor
- rpg:library
- rpg:church_chor
- rpg:darkforest
- rpg:cafe
- rpg:seagull
- rpg:bird01

Test ingame:
`/playsound rpg:market master @p ~ ~ ~ 1 1 0`

## Updates
1) Neue ZIP erstellen (neue OGGs / sounds.json)
2) Neues Release erstellen (z.B. v1.0.1) und ZIP als Asset hochladen
3) SHA1 neu berechnen und in `server.properties` aktualisieren
