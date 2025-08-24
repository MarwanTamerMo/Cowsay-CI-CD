# 🐲 Unleash the Dragon CI 🐲

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/MarwanTamerMo/Cowsay-CI-CD/workflow.yaml)
![Self-Hosted Runner](https://img.shields.io/badge/runner-self--hosted-blueviolet?style=for-the-badge)

Welcome! This project summons a mighty ASCII dragon using the power of **GitHub Actions** and a **self-hosted runner** on your very own machine. 🖥️🔥

When you push a commit, this workflow awakens your local machine, which then runs a script to bring the dragon to life in the job logs.

***

### ✨ The Grand Finale ✨

Here's a preview of the magnificent creature you'll be summoning:

Of course. Here is the complete text formatted in raw Markdown.

You can copy this entire block of code and paste it directly into your README.md file on GitHub.

Markdown

# 🐲 Unleash the Dragon CI 🐲

![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/YOUR_USERNAME/YOUR_REPO/main.yml?style=for-the-badge&logo=githubactions&logoColor=white)
![Self-Hosted Runner](https://img.shields.io/badge/runner-self--hosted-blueviolet?style=for-the-badge)

Welcome! This project summons a mighty ASCII dragon using the power of **GitHub Actions** and a **self-hosted runner** on your very own machine. 🖥️🔥

When you push a commit, this workflow awakens your local machine, which then runs a script to bring the dragon to life in the job logs.

***

### ✨ The Grand Finale ✨

Here's a preview of the magnificent creature you'll be summoning:

< Run for cover, i am a Dragon >

![Dragon](../assets/dragon.png)

***

## 🖥️ Mission Control: Managing Your Runner

Your local runner is the gateway for the dragon. It must be online to receive jobs from GitHub.

#### ▶️ To Power Up the Runner:

1.  Navigate to your `actions-runner` directory.
2.  Launch the runner script:
    ```bash
    ./run.sh
    ```
    You'll see a `Listening for Jobs` message. Your portal is now open!

#### ⏹️ To Power Down the Runner:

Simply press `Ctrl+C` in the runner's terminal window.

> **⚠️ Important:** The workflow will wait indefinitely for a runner to come online. If your job is "stuck," make sure your runner is active!

***

## 🔄 Re-launch the Dragon

Want to see the magic again? You can re-trigger the workflow in a couple of ways:

* **📤 Push It Real Good**: Push any new commit to the `main` branch.
* **✨ Manual Override**: Go to the **Actions** tab in your GitHub repo, select **Dragon ASCII Art**, and click the **Run workflow** button.

---

**Note:** Remember to replace `YOUR_USERNAME/YOUR_REPO` in the status badge URL at the top of the file with your actual GitHub username and repository name to get a working status badge!
