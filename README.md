WebSocket API for OBS Studio.

Discord Financial Contributors on Open Collective

Downloads
obs-websocket is now included by default with OBS Studio 28.0.0 and above. As such, there should be no need to download obs-websocket if you have OBS Studio > 28.0.0.

Binaries for OBS Studio < 28.0.0 on Windows, MacOS, and Linux are available in the Releases section.

Using obs-websocket
It is highly recommended to keep obs-websocket protected with a password against unauthorized control. obs-websocket generates a password for you automatically when you load it for the first time. To change this, open the "obs-websocket Settings" dialog under OBS' "Tools" menu. In the settings dialog, you can enable or disable authentication and set a password for it.

(Psst. You can use (value), (value), (flag) and (flag) on the command line to override the configured values.)--websocket_port--websocket_password--websocket_debug--websocket_ipv4_only

Possible use cases
Remote control OBS from a phone or tablet on the same local network
Change your stream overlay/graphics based on the current scene
Automate scene switching with a third-party program (e.g. : auto-pilot, foot pedal, ...)
Client software
Macro Deck
Touch Portal
Twitchat
OBS-web - hosted client at obs-web.niek.tv/
Streamer.bot
Deckboard
OBS Blade
Aitum
Kruiz Control
Bitfocus Companion Module
MacroGraph - hosted client here
MATRIC
Client libraries (for developers)
Here's a list of available language APIs for obs-websocket:

Python 3.7+ (Asyncio): simpleobsws by IRLToolkit
Python 3.10+ (Non-Asyncio): obsws-python by aatikturk and onyx-and-iris
Rust: obws by dnaka91
Godot 4.0.x: obs-websocket-gd by you-win
Javascript (Node and web): obs-websocket-js by OBS Websocket Community
C (uses obs-websocket-js): v8-libwebsocket-obs-websocket
Go: goobs by andreykaipov
Dart/Flutter (can target all supported platforms): obs_websocket by faithoflifedev
Java: obs-websocket-java by OBS Websocket Community
The 5.x server is a typical WebSocket server running by default on port 4455 (the port number can be changed in the Settings dialog under ). The protocol we use is documented in PROTOCOL.md.Tools

We'd like to know what you're building with obs-websocket! If you do something in this fashion, feel free to drop a message in in the discord server!#project-showoff


