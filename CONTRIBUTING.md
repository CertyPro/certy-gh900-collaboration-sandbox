# Contributing

Thank you for taking part. This sandbox is built for first-time contributors, so
do not worry about getting everything perfect. Follow the steps and ask if you get
stuck.

## The workflow, step by step

1. **Fork** this repository to your own account.
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<your-username>/certy-gh900-collaboration-sandbox.git
   cd certy-gh900-collaboration-sandbox
   ```
3. **Create a branch** for your change:
   ```bash
   git switch -c add-<your-username>
   ```
4. **Make your change.** For the standard exercise, add one line about yourself to
   `CONTRIBUTORS.md` in the format shown there.
5. **Commit** with a clear message:
   ```bash
   git add CONTRIBUTORS.md
   git commit -m "Add <your-username> to contributors"
   ```
6. **Push** the branch to your fork:
   ```bash
   git push -u origin add-<your-username>
   ```
7. **Open a pull request** from your fork back to this repository. Fill in the
   template and reference the issue you picked, for example `Closes #2`.
8. **Respond to review.** A maintainer may suggest a change. Push another commit to
   the same branch and it updates the pull request automatically.

## What makes a good pull request here

- It changes only what the issue asked for.
- It has a clear title and description.
- It links the issue with a closing keyword.
- It is small and easy to review.

## Need help?

Open a **Discussion** with your question. There is no such thing as a silly
question in a learning sandbox.
