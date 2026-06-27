---
title: "AWS Secrets Manager introduces safe secrets handling in the Agent Toolkit for AWS"
url: "https://aws.amazon.com/about-aws/whats-new/2026/06/safe-secrets-handling-in-agent-toolkit-for-aws/"
date: "2026-06-17"
feed_url: "https://aws.amazon.com/about-aws/whats-new/recent/feed/"
---
AWS Secrets Manager offers a secret safety skill within the aws-core plugin of the Agent Toolkit for AWS, enabling secrets in agentic workflows without exposing values to models or logs. A two-layer approach steers models away from raw secrets, and child processes resolve secret references only at execution time outside agent processes; support extends to Claude Code, Codex, and Cursor.
