---
name: 'Sync docs from code changes'
on:
  push:
    - repo: 'thaohienhomes/lobe-chat'
      branch: main
    - repo: 'thaohienhomes/lobe-chat'
      branch: v2-from-zero
context:
  - repo: 'thaohienhomes/pho-chat-docs'
automerge: false
---

Review the diff from the last merged PR. Identify any new features, UI changes, or configuration options that affect end users. Follow the style guide at /style-guide.md. Classify each change using Diátaxis (Tutorial/How-To/Reference/Explanation). Draft updates in both /vi/ and /en/ directories.

Success criteria: After reading the updated docs, a user understands what changed and how to use any new features.
