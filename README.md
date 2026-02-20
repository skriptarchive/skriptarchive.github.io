# Getting Started with SkriptArchive

Welcome to **SkriptArchive**, the community-driven library of Skript (Lang) scripts. This guide will help you quickly navigate, find, and use scripts.

---

## 1. Browsing Scripts

All scripts are organized into **categories** to keep the website clean and easy to navigate:

- **Admin** – moderation, permissions, server management  
- **Utility** – helpful commands or features for players  
- **Fun** – games, minigames, fun commands  
- **GUI** – graphical menus, buttons, inventories  
- **Economy** – shops, currencies, balances  
- **Events** – event-driven scripts for gameplay  
- **Functions** – reusable functions for other scripts  

> **Important:**  
> The sidebar only lists **categories**, not every single script.  
> You can find links to individual scripts **on the pages of each category**.  
> This keeps the sidebar clean and the site easy to navigate.

Each script page contains:  

- Description  
- Version & Requirements  
- Required Addons  
- Author  
- Tags  
- Copyable code block

---

## 2. Using Scripts

1. Go to the scripts category page in Docsify.  
2. Click on a script link to open its page.  
3. Copy the `.sk` file or download it from the [Scripts Repository](https://github.com/SkriptArchive/skripts).  
4. Place it in your server's `plugins/Skript/scripts` folder.  
5. Reload Skript with `/sk reload <script>` or `/sk reload all`.  

> ⚠️ Always test scripts on a development server before using them on your live server.

---

## 3. Contributing Scripts

We welcome new scripts from the community!  

- Fork the [scripts repo](https://github.com/SkriptArchive/skripts).  
- Add your `.sk` file following the standard format:
  - Description  
  - Version  
  - Author  
  - Addons (if required)  
  - Tags (utility, admin, fun, etc.)  
- Open a Pull Request to `main`.  
- PR title format: `[Category] Script Name` e.g., `[Utility] Fly Command`.  

> Maintainers will review scripts for proper format and functionality before merging.

---

## 4. File Standards

- Script filenames should be lowercase and hyphen-separated: `fly-command.sk`  
- Only the **script code** can include localized messages (e.g., German), but **all metadata and documentation must be in English**.  
- Optional subfolders for organization: `/gui`, `/admin`, `/economy`, etc.

---

## 5. License & Attribution

- All scripts are **MIT or CC0 compatible**.  
- Credit original authors when modifying or using scripts.  
- SkriptArchive is **community-driven** and **not affiliated with Mojang, Microsoft, or the official Skript plugin**.

---

🎉 You are now ready to browse, copy, and contribute scripts on SkriptArchive! Enjoy sharing and using scripts with the community.
