# Publish the Liresh profile README

1. Open `https://github.com/lireshnv/lireshnv`.
2. Replace the repository's `README.md` with this package's `README.md`.
3. Upload the entire `assets/` folder, keeping the project image filenames unchanged.
4. Upload `.github/workflows/snake.yml` into the same path in the repository. Keep your existing workflow if it does something else.
5. In GitHub, open **Settings → Actions → General → Workflow permissions** and allow read/write permissions if the snake workflow cannot publish its `output` branch.
6. Open **Actions → Generate contribution snake → Run workflow**. It creates/updates the `output` branch used by the README snake images.

The README uses JetBrains Mono for the animated banner and typing line. GitHub controls the body font, so the rest of the profile uses compact Markdown/HTML typography.

The LeetCode badge points to LeetCode's homepage because a personal LeetCode username has not been verified. Replace `https://leetcode.com/` with your profile URL when available.
