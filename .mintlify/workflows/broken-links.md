---
name: 'Broken link detection'
on:
  cron: '0 10 * * 1'
automerge: false
---

Check all internal links for broken references. Update links to renamed pages. Flag external 404s without removing them.
