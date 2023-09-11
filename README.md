# CodeReview BOT

> A code review robot powered by ChatGPT

### Install

Install: [apps/cr-gpt](https://github.com/apps/cr-gpt);

### Configuration
1. Go to the repo homepage which you want integrate this bot
2. click `settings`
3. click `actions` under `secrets and variables`
4. Change to `Variables` tab, create a new variable `OPENAI_API_KEY` with the value of your open api key (For Github Action integration, set it in secrets)

### Start using

1. The robot will automatically do the code review when you create a new Pull request, the review information will show in the pr timeline / file changes part.
2. After `git push` update the pull request, cr bot will re-review the changed files

## Using Github Actions

1. add the `OPENAI_API_KEY` to your github actions secrets
2. create `.github/workflows/cr.yml` add bellow content
