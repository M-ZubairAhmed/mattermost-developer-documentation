---
title: New Staff Guide
date: 2017-11-07T14:28:35-05:00
subsection: Onboarding
weight: 10
---

### Helpful links
- https://docs.mattermost.com/developer/developer-flow.html
- [Jira bug ticket process](https://docs.mattermost.com/process/new-bug-tickets.html)
- [PR cherry-picking process](https://developers.mattermost.com/contribute/getting-started/branching/)
- [RN build process](https://developers.mattermost.com/internal/mobile-build-process/) if you are joining Apps team
- Glance through the release processes
    - https://docs.mattermost.com/process/feature-release.html
    - https://docs.mattermost.com/process/bug-fix-release.html
- Security: Read through the security channel / issues spreadsheet and look at past exploits
- Developer Reading List - top of public Developer channel

### Mentor For The Day
- Meet with a dev team member every day for about 30 mins.  Dev member will rotate daily to expose the new hire to everyone.  The process with run for approximately for 2 weeks. The goal is to get to know each other, feel free to talk about non-work related stuff.
- Schedule to be sent by manager in channel

### Meet with a few PMs
- List to be sent by manager in channel

### Channels and Teams
- You should be added to the private team `Staff` and join the following channels
    - Alerts
    - Announcements
    - Customer Success
    - Customer Support
    - Confidential Bugs
    - Private Off-Topic (optional)
    - R&D Meeting
    - Social: * (optional)
    - Stand-up
    - Welcome
- Private channels to join in `Contributors`
    - Security
    - Confidential Bugs
    - Developers: Private     
    - MVP Discussion
- Public channels to join in `Contributors`
    - Developers
    - Developers Meeting
    - Bugs
    - Contributors
    - Release Discussion
    - Release Checklist (optional)
    - Toolkit (optional)
    - Redux (optional)
    - Installers and Images (optional)
    - Native Mobile Apps (optional)
    - Desktop App (optional)
    - Developers: Performance (optional)
    - Peer-to-peer Help (optional)

### Meetings and Accounts
- You manager should notify `people-ops` and have you added to all appropriate meetings
    - `people-ops` will also set up your `@mattermost.com` email
- DevOps to setup various accounts as needed
    - Add to email groups
        - dev-ops
        - build
    - LDAP account
    - OneLogin account
    - VPN account
    - Add to GitHub contributors
    - Add IAM user to master AWS account
    - Add to Azure

### Potential topics to chat with a daily mentor about
- GitHub workflow
- Jira workflow
- Sprint planning
- Mattermod
- Internal Jenkins build server
- External Jenkins build server
- API docs
- Webapp structure
- Server structure
- React Native apps
- Desktop app
- Enterprise repo
- Platform-private repo
- Release process
- Org chart and roles
- Operation Gaming
- Redshift Analytics

## GitHub Mattermost Organization Membership

If you've previously contributed to a repository within the `mattermost` organization, you'll show up with a `Contributor` tag:

![contributor](/internal/contributor.png)

Once you're added to the `mattermost` organization on GitHub, you'll show up with the `Member` tag:

![member](/internal/member.png)

By default, however, this tag only appears to other members within the organization: anyone outside will continue to see only the `Contributor` tag. If you want your membership in the `mattermost` organization to be public, follow the steps on https://help.github.com/articles/publicizing-or-hiding-organization-membership/ to find your username on https://github.com/orgs/mattermost/people and change your `Organization visibility` to `Public`.
