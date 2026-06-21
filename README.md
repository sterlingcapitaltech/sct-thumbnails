# SCT Thumbnails — public asset host

Public CDN for **Sterling Capital Technologies** YouTube thumbnails. These PNGs are served
via raw GitHub URLs so tools (e.g. the YouTube "Update Video Thumbnail" automation) can fetch
them by URL.

This repo is **public on purpose** — it contains only finished thumbnail images, which are
public on YouTube anyway. No source, configs, or business data live here; the working
material stays in the private `claude-workspace` repo.

Each video has a `1280x720` master (YouTube's recommended size, ~0.5 MB) and a `2560x1440`
hi-res version. Built to the brand standard (Terminal B type system, navy + gold, shield
lockup). Raw URL pattern:

```
https://raw.githubusercontent.com/sterlingcapitaltech/sct-thumbnails/main/<file>.png
```
