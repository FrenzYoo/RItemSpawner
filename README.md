# RItemSpawner

RItemSpawner is an advanced **item spawner plugin** for Minecraft servers. Instead of spawning mobs, spawners automatically generate **items and experience**, making it ideal for Skyblock, Survival, and farm-based servers.

---

## ✨ Features

* 🧱 **Item-based spawners** (no mob spawning)
* 🎁 Custom item drops per mob type
* ⭐ Configurable XP rewards
* ⚙️ Fully configurable via **YAML files**
* 🎨 Hex color support for names and messages
* 🌍 Multi-language ready message system
* 🧩 Lightweight and performance-friendly
* ⛏️ **Silk Touch check** (optional)

---

## 🧠 How It Works

Each spawner is linked to a specific mob type, but instead of spawning the mob, it periodically produces configured items and experience points.

Drops and XP values are defined in `config.yml`, allowing server owners to fully control the economy and balance.

Spawner items also store owner information, making management clear and secure.

---

## ⚙️ Configuration

### `config.yml`

* Define item drops per mob type
* Set drop amount ranges
* Configure XP rewards
* Customize spawner item name and lore
* Edit mob display names

### `messages.yml`

* Prefix customization
* All player and admin messages
* Full hex color support

---

## 🔑 Commands & Permissions

### Player Commands

This plugin is primarily admin-focused and does not provide direct player commands by default.

---

### Admin Commands

All admin commands require the following permission:

* **Permission:** `ritemspawner.admin`

Admin commands:

* **`/ritemspawner give <player> <mob> <amount>`**
  Gives an item spawner of the specified mob type to a player.

* **`/ritemspawner delete`**
  Deletes the item spawner block you are currently looking at.

* **`/ritemspawner list`**
  Displays the total number of item spawners currently placed on the server.

* **`/ritemspawner reload`**
  Reloads the plugin configuration and messages files.

Aliases:

* `/ritemsp`
* `/rspawner`

---

## 🎯 Use Cases

* Skyblock servers with automated farms
* Survival servers wanting mob-free item generation
* Economy-focused servers
* Performance-optimized farm systems

---

## 🛠️ Technologies Used

* Java
* Spigot / Paper API
* YAML Configuration

---

## 🚧 Project Status

⚠️ **RItemSpawner is still under active development.**
New features and improvements are continuously being added.

---

## 📄 License

This project is distributed under its own license.

---

Feel free to open issues or suggest improvements!
