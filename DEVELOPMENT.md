# Development Guide

## Setup

We **strongly** advise using Linux, macOS, or Windows Subsystem for Linux. All
instructions herein will assume you've done so; if you are using Windows anyway,
you will need to adapt commands to your system.

Install Deno on your system following the instructions here:
https://deno.land/manual@v1.36.1/getting_started/installation

We use a few Python-based development tools as well, so you should install
Python 3.10 or later. Then, run the following (under Mac/Linux):

```bash
python3.10 -m venv venv
venv/bin/pip install branch-detective commitizen
```

You will also need to install the Quarkboard CLI, which serves as the backend:
https://gitlab.com/quantifiedtasks/quarkboard-cli

Please enable the commit hooks to help ensure code quality:

```bash
git config --local core.hooksPath .githooks/
```
