# GroundZero Starter

This is the real repo behind Odyssey GroundZero's "Set up GitHub" onboarding task. There's no trick to the exercise - the point is practicing the exact workflow working engineers use every day: fork, clone, branch, commit, push, pull request.

## The task

1. **Fork this repo** - click "Fork" in the top right of this page. That gives you your own copy under your GitHub account.
2. **Clone your fork locally** - using the Git you just installed:
   ```
   git clone https://github.com/<your-username>/groundzero-starter.git
   cd groundzero-starter
   ```
3. **Make a branch** for your change (not strictly required by Git, but it's how real teams work):
   ```
   git checkout -b add-me
   ```
4. **Edit `CONTRIBUTORS.md`** - add a new row with your name and your real EverCloud ID (find it on your dashboard - it looks like `EC-2026-04829`).
5. **Commit and push** to your fork:
   ```
   git add CONTRIBUTORS.md
   git commit -m "Add <your name> to CONTRIBUTORS.md"
   git push origin add-me
   ```
6. **Open a pull request** from your fork's `add-me` branch back to **this** repo's `main` branch. GitHub will prompt you for this right after you push.
7. **Paste the real PR URL** into the "Set up GitHub" task on your OnCloudLearning dashboard.

That's it - one real commit, one real PR, the same shape as every PR you'll open for the rest of this programme.
