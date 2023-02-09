---
name: Meeting Data Audit
about: Instructions for auditing project meeting data/calendar events
title: 'Meeting Data Audit: [Replace PROJECT NAME]'
labels: 'feature: calendaring, prep, status: needs audit spreadsheet, status: needs
  calendar event audit, status: needs hackforla.org/VRMS audit, status: needs post
  audit recommendations document, status: needs recommendations, status: needs Slack
  audit document, status: needs Slack data, status: needs Slack reconciliation, status:
  needs Zoom accounts audit, status: needs Zoom Setup data'
assignees: ''

---

### Overview
We need to audit all calendar events for a given project to match the Zoom Setup and Zoom Audit Spreadsheet so that we can optimize the availability of the Zoom rooms and have the most current meeting information.

### Prerequisite 
#### If you are not the PM on the project this issue is for
-  access to the 1Password vault for Google Drive Migration 
- know your GitHub username and password so that you can use it in the (Google Drive Migration) hfla-email-all@hackforla.org Chrome profile
#### If you are the PM on the project this issue is for
-  access to the 1Password vault for the project
- access to the project's shared drive through the project's email Chrome profile
  - [ ] add the project's email as a `Contributor` if the drive is not already shared with the email
- know your GitHub username and password so that you can use it in the project email's Chrome profile
 
### Action Items
#### Setup
##### Customize Issue
- [ ] click the `Edit` button next to the issue title and replace `[Replace PROJECT NAME]` with the project's name
- [ ] Search for `[Replace PROJECT NAME]` in this issue
   - [ ] Replace with the name of the project (e.g., Expunge Assist)
- [ ] add this issue to the `Project Management` board
- [ ] if you will be working on this issue right away, assign yourself and move it to `In Progress`
- [ ] if you will not be working on this issue right away, move it to `Prioritized Backlog`
- [ ] Delete the customize issue section (7 prior lines starting from ```### Customize issue```)
##### Setup Access Through Proper Profile
- PMs
   - [ ] Log into the project's email and open it in a new chrome profile, so that you can access the account's calendar
   - [ ] open this issue in the project's profile browser and follow steps to Access GitHub
- Non PMs
   - [ ] Log into the [hfla-email-all@hackforla.org](mailto:hfla-email-all@hackforla.org) email and open it in a new chrome profile, so that you can access the account's calendar
   - [ ] open this issue in the hfla-email-all profile browser and follow steps to Access GitHub
##### Access GitHub
- [ ] Log into your GitHub account.  If you are already logged in you will see either your icon.  If you are not, you will see a sign-in button top right in the issue that is open now in the new profile browser.
- [ ] Close any other browsers you have open that are not in the new profile browser, so that you don't end up opening links in the wrong browser (this will be particularly important when you are accessing drives)
##### Add Org Level Audits folder to Starred
If you do not see the project's drive in the list of shared drives, see Prerequisite
- [ ] access the `Org Level Audits` folder in the project's shared drive
- [ ] right click on the folder and select `Add to starred`

#### Prep
For each of the following items, there are instructions in the wiki. Copy the instruction for next item to be checked off (must do them in order), to a comment below, and then complete the tasks in the comment.

During these tasks you will be asked to add link to resources, and that section is at the bottom of this issue (go view it now).

- [ ] [Create Slack Audit document](https://github.com/hackforla/admin-calendaring/wiki/Create-Slack-Audit-document) 
- [ ] [Add Slack channel(s)](https://github.com/hackforla/admin-calendaring/wiki/Add-Slack-Channel(s))
- [ ] [Create Recommendations & Next Steps document](https://github.com/hackforla/admin-calendaring/wiki/Create-Recommendations-&-Next-Steps-document)
- [ ] [Create Meeting Data Audit and Reconciliation Spreadsheet](https://github.com/hackforla/admin-calendaring/wiki/Create-Meeting-Data-Audit-and-Reconciliation-Spreadsheet)
- [ ] After the first 4 Prep items have been checked off and their labels removed, 
   - [ ] remove the `prep` label
   - [ ] add the `admin prep` label
   - [ ] move issue to `Prioritized Backlog` on the project board
   - [ ] unassign yourself
   - [ ] remove the `Org Level Audits` folder from Starred
      - [ ] access https://drive.google.com/drive/starred
      - [ ] look for the `Org Level Audits` folder that belongs to the project by looking under `Owner` for the project name
      - [ ] right click on the folder and select `Remove from starred`
#### Admin Prep
- [ ] [Import project's data from Zoom Setup spreadsheet](https://github.com/hackforla/admin-calendaring/wiki/Import-project's-data-from-Zoom-Setup-spreadsheet)
- [ ] [Setup Automation Formulas for the Audit](https://github.com/hackforla/admin-calendaring/wiki/Setup-Automation-Formulas-for-the-Audit)
- [ ] After the first 2 Admin Prep items have been checked off and their labels removed, 
   - [ ] remove the `admin prep` label
    - [ ] add the `audit` label

#### Audit
**NOTE: There are autogenerated notes in the spreadsheet you will be using so please do not edit any `Auto Notes` columns**
- [ ] [Perform Calendar Event Audit](https://github.com/hackforla/admin-calendaring/wiki/Perform-Calendar-Event-Audit) 
- [ ] [Perform Zoom Accounts Audit]( https://github.com/hackforla/admin-calendaring/wiki/Perform-Zoom-Accounts-Audit)
- [ ] [Perform Slack Audit](https://github.com/hackforla/admin-calendaring/wiki/Perform-Slack-Audit)
- [ ] [Perform hackforla.org/VRMS Audit](https://github.com/hackforla/admin-calendaring/wiki/Perform-hackforla.org-VRMS-Audit) 
- [ ] After the first 4 Audit items have been checked off and their labels removed, 
   - [ ] remove the  `audit` label
   - [ ] add the `reconciliation` label
   - [ ] move issue to `Prioritized Backlog` on the project board
   - [ ] unassign yourself

#### Reconciliation
- [ ] [Reconcile the Slack Audit document with the Slack Audit Sheet](https://github.com/hackforla/admin-calendaring/wiki/Reconcile-the-Slack-Audit-Document-with-the-Slack-Audit-Sheet)

#### Recommendations and next steps
- [ ] [Add recommendations](https://github.com/hackforla/admin-calendaring/wiki/Add-recommendations)
- [ ] [Review team feedback and respond](https://github.com/hackforla/admin-calendaring/wiki/Review-team-feedback-and-respond)

#### Resources/Instructions
1.0 [Zoom Setup Spreadsheet](https://docs.google.com/spreadsheets/d/15P3MYyNQ7Xn0pqdrTynDDipjrLl5LCN9xHVLhk9SWa8/edit#gid=1276874845)
2.0 [[Replace PROJECT NAME]: Meeting Data Audit and Reconciliation Spreadsheet]
3.0 [[Replace PROJECT NAME]: Slack Audit Document]
4.0 [[Replace PROJECT NAME]: Post Audit Recommendations]
