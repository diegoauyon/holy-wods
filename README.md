# holy-wods

The box's daily programs as a read-only JSON feed, published automatically by an [openGym](https://github.com/Kinau-Guatemala/openGym) server each time a program is saved.

- Feed: `https://raw.githubusercontent.com/diegoauyon/holy-wods/main/feed.json`
- Format: `{ v: 1, box, updatedAt, programs: [{ date, title, tracks }] }` — programs only, never anyone's logs or personal data.
- Use it from the openGym app: Settings → CrossFit → Box feed, then paste the URL or scan the QR.
