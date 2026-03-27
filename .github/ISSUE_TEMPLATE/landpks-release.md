---
name: LandPKS Release
about: Tasks from finishing milestone tasks through publishing to beta and production
title: Release [version number to app stores]
labels: Product
assignees: ''
type: Task

---

First: Finalize tasks in Milestone

- [ ] (if needed) update production backend to support [version]
- [ ] Product: write up release notes for app store (review from Engineers)
- [ ] a few days before release
   - [ ] agree no more fixes go in 
   - [ ] pull unfinished issues into new sprint
- [ ] Create interstitial with release notes
   - [ ] Product Draft
   - [ ] Engineer implements
- [ ] Localize
  - [ ] Perform autotranslation
- [ ] Engineering: Create build with new features pointing to staging
- [ ] Product: Perform smoke tests

Beta:
- [ ] Engineering create release candidate
- [ ] Derek: submit to apple and google
- [ ] Smoke tests on beta
- [ ] Release build to beta track
- [ ] Communicate with testers and translators
    - [ ] Message WhatsApp groups (name new features, ask to download and test)
    - [ ] Ask [Translation Community](https://docs.google.com/spreadsheets/d/1US7jw4da00aqRhsR8GyTsYeFMJ2lVZ6aVd017ucI5wU/edit?usp=drive_web&ouid=115280322001227706952) to review
- [ ] Identify any changes that need to be made.
   - [ ] Choose whether to incorporate into the *next* or *current* release.

Publish LandPKS in app stores:
- [ ] agree on publish date ___
- [ ] Engineering push to production
- [ ] Product: Update release notes on website

Next: do Comms (separate issue)
