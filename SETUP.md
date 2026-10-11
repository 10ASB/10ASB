# ASB-10 Multiverse GitHub Profile — Setup

## Files
- `README.md`: Marvel-inspired profile layout and verified project links.
- `.github/workflows/arcade.yml`: GitHub Actions workflow to generate the Pac-Man contribution animation.
- `assets/README-ASSET-NOTE.txt`: reminder for the banner artwork.

## Install
1. Download and extract this ZIP.
2. Open your special profile repository: https://github.com/10ASB/10ASB
3. Upload/replace `README.md` at the repository root.
4. Upload `.github/workflows/arcade.yml` while preserving the folder path.
5. Add your banner image as `assets/multiverse-banner.png` (or change the image path in README.md).
6. In the repository, open Settings → Actions → General. Ensure workflows are allowed and the workflow has permission to write repository contents. The workflow declares `contents: write`.
7. Open Actions → “Generate multiverse arcade” → Run workflow. Wait for success.
8. Reload your profile. The arcade image may take a little while to appear.

## Notes
- The README can display images and widgets, but it cannot run arbitrary JavaScript or webpage animations.
- The Pac-Man action uses a third-party GitHub Action. Review its source and pin it to a commit SHA if you want stronger supply-chain control.
- This does not modify your GitHub account automatically. Upload/commit these files yourself.
