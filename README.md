![TestDriver.ai](https://github.com/dashcamio/testdriver/assets/318295/2a0ad981-8504-46f0-ad97-60cb6c26f1e7)

# TestDriver.ai Web Quickstart

GitHub actions workflow files that generate and run end-to-end regression tests.

---

**What is TestDriver?**

> Next generation autonomous AI agent for end-to-end testing of web & desktop

[Website](https://testdriver.ai) | [Docs](https://docs.testdriver.ai) | [GitHub Action](https://github.com/marketplace/actions/testdriver-ai) | [Join our Discord](https://discord.gg/a8Cq739VWn)

---

## Getting Started

Setup takes place entirely within GitHub and the TestDriver.ai dashboard. There's no need to clone this repo locally.

Our steps look like this:

1. Use this repository template.
1. Generate test plans
1. Generate regression tests

Overview
This short tutorial will walk you through setup of TestDriver in a new repository! It only takes a few steps and we're going to accomplish everything within the GitHub interface and TestDriver dashboard.
Set up your test repository
Generate test plans
Generate regression tests
If you don't have a TestDriver API key, you'll need to apply for the private beta before following this tutorial.
Set up the test repository
First, copy our template repository
This template repository contains GitHub actions workflow files that will handle generating and running tests. 
Open our template repository in a new tab
Click "use this template"

Click "Create a new repository"
Customize the template with GitHub variables
This quickstart will perform end to end tests on a live website. 
Add TESTDRIVER_WEBSITEvariable

https://github.com/{{your user}}/{{your repo}}/settings/variables/actions

Run the workflow

That will generate some test prompts

Review test results
Merge

Generate Regression Tests

Each Test Plan turns into a regression test

TestDriver opens a bunch of PRs



In the PR, press . to open in github.dev . 
