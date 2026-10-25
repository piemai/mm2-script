# KYUZXC MM2 [V1.0]

High-performance, feature-rich Murder Mystery 2 script featuring a modern resizable acrylic UI, robust combat assists, visual ESP suites, and anti-kick farming tools.

---

## Features

### 1. Visuals
* **Role ESP:** Color-coded overhead tags (Red = Murderer, Blue = Sheriff, Green = Innocent).
* **Box ESP:** Dynamic 3D screen-space bounding boxes matching player roles.
* **Skeleton ESP:** Live 3D bone-to-joint rig rendering through walls.
* **Tracer ESP:** Snaplines pointing directly to players.
* **Gun Drop ESP:** Real-time tracking of dropped sheriff revolvers.
* **Coin ESP:** Highlight markers for active map coins.

### 2. Combat & Brutal
* **Knife Kill Aura:** Automatic 20-stud range knife strike using `firetouchinterest`.
* **FOV Silent Aim Circle:** Adjustable field-of-view visual circle for target locking.
* **Sheriff Silent Aim:** One-tap or floating button execution that predicts target movement and fires the gun.

### 3. Player & Movement
* **Anti-Fling Protection:** Nullifies angular and rotational velocity to prevent lobby fling exploits.
* **Speed Hack:** Lockable custom walkspeed.
* **Infinite Jump:** Mid-air jumping without cooldowns.
* **Unbreakable Noclip:** Physics-stepped collision removal that works across all map geometry.
* **Safe Spawn Teleport:** Warps you safely above map spawn points without clipping underneath.

### 4. Farming & Teleports
* **Safe Tween Coin Farm:** Anti-kick interpolated coin collection with zero rubberbanding.
* **Auto-Grab Dropped Gun:** Snatches dropped weapons instantly and snaps you back to origin.
* **Auto-Rejoin:** Automatically re-queues when rounds end.
* **Player TP Dropdown:** Dynamic scrolling list to instantly teleport to any player in the server.

---

## Usage
Execute via any supported executor. Use the bottom-right corner handle (`◢`) to resize the UI to fit any device screen.

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/piemai/mm2-script/refs/heads/main/mm2%20script%20AUTO%20KILL"))()
