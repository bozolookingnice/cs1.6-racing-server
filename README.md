# cs1.6-racing-server
🧾 CS 1.6 Racing Mod — FULL ITEMIZED FEATURE LIS

[AMXX] → done in AMX Mod X (Pawn, server-side script)

[MM] → done in Metamod plugin (C/C++, engine hooks)

[AMXX/MM] → starts in AMXX, refined or assisted by Metamod

[MAP] → mapping work (Hammer)

[ASSET] → models/sounds/sprites

[INFRA] → server / tooling

🎮 Core Game Mode

Disable all weapons [AMXX]

Block weapon pickup [AMXX]

Block shooting & reloading [AMXX]

Disable bomb / hostage objectives [AMXX]

Disable round win conditions [AMXX]

Infinite round timer [AMXX]

Freeze players at race start [AMXX]

Race countdown (visual + audio) [AMXX]

Race state control (idle / countdown / running / finished) [AMXX]

Auto-restart race [AMXX]

Late-join spectator mode [AMXX]

Player ready system [AMXX]

Force team assignment [AMXX]

No damage / friendly fire disabled [AMXX]

Fall damage disabled [AMXX]

Collision handling between players (on/off) [AMXX/MM]

🏎 Player Movement & Physics

Custom max speed [AMXX]

Custom gravity [AMXX]

Custom friction [AMXX/MM]

Acceleration curve [AMXX/MM]

Deceleration curve [AMXX/MM]

Speed clamping [AMXX/MM]

Disable jump [AMXX/MM]

Disable crouch [AMXX/MM]

Disable air-strafing [MM]

Ground detection [MM]

Sliding on turns [AMXX/MM]

Drift approximation [MM]

Boost pads [AMXX]

Slowdown zones [AMXX]

Kill zones (reset) [MAP + AMXX]

Out-of-bounds detection [MAP + AMXX]

Automatic respawn on crash [AMXX]

Velocity smoothing [MM]

Input filtering (W/A/S/D) [MM]

Steering sensitivity control [AMXX/MM]

🧠 Vehicle Abstraction (Player-as-Car)

Player model hidden [AMXX]

Fake car model attached [AMXX]

Car orientation follows velocity [AMXX/MM]

Car pitch/roll alignment to surface [MM]

Wheel rotation animation [AMXX]

Car color selection [AMXX]

Car skin selection [AMXX]

Car class stats (speed/grip/accel) [AMXX]

Hitbox adjustment [MM]

Camera offset tuning [AMXX]

📷 Camera System

Third-person camera [AMXX]

Camera distance adjustment [AMXX]

Camera height adjustment [AMXX]

Smooth camera follow [AMXX/MM]

Camera collision prevention [MM]

First-person fallback [AMXX]

Spectator camera [AMXX]

Camera lock during countdown [AMXX]

⏱ Racing Systems

Lap counter [AMXX]

Lap timer [AMXX]

Best lap tracking [AMXX]

Sector timing [AMXX]

Checkpoint validation [MAP + AMXX]

Missed checkpoint detection [AMXX]

False start detection [AMXX/MM]

Finish line detection [MAP + AMXX]

Race completion handling [AMXX]

DNF detection [AMXX]

Split-time display [AMXX]

Ghost lap support (optional) [AMXX]

🏁 Position & Competition

Live position tracking [AMXX]

Overtake detection [AMXX]

Tie-breaking rules [AMXX]

Finish order recording [AMXX]

Podium display [AMXX]

Replay race results [AMXX]

Time trial mode [AMXX]

Lap race mode [AMXX]

Knockout mode [AMXX]

Drag race mode [AMXX]

🧩 Powerups & Events (Optional)

Speed boost pickup [AMXX]

Temporary grip boost [AMXX/MM]

Slowdown trap [AMXX]

Reset-to-last-checkpoint [AMXX]

Random pickup boxes [AMXX]

Cooldown system [AMXX]

Visual effect feedback [AMXX]

Sound feedback [AMXX]

🧾 HUD & UI

Speedometer [AMXX]

Gear indicator (fake) [AMXX]

Current lap display [AMXX]

Best lap display [AMXX]

Position indicator [AMXX]

Countdown display [AMXX]

Race timer [AMXX]

Sector timer [AMXX]

Split difference indicator [AMXX]

Checkpoint missed warning [AMXX]

Finish banner [AMXX]

Results screen [AMXX]

Mini-leaderboard [AMXX]

Debug HUD [AMXX]

🔊 Audio System

Engine idle sound [AMXX]

Engine acceleration sound [AMXX]

Engine deceleration sound [AMXX]

Tire screech sound [AMXX/MM]

Boost sound [AMXX]

Countdown beep [AMXX]

Finish horn [AMXX]

Crash sound [AMXX]

🧱 Map Interaction

Start grid logic [MAP + AMXX]

Track boundaries [MAP]

Anti-shortcut detection [MAP + AMXX]

Jump pads [MAP + AMXX]

Banked turns [MAP]

Moving obstacles [MAP + AMXX]

Timing gates [MAP + AMXX]

Reset triggers [MAP + AMXX]

Visual signage [MAP]

Dynamic lights (start lights) [MAP + AMXX]

🧠 AI & Bots (Limited)

Disable bots [AMXX]

Spectator bots (optional) [AMXX]

Time-ghost replay (non-interactive) [AMXX]

⚙ Config & Admin

Server cvars [AMXX]

Per-map config [AMXX]

Admin restart race [AMXX]

Admin skip track [AMXX]

Admin force end [AMXX]

Player vote system [AMXX]

Debug mode toggle [AMXX]

Performance metrics [AMXX/MM]

Logging system [AMXX]

🧩 Metamod Extensions (Explicit)

Engine-level input filtering [MM]

Engine-level velocity control [MM]

Custom friction handling [MM]

Acceleration smoothing [MM]

Drift physics refinement [MM]

Ground contact enforcement [MM]

Jump suppression [MM]

Custom natives exposed to AMXX [MM]

🖥 Server Infrastructure

Linux server support [INFRA]

Auto-restart on crash [INFRA]

Log rotation [INFRA]

Asset fast-download [INFRA]

Map rotation logic [AMXX]

Version compatibility checks [AMXX]

🧠 Development & Tooling

Debug overlays [AMXX/MM]

Replay logging (server-side) [AMXX]

Performance profiling [MM]

Map validation tool [AMXX]

Plugin self-test mode [AMXX]

Versioned changelog [INFRA]
