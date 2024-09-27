![TestDriver.ai](https://github.com/dashcamio/testdriver/assets/318295/2a0ad981-8504-46f0-ad97-60cb6c26f1e7)

# TestDriver.ai Web Quickstart

GitHub actions workflow files that generate and run end-to-end regression tests on website.

---

**What is TestDriver?**

> Next generation autonomous AI agent for end-to-end testing of web & desktop

[Website](https://testdriver.ai) | [Docs](https://docs.testdriver.ai) | [GitHub Action](https://github.com/marketplace/actions/testdriver-ai) | [Join our Discord](https://discord.gg/a8Cq739VWn)

---

## Prereqs

1. You need a TestDriver API key
1. A live website URL to test 

> Setup takes place entirely within GitHub and the TestDriver.ai dashboard. There's no need to clone this repo locally.

### Setup

#### Fork this repo

First, make a copy of this repository. This repo contains example workflow files to get you set up with TestDriver super fast.

[Click here to fork this repository](https://github.com/testdriverai/quickstart-web/fork).

#### Create a `TESTDRIVER_WEBSITE` variable.

Once the fork has been created, [add a GitHub variable](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/store-information-in-variables#creating-configuration-variables-for-an-environment).

You must set the GitHub **variable** `TESTDRIVER_WEBSITE`. The value should be the root domain of the website you want to test (ex `https://example.com`).

#### Create a `TESTDRIVER_API_KEY` secret.

Once the fork has been created, [add a GitHub variable](https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/store-information-in-variables#creating-configuration-variables-for-an-environment).

You must set the GitHub **variable** `TESTDRIVER_WEBSITE`. The value should be the root domain of the website you want to test (ex `https://example.com`).

### Generate Test Plans

Your repo will come with 3 GitHub workflows already configured. 

/actions/workflows/generate-explore.yml

Run the workflow

That will generate some test prompts

Review test results
Merge

Generate Regression Tests

Each Test Plan turns into a regression test

TestDriver opens a bunch of PRs



In the PR, press . to open in github.dev . 
