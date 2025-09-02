
# 🚀 Discord Bot

[![Node.js](https://img.shields.io/badge/Node.js-16%2B-brightgreen?logo=node.js)](https://nodejs.org/)
[![Discord.js](https://img.shields.io/badge/discord.js-v14-blue?logo=discord)](https://discord.js.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?logo=mongodb)](https://www.mongodb.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A powerful and customizable **Discord Bot** built with [discord.js](https://discord.js.org), featuring **MongoDB database integration** for secure and structured data management.

---

## ✨ Features

* Full MongoDB integration for persistent storage.
* Flexible configuration via `config.js`.
* Advanced time handling with **moment.js**.
* Backup-ready using `pro.db`.
* Clean and modular code structure.

---

## 🛠️ Installation

```bash
git clone https://github.com/username/repo.git
cd repo
npm install
```

---

## ⚙️ Configuration

Edit `config.js` and fill in your details:

```js
module.exports = {
  prefix: "!",
  owners: ["your_id"],
  Guild: "your_server_id",
  mongoURL: "mongodb+srv://user:password@cluster.mongodb.net/dbname"
};
```

---

## ▶️ Run the Bot

```bash
node index.js
```

---

## 📦 Requirements

* Node.js **v16+**
* Libraries: `discord.js`, `pro.db`, `moment`, `ms`

---


---

## ⚡ Usage Examples

| Command   | Description                                                 |
| --------- | ----------------------------------------------------------- |
| `!top`    | Shows the top active users in voice and chat.               |
| `!check`  | Checks which members have the same role.                    |
| `!rooms`  | Displays how many staff members are outside voice channels. |
| `!setlog` | Automatically creates log channels.                         |

💡 *You can customize or add more commands easily in the `commands/` folder.*

---



🛠️ Installation

Clone the repository and install all required libraries at once:

git clone https://github.com/username/repo.git
cd repo
npm init -y
npm install discord.js pro.db moment ms

✅ After this,  can simply run:
npm install


🙏 Acknowledgements

We sincerely thank everyone who supported this project.
Special appreciation to the open-source communities of Discord.js, MongoDB, and related libraries.
Your feedback and trust made this bot possible!

## 📝 Notes

* The bot **automatically creates a MongoDB database** on the first run.
* Backup and local storage supported via `pro.db`.
