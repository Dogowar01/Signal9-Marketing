# Signal9 Social Studio — Version 3

Personal iPhone-first, offline-capable PWA for Signal9 Studios.

## V3 additions
- Refined premium editorial visual styling and clearer focus states
- Separate optional Facebook, Instagram and TikTok caption versions
- One-tap copy buttons for master or platform-specific captions
- Local marketing task manager with categories, priority, due dates and completion

## Included
- Dashboard and publishing pipeline
- Content studio with local image attachments
- Monthly publishing calendar
- 18 marketing prompts
- Manual performance tracking
- Campaign manager
- Artwork catalogue with print details and images
- Caption templates and hashtag collections
- Full JSON backup and restore, including image attachments
- PWA manifest, service worker and home-screen icons

## Limitations
- No automatic publishing, social account login, live analytics or platform API integration.
- Analytics and follower counts are manually recorded.
- Caption templates and prompts are local content, not AI-generated.
- Data is stored in this browser's IndexedDB. Export backups regularly; clearing Safari website data can erase local records.
- Public repository contains app code only, never private backups or business data.

## Publish on GitHub Pages
1. Create a public repository named `signal9-social-studio`.
2. Upload the contents of this folder to the repository root (index.html must be at root).
3. In repository Settings → Pages, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
4. Open the published HTTPS address in iPhone Safari → Share → Add to Home Screen.
5. Open the installed app once while online so its service worker can cache the app.

## Updating
Replace repository files with the new version and commit. The service worker cache is versioned and refreshes when the app is next opened online.
