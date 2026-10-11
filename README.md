# beequation-media

Public media for Beequation's daily social posts, served at https://trettbob.github.io/beequation-media/ so the
scheduler (Metricool) can fetch each file by link.

Files are made by the renderer in the growth folder (`growth/renderer`, `--push <this folder>`), one folder per
puzzle: `<YYYY-MM-DD>/`, `<YYYY-MM-DD>-kids/` or `practice-<seed>/`, each with `question-square.png` (1080×1080),
`question-portrait.png` (1080×1350), `question-pin.png` (1000×1500), `question-video.mp4` (1080×1920),
`answer-*.png` and `puzzle.json`.

Don't edit files here by hand; re-render instead.
