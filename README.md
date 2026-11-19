# ssludge-radio
sSLudGe — 24/7 underground electronic music radio

## Checkpoint (recovery point)

From anywhere, after installing the terminal command once:

```bash
ssludge-checkpoint "describe what you are saving"
```

This commits any local changes, tags `checkpoint-YYYYMMDD-HHMM`, pushes `main` and the tag to `git@github-ssludge:sSLudGesSLudGe/ssludge-radio.git`, and optionally checks GitHub Pages.

**Install command (one time):**

```bash
chmod +x /Users/avery/Desktop/sSLudGe/ssludge-radio/tools/ssludge-checkpoint
ln -sf /Users/avery/Desktop/sSLudGe/ssludge-radio/tools/ssludge-checkpoint ~/.local/bin/ssludge-checkpoint
```

Override repo path with `SSLUDGE_ROOT`. Set `SSLUDGE_CHECKPOINT_VERIFY_PAGES=0` to skip the HTTP check.
