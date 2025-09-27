# UI-UX-Experiment3
```
NAME:PRAVEEN SANTHALINGAM M
REGISTER NO: 212224040246
```
## Aim:
The aim of this experiment is to apply heuristic evaluation of existing websites or apps and redesign them by combining features of two competing applications to improve the overall user experience.
## Algorithm:
```

Start Application

Load the app interface with three main tabs: Chats, Status, and Settings.

Display navigation bar with active tab highlighted.

Tab Switching

When user clicks a tab:

Deactivate all other tabs.

Activate the clicked tab.

Show its content section, hide others.

Chats Section

Display list of chat items with avatars, last message, and time.

When a chat is clicked:

Open the conversation view.

Show messages in bubble style (sent = right, received = left).

Composer:

On typing, enable Send button.

On send, append new bubble, clear input.

Upload Flow:

If a file is uploaded → show upload card with:

progress bar, estimated time, Pause/Cancel.

On pause → stop upload simulation.

On cancel → remove upload card.

On completion → replace with success message.

Delete Action (2-step safe delete)

User clicks Delete on chat/message →

Step 1: show confirmation modal (Delete / Backup & Delete / Cancel).

Step 2: if Backup & Delete chosen → save to "Archive" before deleting.

Show Toast notification with "Undo" option.

If Undo clicked → restore message from archive.

Status Section

Split into Your Status (user’s posts) and Suggested Status (contacts’ updates).

On click, open fullscreen preview with back button.

Settings Section

Show categorized setting items (Privacy, Notifications, Account).

Provide Search bar → filter settings dynamically.

Enlarged touch areas for accessibility.

Error Handling

If action fails (e.g., upload error):

Show toast or inline error with description + suggested fix.

Example: “Upload failed. Retry or check network.” with Retry button.

Privacy Onboarding

On first launch, display modal explaining privacy settings.

Require user to Accept / Skip.

Save preference in localStorage (simulate persistence).

Accessibility Features

Ensure all buttons ≥ 44px.

Use ARIA labels for icons.

Provide keyboard focus styles for navigation.

End Application

User can navigate back and forth between tabs.

App state (chats, statuses, settings changes) persists until page reload.
```
## Output:
<img width="1571" height="953" alt="image" src="https://github.com/user-attachments/assets/6defcf70-94da-421b-92f9-ba9c85704cf1" />

## Result:

succesfully analyzed and deployed .
