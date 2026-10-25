# Sammy Motion Works — Website Starter

A functional **static browser prototype**. No account, build process, or server required to try it.

## Open locally

Open `index.html` in a modern browser. Choose a local video, add cues, and preview virtual motion. Use Export to save `.smwtrack` files.

## Host publicly

Upload `index.html`, `style.css`, and `app.js` together to a static hosting service (for example GitHub Pages or Netlify). Use HTTPS when published. This package does not automatically publish a site or reserve a domain.

## Implemented

- Responsive navigation for desktop/mobile
- Local browser video player
- Timed pitch/roll/vibration cue editor with import/export
- Virtual seat animation synchronized to video playback
- Audio amplitude-based *suggested vibration cues* (not physical-motion detection; browser codec and file-size limits apply)
- Series/episode cue organization in browser localStorage
- Game cue project creation and virtual motion demo
- Local-only marketplace gallery
- Non-spendable illustrative Sammy Token earnings timer

## Not implemented

- Public marketplace uploads or moderation
- User identity, verified creator badges, token balances, transactions, or anti-cheat backend
- Real rig hardware, manufacturer adapters, safety validation
- Live game telemetry
- Direct commercial DVD/Blu-ray playback, protected streaming playback, or content hosting

The project uses localStorage for cue drafts and local gallery. Clearing browser data loses them; export important cue tracks. Uploaded video is not sent anywhere.

## Future architecture

Add an authenticated API for community uploads and server-verified token awards. Validate and moderate uploaded track metadata; enforce file-size and rate limits. For physical rigs, develop independent manufacturer-approved adapters and safety systems. Do not trust cue values directly as actuator commands.
