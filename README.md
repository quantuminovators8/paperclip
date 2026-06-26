Great choice! 🍎 This setup keeps Ubuntu looking clean and macOS-inspired while staying easy to maintain.

> **Before you start**
> Open a Terminal (`Ctrl` + `Alt` + `T`) and update your system:
>
> ```bash
> sudo apt update && sudo apt upgrade -y
> ```

---

# Step 1: Install GNOME Tweaks & Extensions

```bash
sudo apt install gnome-tweaks gnome-shell-extensions gnome-shell-extension-manager git wget curl unzip -y
```

This installs:

* ✅ GNOME Tweaks
* ✅ Default GNOME extensions
* ✅ Extension Manager
* ✅ Git

---

# Step 2: Install the Inter Font

```bash
sudo apt install fonts-inter -y
```

Then later you can select **Inter** inside **GNOME Tweaks → Fonts**.

---

# Step 3: Install WhiteSur Theme

Clone the official repository:

```bash
git clone https://github.com/vinceliuice/WhiteSur-gtk-theme.git
```

Go inside:

```bash
cd WhiteSur-gtk-theme
```

Run the installer:

```bash
./install.sh
```

For the modern rounded version:

```bash
./tweaks.sh -f
```

---

# Step 4: Install WhiteSur Icons

Go back:

```bash
cd ..
```

Clone:

```bash
git clone https://github.com/vinceliuice/WhiteSur-icon-theme.git
```

Install:

```bash
cd WhiteSur-icon-theme
./install.sh
```

---

# Step 5: Install WhiteSur Cursor

Back again:

```bash
cd ..
git clone https://github.com/vinceliuice/WhiteSur-cursors.git
```

Install:

```bash
cd WhiteSur-cursors
./install.sh
```

---

# Step 6: Install Dash to Dock

Ubuntu usually already includes it.

Open:

**Extension Manager**

Search:

```
Dash to Dock
```

Click:

**Install**

Recommended settings:

* Position → Bottom
* Center Icons
* Intelligent Auto-hide
* Icon Size → 56 px

---

# Step 7: Install Blur My Shell

Open **Extension Manager**

Search:

```
Blur My Shell
```

Install it.

Recommended:

* Blur Top Panel
* Blur Overview
* Blur Dash
* Medium blur radius

---

# Step 8: Enable User Themes

Open **Extension Manager**

Enable:

```
User Themes
```

This allows GNOME to use custom shell themes.

---

# Step 9: Apply Everything

Open:

```
GNOME Tweaks
```

Go to **Appearance**.

Set:

| Setting      | Value    |
| ------------ | -------- |
| Applications | WhiteSur |
| Icons        | WhiteSur |
| Cursor       | WhiteSur |
| Shell        | WhiteSur |
| Legacy Apps  | WhiteSur |

Then go to **Fonts**:

Interface Font

```
Inter Regular 11
```

Document Font

```
Inter Regular 11
```

Monospace

```
JetBrains Mono 11
```

(Optional but looks excellent.)

---

# Step 10: Wallpaper

Download any macOS Sonoma, Sequoia, or Big Sur wallpaper.

Right-click it:

```
Set as Wallpaper
```

---

# Step 11: Make Ubuntu Feel Even More Like macOS

In **Settings → Multitasking**:

* Enable Hot Corner
* Enable Workspaces

In **Settings → Appearance**:

* Dark Style (optional)

---

# Step 12: Restart GNOME

Log out and log back in.

Or press

```
Alt + F2
```

Type

```
r
```

Press Enter.

> **Note:** The `Alt + F2` → `r` restart shortcut only works on X11 sessions, not Wayland. If you're using Wayland (the default on many Ubuntu installations), simply log out and back in.

---

# Optional: Install macOS-style window buttons

Inside the WhiteSur theme directory:

```bash
./tweaks.sh -F
```

This moves the close/minimize/maximize buttons to the left like macOS.

---

## 🎉 Final Result

You'll have:

* ✅ macOS-style dock
* ✅ Apple-like icons
* ✅ Apple-inspired window theme
* ✅ Rounded windows
* ✅ Blur effects
* ✅ Inter font
* ✅ Modern GNOME desktop
* ✅ Full Ubuntu stability

If you want to go even further, I can also help you add:

* 🍎 a global menu like macOS,
* 🍎 a Spotlight-style app launcher,
* 🍎 animated window effects,
* 🍎 and a Launchpad-style application grid—while keeping Ubuntu stable and update-friendly.
