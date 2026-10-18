# heptabase-assets

Self-hosted images that are embedded in Heptabase cards, so the links never rot.
Files are added automatically by the `note-to-heptabase` skill in
[lesh-marketplace](https://github.com/LeshLiao/lesh-marketplace).

## Layout

```
images/<YYYY>/<MM>/<yyyymmdd>-<kebab-topic>.<ext>
```

Example: `images/2026/10/20261018-android-activity-lifecycle.png`

## Rules

- Public repo on purpose: Heptabase loads images from the raw URL
  `https://raw.githubusercontent.com/LeshLiao/heptabase-assets/main/<path>`.
- Never overwrite or rename an existing file; cards already point at it. Add `-2`, `-3`, … instead.
- Keep each image under 5 MB.
