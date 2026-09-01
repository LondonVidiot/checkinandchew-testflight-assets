# Check In and Chew — TestFlight feedback screenshots

This repo exists **only** to host screenshots so they render inline in
GitHub issues on the private
[`LondonVidiot/CheckInAndChew`](https://github.com/LondonVidiot/CheckInAndChew)
repo. GitHub's raw content CDN (`raw.githubusercontent.com`) refuses
unauthenticated requests for private-repo files — even with a valid API
token, since a plain `<img>` tag can't carry an `Authorization` header —
so images committed to the private repo never actually render in issue
bodies. A public repo has no such restriction.

**Nothing here is app source code, and nothing here is secret.** It's
populated automatically by `scripts/sync_testflight_feedback.py` in the
main repo. Each file is named after its TestFlight feedback submission ID.

If a screenshot ever needs to come down (e.g. it shows something
sensitive), delete the file here and edit the referencing GitHub issue in
the private repo — this repo isn't otherwise linked to or discoverable
from anywhere public.
