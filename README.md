## Overview

ChristheDM's Shortcut Panel is a sleek overlay panel for Foundry VTT that gives the GM a fast way to organize and open important game content. Instead of relying on a separate manager window, the panel itself is the workspace: drag documents directly into it, sort them into visual categories, add dividers, and open what you need without digging through sidebars.

The module is built around a clean in-game UI with category cards, quick tab switching, drag-and-drop workflows, and player visibility controls.

## Main Features

### Overlay Shortcut Panel
- Floating in-game shortcut panel designed for quick access.
- Can be shown or hidden with:
  - the **Token Controls toggle button**, or
  - the default **Y hotkey**.
- Remembers panel visibility and active tab/category state.

### Supported Tabs
The panel supports separate tabs for:
- **Journals**
- **Actors**
- **Items**
- **Rolltables**
- **Macros**

### Arrow Carousel Tab Header
- Full-width top header for tab navigation.
- Left and right arrow controls cycle through tabs.
- When browsing categories, the current tab name is shown in the header.
- When inside a category, the header changes to **Back**, letting you return to the category browser.

## Drag-and-Drop Panel Management

### Add Shortcuts Directly to the Panel
The GM can drag supported Foundry documents directly into the active tab.

Examples:
- Drag an Actor into the **Actors** tab.
- Drag a Journal into the **Journals** tab.
- Drag an Item into the **Items** tab.

This replaces the old manager-based workflow for normal use.

### Keep Existing Data
- Existing saved shortcut data is preserved.
- Older saved entries remain available after upgrading to the current system.

## Categories

### Category Card Browser
Each tab opens into a visual category browser.

Features include:
- Rounded square category cards.
- **Two cards per row**.
- White centered category names with drop shadow.
- A default **All** card.
- A low-opacity **+ card** used to create a new category.

### Category Images
Each category can have its own artwork.

Right-click a category card to:
- rename it
- set or change its image
- align the image
- delete it

### Foundry File Browser Integration
- **Set Image** uses Foundry's native file browser so you can pick artwork directly.

### Category Image Alignment Tool
- Align category artwork inside the rounded square frame.
- Drag the image to reposition it.
- Use the mouse wheel to zoom in and out.
- The image remains clipped inside the category card bounds.
- Confirm to save the crop/alignment.

### Category Reordering
- GMs can drag one category card onto another to reorder categories.
- The cards swap positions when dropped.

## Entries Inside Categories

When a category is opened:
- the entry list uses the full available width
- the side rail is removed
- the top header changes to **Back**

### Shortcut Entries
- Individual shortcuts appear as their own styled buttons/cards.
- Clicking a shortcut opens the linked Foundry document.

### Dividers
- GMs can add dividers to break a category into sections.
- Divider labels are non-clickable organizational markers.
- Divider color can be customized.

### Scrollable Lists
- If a category contains enough entries to exceed the panel height, the list becomes scrollable.
- Entries no longer run off-screen.

## Entry Management Tools

Right-click a shortcut entry to manage it.

Available actions include:
- **Rename**
- **Send to Category**
- **GM Only / Visible to Players** toggle
- **Delete**

Right-click a divider to manage it.

Available actions include:
- **Rename**
- **Color**
- **Send to Category**
- **Delete**

### Reassign Entries by Drag and Drop
- Drag an existing panel entry onto a category to move it there.
- Drop a Foundry document directly onto a category card to add it straight into that category.

## Player Visibility Controls
- Entries can be marked **visible to players** or **GM only**.
- Players only see entries that the GM has allowed them to see.
- Player category browsing automatically hides categories that do not contain any visible entries.

## Canvas Drag-and-Drop

### Drag Actors to the Scene
- Actor shortcuts can be dragged from the panel directly onto the scene.
- Foundry handles the actor drop as normal canvas actor placement.

### Drag Items to the Scene
- Item shortcuts can be dragged from the panel onto the scene.
- Dropping an item creates a **Tile** using the item's art.
- Tile size is automatically scaled from the artwork proportions when possible.

## Quality-of-Life Features
- Clean overlay presentation designed for fast use during play.
- Context-sensitive behavior between category browsing and entry browsing.
- Organized per-tab structure.
- Built to keep the current visual layout intact while expanding functionality.

## Typical Workflow
1. Open the panel with the token control toggle or the **Y** hotkey.
2. Use the top arrow header to switch between tabs.
3. In a tab, click a category card such as **All** or a custom category.
4. Drag documents from Foundry into the panel to add shortcuts.
5. Use the **+ category card** to add more categories.
6. Right-click categories or entries to manage them.
7. Drag actors or items from the panel onto the scene when needed.

## Notes
- The old Shortcuts Manager has been retired from the normal workflow.
- The panel itself is now the primary management interface.
- This module is intended for **Foundry VTT v13**.

