# 📊 Power BI Theme & Layout Configuration

![Power BI](https://img.shields.io/badge/Power%20BI-Theme-yellow?logo=powerbi)
![Status](https://img.shields.io/badge/status-active-success)
![License](https://img.shields.io/badge/license-MIT-blue)

A structured repository containing **Power BI report internals**, including themes, layouts, metadata, and configuration files.
This is useful for **custom styling, reverse engineering `.pbix` files, and standardizing dashboards**.

---

## 📌 Overview

This project helps you:

✨ Apply consistent branding across reports
🎨 Use custom themes with advanced styling
🔍 Understand Power BI internal structure
⚙️ Modify report layouts and configurations

---

## 🧱 Repository Structure

```id="9rx9lm"
.
├── 📁 DataModel/            # Tables, relationships, measures
├── 📁 DiagramLayout/       # Model view structure
├── 📁 Layout/              # Report pages & visuals
├── 📁 Metadata/            # Report metadata
├── 📁 SecurityBindings/    # Row-Level Security (RLS)
├── 📁 Settings/            # Report settings
├── 📁 Version/             # Version info
├── 📄 [Content_Types].xml  # Internal package definition
├── 🎨 CY26SU02.json        # Full custom theme
├── 🎨 AccessibleDefault.json # Accessibility theme
```

---

## 🎨 Theme Details

### 🌈 CY26SU02.json (Advanced Theme)

✔ 40+ custom colors
✔ Full visual customization
✔ Typography control
✔ Chart styling (bar, line, pie, etc.)
✔ Gridlines, axes, and layout tuning

💡 **Best For:** Enterprise dashboards, branding-heavy reports

---

### ♿ AccessibleDefault.json (Accessible Theme)

✔ High contrast colors
✔ Simplified palette
✔ Readability-focused
✔ Minimal design

💡 **Best For:** Accessibility compliance and clean dashboards

---

## ⚙️ How It Works

Power BI `.pbix` files are essentially compressed packages.
This repo represents the **decomposed structure** of such a file.

```id="rts0tx"
.pbix file
   ↓ (extract)
Internal JSON + XML files
   ↓
Modify / Version Control
   ↓
Rebuild / Apply Theme
```

---

## 🚀 Getting Started

### 🔹 Import Theme

1. Open **Power BI Desktop**
2. Navigate to:

   ```
   View → Themes → Browse for themes
   ```
3. Select one:

   * `CY26SU02.json`
   * `AccessibleDefault.json`

---

### 🔹 Modify Theme

* Open `.json` file in VS Code
* Update:

  * Colors
  * Fonts
  * Visual styles
* Re-import into Power BI

---

## 🛠️ Use Cases

| Use Case                     | Description                            |
| ---------------------------- | -------------------------------------- |
| 🎨 Branding                  | Apply consistent company colors        |
| 📊 Dashboard Standardization | Maintain uniform design across reports |
| 🔍 Reverse Engineering       | Understand `.pbix` internals           |
| 🔐 Security                  | Configure RLS via SecurityBindings     |
| ⚡ Optimization               | Fine-tune visuals and layouts          |

---

## ⚠️ Important Notes

⚡ These files are **not typically edited manually** unless you know the schema
⚡ Incorrect changes may break the report
⚡ Always keep a backup before modifying

---

## 🤝 Contributing

Contributions are welcome!

You can:

* Improve themes 🎨
* Add templates 📄
* Enhance accessibility ♿
* Optimize layouts ⚡

---

## 📄 License

This project is developed under the guidance of **ACE Academy (Sunstone)**.

---

## ⭐ Support

If you found this useful, consider giving it a ⭐ on GitHub!
