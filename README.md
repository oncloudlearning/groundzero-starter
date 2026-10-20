# GroundZero Starter

**An [OnCloudLearning](https://oncloudlearning.com) Odyssey: GroundZero resource.**

This repo is the real exercise behind Odyssey GroundZero's "Set up GitHub" onboarding task - the first real Git/GitHub workflow every participant completes, using the same fork → clone → branch → commit → push → pull request shape you'll use for every PR for the rest of the programme. There's no trick to it - the point is practicing the real workflow, not the edit itself.

## Who this is for

Anyone enrolled in OnCloudLearning's Odyssey: GroundZero pathway, working through the "Set up GitHub" task on their dashboard.

## About OnCloudLearning, Odyssey, and EverCloud

OnCloudLearning is the real learning platform and the owner of this programme. Odyssey is the practical engineering experience programme it runs, and GroundZero is Odyssey's foundations pathway. Some later GroundZero exercises are set inside **EverCloud Technologies** - a *fictional* organisation used purely as a realistic simulation backdrop for engineering scenarios, tickets, and environments. EverCloud doesn't own this repo, this programme, or OnCloudLearning itself.

## Prerequisites

- Git, installed locally (the "Prepare your workstation" onboarding task)
- A GitHub account
- A text editor - VS Code is what the workstation-prep task installs, but any editor works

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

## Next steps

Once your PR is open, paste its URL into the "Set up GitHub" task on your dashboard - it's checked against this repo for real (not just a self-reported checkbox) before the task marks itself done. From there, head back to your dashboard to continue onboarding and unlock your first real mission.

That's it - one real commit, one real PR, the same shape as every PR you'll open for the rest of this programme.
