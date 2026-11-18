# Cannon Advisory Games

Official home for Cannon Middle School Advisory Games.

## Pages
- **Homepage:** `/`
- **5th Grade Gourd Derby race control:** `/gourd-derby/`
- **Advisory standings:** linked from homepage to the existing ThinkTank scoreboard.

## Hosting
Connect this GitHub repository to a new Netlify site. Use:
- Branch: `main`
- Base directory: repository root (leave blank)
- Build command: leave blank
- Publish directory: `.`

Changes committed to `main` are automatically deployed after the Netlify Git connection is configured.

## Scoring and data
Gourd Derby is linked to the existing TinkerHub Supabase project, with grade 5 data in `public.gourd_derby_states`. Visitors can view results; only approved TinkerHub admin users can modify results. Local browser mode is available for testing. Avoid counting local demos as official results.

## Authentication
For magic-link login, configure the Netlify production URL under **Supabase Auth → URL Configuration** as an allowed redirect URL. Test an authorized administrator login and a complete save/reload before official race day.

## Roadmap
Add the 6th, 7th, and 8th grade Gourd Derby races; Big Wheel Derby; Ponginator; and further advisory games.
