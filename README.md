## Set up on your computer

1. Install [Git](https://git-scm.com/downloads) ([Git for Windows](https://gitforwindows.org/) on Windows), [Deno 2.9.7](https://docs.deno.com/runtime/getting_started/installation/), and a code editor. If you use VS Code, install its [Deno extension](https://marketplace.visualstudio.com/items?itemName=denoland.vscode-deno). Check `git --version` and `deno --version` in a _new_ terminal window after installation.
2. Clone your newly created repository onto your own computer and open that folder in your editor. Do not clone the instructor's template as your submission.
3. Run `deno task setup` from the repository root to enable the pre-commit checks. Use the same command on macOS and Windows, including PowerShell. Run it once for each new clone.
4. Run `deno task dev` and open the local address it prints. Try the button before editing.
5. Make your own change to the button handler in `src/main.ts`. Make its effect visible on the page, test it locally, and run `deno task ci` before committing and pushing to GitHub.
6. Replace this README with a short description of **your** project and what you changed. Keep useful setup instructions if you like.

Section Activity:
I made the counter button interactive upon clicking in this project.
Page begins with a counter at 0, and then updates by +1 through counter++ whenever the button is clicked, and updates visually using counterElement.textContent

## Publish the page

In **your repository**, open **Settings → Pages → Build and deployment** and set **Source** to **GitHub Actions**. Push a commit to `main`, then check the **Actions** tab for a successful deployment. The published URL should look like `https://<your-username>.github.io/<your-repository>/`. Open it and check that the button works there too. GitHub Actions may need to be enabled on a new repository before the workflow runs.

For S01, submit the **repository URL**, not just the Pages URL, in the Canvas quiz. The teaching team checks the repository, workflow run, published page, code change, and README before awarding credit. If your computer cannot run the project, talk with your TA during section and describe what you tried in your quiz response.
