# Code Audit Summary

Open these, in order:

1. **02_largest-files.txt** – remove/move files >5–10 MB if not essential.
2. **08_largest-images.txt** – resize/compress, convert to WebP where possible.
3. **05_css-classes-unused-candidates.txt** – candidates for CSS cleanup (verify before deleting).
4. **07_js-maybe-unused.txt** – JS not referenced by HTML (verify dynamic loads).
5. **04_duplicates.txt** – dedupe assets.
6. **03_possible-bloat.txt** – backups/archives/raw uploads to ignore or relocate.

After pruning:
- Stage/commit/push changes from this `code-audit` branch.
- Open a Pull Request into `main`.
