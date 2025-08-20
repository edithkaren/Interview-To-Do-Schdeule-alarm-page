# Interview-To-Do-Schdeule-alarm-page

A simple offline HTML + CSS + JS web page to manage interview reminders. Built for Rudraksh to track upcoming interviews and receive alarms directly in the browser.

🚀 Features

Add, Edit, Delete Tasks – Manage your interviews or other to‑do items.

Automatic Prefill – Four sample interviews (Quest Digiflex, American Chase, Integra Mania, Moreyeahs) are automatically created for tomorrow at 10:00, 12:00, 14:00, and 16:00 IST.

Alarms & Notifications – Rings a chime, shows a browser notification, and pops an alert when the time comes.

Reminder Offset – Set reminders early (5, 10, 15, or 30 minutes before the actual event).

Snooze – Postpone alarms by 5, 10, or 15 minutes.

Local Storage – All tasks are saved in your browser. They stay even if you close and reopen the tab.

Responsive Design – Works well on desktop and mobile.

🛠 How to Use

Open the index.html file in your browser (Chrome/Edge/Firefox recommended).

Grant notification permission when prompted.

Keep the tab open for alarms to work.

Use the input form to add new tasks:

Title → Task/Interview name.

Date & Time → Select interview time (defaults to tomorrow 10 AM IST).

Reminder → Choose how many minutes before you want the alarm.

Press Add.

Your tasks will show up in the list. You can:

Mark them Done/Undo.

Delete them.

Snooze them for 5, 10, or 15 minutes.

🔔 Alarm Behavior

At the scheduled time (or the chosen early reminder), you’ll get:

A sound chime (browser audio).

A notification popup (if notifications are allowed).

An alert box inside the page.

The page title also flashes “⏰ ALARM!” for extra visibility.

📦 Project Structure
Interview-ToDo-Alarm/
│
├── index.html   # Main web app (HTML + CSS + JS)
└── README.md    # Documentation (this file)
📅 Default Prefilled Interviews

Quest Digiflex — Tomorrow 10:00 IST

American Chase — Tomorrow 12:00 IST

Integra Mania — Tomorrow 14:00 IST

Moreyeahs — Tomorrow 16:00 IST

You can adjust the times as per your actual interview schedules.

⚠️ Notes

Notifications only work if you keep the page/tab open.

Works offline (no server required).

Tested in latest Chrome, Edge, and Firefox.

👨‍💻 Author

Built for Rudraksh Paliwal.
