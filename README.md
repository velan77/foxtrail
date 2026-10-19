# Foxtrail

Foxtrail is a small, responsive campus adventure for curious minds. Visitors can pick a short creative, social, or exploration quest, read its prompt, and mark it complete to collect curiosity points.

## Run it

Open `index.html` in a browser. There is no build step or account required.

## Design decisions

- **A gentle starting point:** the concept turns a blank “what should I do?” moment into a few approachable, time-boxed invitations.
- **Warm night-campus palette:** charcoal surfaces keep the page calm, while fox-orange and sunset tones guide attention toward the next action. The illustrated trail gives the experience a sense of place without needing campus-specific assets.
- **Progress with no pressure:** each quest shows its time and reward up front. Completion feedback is celebratory but small, and saved progress lives in the browser with `localStorage`.
- **Small-screen friendly:** the sidebar simplifies on mobile, cards adapt to the viewport, and controls remain easy to reach.
- **Lightweight implementation:** plain HTML, CSS, and JavaScript keep the experience easy to inspect and run. Quest content is mock data in `script.js`.

## Interactions

- Filter quests by creative, social, and explore.
- Open a quest to read its full prompt and completion details.
- Complete a quest to update points, minutes, and quest count.
- Use **Surprise me** to open a random unfinished quest.
- Progress persists in the current browser.
