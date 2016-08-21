# Brackets No Distractions Advanced Toolbar View
Extends the "No Distractions" view to display the sidebar when pointing at the left side of the editor and the toolbar when pointing at the right side.


## Installation
Open the [Extension Manager](https://github.com/adobe/brackets/wiki/Brackets-Extensions) (File → Extension Manager), search for "No Distractions Advanced Toolbar View" and hit install.

## Usage
Enable the "No Distractions" view (View → No Distractions Toolbar View) and point to the left/right edge of the editor.

## Options
The extension provides two display modes: **overlay** (default) and **push**. In **overlay** mode, the sidebar/toolbar will be on top of the content area (see image above), while in **push** mode, the content area will be pushed off-canvas (see image below).


To set the mode, open the Preferences file (Brackets → Preferences) and add the following setting:

``"no-distractions-advanced.mode": "push"``
``"no-distractions-advanced.mode": "overlay"``

``"no-distractions-advanced.rightSideViewMode": "visible"``
``"no-distractions-advanced.rightSideViewMode": "hidden"``
