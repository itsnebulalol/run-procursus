# Run Procursus

Run a make command in the Procursus repo and upload as an artifact.

# How to use

1. Fork this repo
2. Enable workflows in the Actions tab
3. Click Run Procursus on the left
4. Click Run workflow, then put in the command
    - ex. `nano-package MEMO_TARGET=iphoneos-arm64-rootless MEMO_CFVER=1800`

Note that some packages may not work, as the workflow will time out if no
activity is being done.
