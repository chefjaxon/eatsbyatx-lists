# eatsbyatx-lists
EatsByATX's old client and chef pages. Since Oct 13, 2026 the pages live at
https://eatsbyatx.sousdesk.com/. menu.html, list.html and chef.html here only
forward to the same page there with the link's query string kept, so links
already sent keep working and an old page can no longer save a stale record.
schedule.html only says the schedule moved (every chef uses their coded
SousDesk link; the old page read a Make webhook that no longer answers without
SousDesk's key). This repo retires Fri Oct 30, 2026 or later.

text.html is still LIVE and must not be removed when this repo retires: it is the
tap-to-text page linked from every event on the "Client check-ins" Google Calendar
(Make scenario "EatsByATX — Daily Client Check-ins", 6983064). Move it to SousDesk
and update the PAGE constant in that scenario before turning off this site.
