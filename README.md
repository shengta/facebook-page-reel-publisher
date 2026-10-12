# Facebook Page Reel Publisher

A portable [Agent Skill](https://agentskills.io/) for planning or publishing **one prepared video** as a Facebook Page Reel. It checks for an existing post, verifies the selected media and Page settings, submits once, and records a direct-link readback.

## Install in Codex

Ask Codex to install this skill from:

https://github.com/shengta/facebook-page-reel-publisher/tree/main/facebook-page-reel-publisher

The skill folder is [facebook-page-reel-publisher](facebook-page-reel-publisher/), with its instructions in [SKILL.md](facebook-page-reel-publisher/SKILL.md). The official Codex skill installer can use the repository and path:

```text
--repo shengta/facebook-page-reel-publisher --path facebook-page-reel-publisher
```

## Use

Invoke `$facebook-page-reel-publisher` to prepare or publish a named, ready video to a specified Facebook Page. Provide the video version, target Page, caption, and any cover or posting preferences. A planning request stops before publication; a clear request to publish authorizes the single submission.

The skill is interface-neutral: it can use an authorized Android app or browser uploader available in the current environment. It contains no account credentials, device address, Page identity, video asset, or prior publication receipt.

## Scope

This skill handles Reel publication and verification. It does not produce the video or authorize advertising, additional platforms, or duplicate uploads.

No license has been selected for this repository.
