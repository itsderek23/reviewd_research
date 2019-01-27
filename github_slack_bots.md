# List of GitHub Slack Bots

A list of Slack bots that interact with GitHub.

## Reminders

There are several bots dedicated to reminding your team of open pull requests and review requests.

### Closed Source (hosted)

#### [Pull Reminders](https://pullreminders.com)

Posts a daily message to Slack with outstanding review requests. Can also be configured to send realtime messages on PR comments, mentions, and more. 

Pricing starts at $14/mo and is free for open-source, non-commercial projects.

#### [Loolp](https://www.loolp.com/)

Notifies Slack members of review requests and completed reviews. These messages appear to be in realtime - there is no daily reminder like Pull Reminders, Seal, or Slack Pull Reminders.

#### [Eleminder](https://eleminder.com/)

Reminds you of outstanding review requests, PR comments, build status, and more.

__Install:__ via a Slack + GitHub app. 

Eleminder has a light feature set: all interaction is via the Slack bot.

### Open Source (self-hosted)

#### [Seal](https://github.com/binaryberry/seal)

A Ruby script that sends a daily message with a list of open pull requests to Slack. Has a "Deploy to Heroku" button. 321 stars.

#### [Thoughtbot Pester](https://github.com/thoughtbot/pester)

Sends open PRs to Slack at a defined interval (ex: every 30 minutes). 140+ stars.

#### [Slack Pull Reminders](https://github.com/ekmartin/slack-pull-reminder)

A Python script that posts a message to Slack with a list of all open PRs for the specified org. 36 stars.

#### [review-waiting-list-bot](https://github.com/ohbarye/review-waiting-list-bot)

A Slack bot that lists outstanding review requests via `@review-bot ls`. 59 stars.

## Everything else

#### [Official GitHub Slack Bot](https://slack.github.com/)

The GitHub-supported Slack bot has the following key features:

1. Allows to you subscribe to repo activities like new commits, pull requests, and issues. 
2. Rich previews of private links (pull requests, blocks of code, comments, etc).
3. Open/close issues via `/github` commands.

The source code is available on [GitHub](https://github.com/integrations/slack). 700+ stars.

__Install:__ via a [GitHub app](https://github.com/marketplace/slack-github) or self-hosted.

#### [Netflix Hubcommander](https://github.com/Netflix/hubcommander)

HubCommander helps you manage GitHub orgs, performing tasks like:

* Repository creation
* Repository deletion
* Repository description and website modification

1,000+ stars.

__Install:__ self-hosted.

#### [Probot Reminders](https://github.com/probot/reminders)

Add comments to GitHub issues (ex: `/remind me in 10 minutes`) and get a Slack message at the specified time. There is a hosted app, but it doesn't appear to be functioning. 60 stars.

#### [Repo Info](https://gitrepo.info/)

Check the health of public repos via Repo Info's Slack bot. When posting a link to a GitHub repo in Slack, Repo Info displays the number of stars, watchers, forks, recent activity, and checks for outdated dependencies.

#### [Wakatime](https://wakatime.com/slack)

Reports the time spent writing code (uses IDE integrations) on new commits via a Slack message.

#### [SlashDeploy](https://getslashdeploy.com/)

Allows you to manage deploys within Slack by leveraging the GitHub deployments API. Pricing starts at $15/mo.

#### [Engineer Notifier](https://github.com/petrgazarov/engineer-notifier)

Mentions engineers by their Slack handle when they are mentioned on GitHub. Define slack => GitHub handles via the `MENTIONS_TO_HANDLES` environment variable. Has a "Deploy to Heroku" button.

#### [DeployBot](https://deploybot.com/)

DeployBot is a full-featured deployment tool, automating the entire deploy process. There is a [Slack bot](https://support.deploybot.com/article/90-how-do-deploybot-and-slack-work-together) for triggering deploys. DeployBot supports GitHub and several other approaches for code hosting.

Pricing starts at $15/mo.
