# Fortnite F + G Edit Combo

A Windows keyboard utility for a Fortnite setup that uses **F** to start an edit and **G** to select edit tiles. Built with AutoHotkey v2.

## Setup

1. In Fortnite's keyboard settings, bind editing to **F** and edit-tile selection to **G**.
2. Download and run the compiled `.exe`. The combo starts disabled each time you launch it.
3. Press **Ctrl + Alt + F8** to enable it. A brief on-screen message shows the current state.

## Controls

| Input | What happens |
| --- | --- |
| **Hold F** while enabled | Sends **F** immediately and adds **G** after a configured delay of **20 ms**. **G** stays held while you hold **F**. |
| **Release F** after a hold | Releases **G**. |
| **Ctrl + Alt + F8** | Toggles the combo. When disabled, **F** works normally. |

The combo works system-wide while enabled. To close the utility, right-click its icon in the Windows notification area and choose **Exit**.
