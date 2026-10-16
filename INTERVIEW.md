# Git and Jenkins practice: reviewer guide

A collection of early Git exercises with a Jenkinsfile and small source/text files.

## Start the review

Use a concrete commit or pipeline example to explain what was learned. This is a practice repository, not a finished service.

| Source | Review focus |\n| --- | --- |\n| [Jenkinsfile](Jenkinsfile) | Triggers, credentials, failure handling, and deploy conditions |\n| [Power/Go.txt](Power/Go.txt) | Implementation, assumptions, and operational boundaries |\n| [killer.java](killer.java) | Implementation, assumptions, and operational boundaries |\n| [power.txt](power.txt) | Implementation, assumptions, and operational boundaries |\n| [ranu.txt](ranu.txt) | Implementation, assumptions, and operational boundaries |\n| [vishnu/Ram.txt](vishnu/Ram.txt) | Implementation, assumptions, and operational boundaries |

## A useful interview walkthrough

1. State the problem and the specific part you implemented or changed.
2. Open the source above and follow one request, release, or failure from start to finish.
3. Show a reproducible result, including an actual failure and the observation that confirms recovery.
4. Explain one tradeoff and one limitation. Distinguish a local test from a live deployment.

## Evidence and limits

This guide is based on the default-branch source inspected on 16 October 2026. It is a source review, not a fresh deployment or a certification of every feature. Existing CI runs and tests should be checked at the commit being demonstrated. Do not present screenshots, inherited code, planned features, or old README statements as proof of a current deployment.
