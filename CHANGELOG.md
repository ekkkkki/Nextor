# Changelog

All notable changes to Nextor.

## v1.0.0 — 2026-06-07

First public release of **Nextor** — a free, open-source macOS menu-bar app for Apple Reminders
and Calendar. Press **⇧⌘A** from any app to see what's next and add what's new.

### Glance + capture
- **Opens to your agenda** — overdue, today and the next few days, grouped by day. Complete,
  delete or reschedule items right in the panel.
- **Natural-language capture** in **English / 中文 / 日本語** — type the way you think and Nextor
  files a Reminder or Calendar event, parsing the time, duration, range, location, priority,
  list, tags and recurrence.
- **Reminder vs. event, decided automatically** — a time range or duration, or a place / meeting
  word, makes it a Calendar event (with the address pulled out as the location); otherwise a
  Reminder.
- **Paste a long event page** (an invite, a webpage) and Nextor extracts the event name, time and
  location, keeping the rest as notes.
- **Smart search** across Reminders and Calendar with a small filter language
  (`is:event due:week ~Work #urgent !!`), with inline complete / reschedule / delete.

### Built for speed
- Pre-warmed panel (first ⇧⌘A is instant), cached date formatting, a single store fetch per open,
  debounced parsing, and an IME-safe input field — smooth even with a long agenda or a big paste.

### Private & native
- Everything runs locally and writes directly to Apple Reminders / Calendar. Optional on-device
  Apple Intelligence refinement is opt-in. No account, no tracking, no subscription. MIT licensed.
