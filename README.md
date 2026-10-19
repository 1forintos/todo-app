# TODO // SYS — User Manual

A lightweight, distraction-free, terminal-themed To-Do app designed for Android phones and desktop browsers. Built as a 100% self-contained offline application with zero server dependencies.

---

## 📱 How to Install on Android

### Option A: Via GitHub Pages (Recommended)
1. Push `index.html` to a GitHub repository and enable **GitHub Pages** in repository settings.
2. Open your GitHub Pages link in **Google Chrome** on your Android phone.
3. Tap the **⋮** menu in the top right corner.
4. Select **Add to Home screen** (or **Install app**).
5. The app will install with its custom amber checkbox icon and launch full-screen without browser address bars.

> **Offline Guarantee:** All tasks are stored exclusively on your device inside browser storage (`localStorage`). No data is sent to GitHub or any server.

---

### Option B: As a Local File (`file:///`)
1. Copy `index.html` and `icon.png` to your phone's storage.
2. Open `index.html` in Chrome.
3. *(Optional custom icon)* Use an app like **Shortcut Maker** (from Google Play Store) to create a home screen shortcut to the file and select `icon.png` as its icon.

---

## ⚡ Features & Usage

### 1. Creating and Managing Lists
* **Switch Lists:** Tap any list tab at the top (`DAILY`, `PROJECTS`, `SUPPLIES`, etc.) to switch views.
* **Active Counter:** The number in parentheses on each tab shows how many uncompleted tasks remain.
* **New List:** Tap `+ NEW LIST`, enter a name in the dialog, and tap **CONFIRM**.
* **Delete List:** Open `⚙ ACTIONS ▾` and select `[DELETE CURRENT LIST]`.

---

### 2. Adding Tasks
* At the bottom of the screen, tap the `> enter new task...` field.
* Type your task description and tap `[+] ADD` (or press **Enter** on your keyboard).
* Newly added items appear immediately at the top of the active list.

---

### 3. Completing Tasks
* **Complete an item:** Tap directly on the square checkbox on the left of any task.
* **Animation:** The checkbox will fill with an amber checkmark `✓`, smoothly fade out, and the items below will slide up into place.
* **Text Selection:** Tapping or selecting the task text will **not** complete the task, preventing accidental check-offs while scrolling.

---

### 4. Viewing and Restoring Completed Tasks
* In the bar below the list tabs, check the **`COMPLETED (count)`** checkbox.
* Completed tasks will be displayed in place with strikethrough text.
* Tap the checkbox of any completed task to **uncheck** and restore it back to the active list.

---

### 5. `⚙ ACTIONS ▾` Menu
Located next to the `COMPLETED` toggle:

| Action | Description |
| :--- | :--- |
| **`[EXPORT JSON]`** | Downloads a `.json` backup file of all your lists and tasks. |
| **`[RESTORE JSON]`** | Restores your lists and tasks from a previously saved backup file. |
| **`[DELETE CURRENT LIST]`** | Deletes the active list and all tasks inside it. |
| **`[PURGE COMPLETED]`** | Permanently deletes all completed items in the current list. |
| **`[PURGE ALL IN LIST]`** | Clears all tasks (both active and completed) from the current list. |

---

## 💾 Backup & Data Privacy

* **100% Offline & Private:** All your data remains in your device's `localStorage`.
* **Backups:** Because clearing your browser data will delete local storage, it is recommended to periodically use `[EXPORT JSON]` to save a backup copy to your device or cloud drive.

