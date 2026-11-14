# Daily Game Factory

The gallery of every game from the Daily Game Factory: three new, original browser games every day.

**Live site:** https://games.getsimpleinvoice.app/

Each game has its own repo and is hosted at `https://elivoronov-ctrl.github.io/<slug>/`. To add games, add entries to the `GAMES` array in `index.html` and their screenshots to `shots/`.

## Feedback

The site has a **Feedback & ideas** form (`#feedback`, or `#feedback=<slug>` to preselect a game; each game card has a "Report a bug" link). Submissions go to the `public.feedback` table in the `flight5` Supabase project through the `submit_feedback` RPC function. The public key can only call that function: it can't read the table or write to it directly. Name and email are optional. Columns `status` (`new` → `triaged` / `in_progress` / `done` / `used` / `wontfix` / `spam`), `notes` and `handled_at` are there for follow-up jobs.
