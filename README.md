# field-drill-status

Public status file for **Field Drill**, a study app for San Francisco EMS protocols.

Once a month, an automated check compares the app's content against the SF EMS Agency protocols. `status.json` lists each source protocol's title, effective date, when it was last checked, and whether it has changed since. The app reads this file to show "last checked" dates and to warn when a protocol was updated.

It contains no personal data. Field Drill is for study only and is not affiliated with the SF EMS Agency.
