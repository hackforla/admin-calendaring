---
name: Project Meeting Data Audit
about: Instructions for auditing project meeting data/calendar events
title: 'Meeting Data Audit: [Replace PROJECT NAME]'
labels: 'feature: calendaring, prep, status: needs audit spreadsheet, status: needs
  calendar cleanup, status: needs calendar event audit, status: needs hackforla.org/VRMS
  audit, status: needs spreadsheet set up, status: needs Zoom accounts audit, status:
  needs Zoom Setup spreadsheet audit'
assignees: ''

---

### Overview
We need to audit all calendar events for a given project to match the Zoom Setup and Zoom Audit Spreadsheet so that we can optimize the availability of the Zoom rooms and have the most current meeting information.

### Prerequisite 
<details><summary>Admin Team</summary>

-  access to the 1Password vault for HfLA-email-all
- know your GitHub username and password so that you can use it in the hfla-email-all@hackforla.org Chrome profile
</details> 


<details><summary>PMs</summary>

-  access to the 1Password vault for the project
- access to the project's shared drive through the project's email Chrome profile
  - [ ] add the project's email as a `Content Manager` if the drive is not already shared with the email
- know your GitHub username and password so that you can use it in the project email's Chrome profile
</details> 

### Set up
#### Set up Access Through Proper Profile
<details><summary>Admin Team</summary>

   - Log into the [hfla-email-all@hackforla.org](mailto:hfla-email-all@hackforla.org) email and open it in a new chrome profile, so that you can access the account's calendar
   - open this issue in the hfla-email-all profile browser and follow steps to `Access GitHub`
</details> 

<details><summary>PMs</summary>

   - Log into the project's email and open it in a new chrome profile, so that you can access the account's calendar
   - open this issue in the project's profile browser and follow steps to `Access GitHub`
</details>


#### Access GitHub
- Log into your GitHub account.  If you are already logged in you will see either your icon.  If you are not, you will see a sign-in button top right in the issue that is open now in the new profile browser.
- Assign yourself to this issue and move it to `In progress (actively working)`
- Close any other browsers you have open that are not in the new profile browser, so that you don't end up opening links in the wrong browser (this will be particularly important when you are accessing drives)

#### Add Org Level Audits folder to Starred
If you do not see the project or CoP's drive in the list of shared drives, see `Prerequisite` above

- access the `Org Level Audits` folder in the project or CoP's shared drive, it will be preceded by the project or CoP initials
  - a star next to the folder name indicates that it has already been starred and you don't need to do the next step
- right click on the folder and select `Add to starred`

<details><summary>Notes</summary>

<i>There are automation formulas used throughout the meeting data and audit reconciliation sheet to autofill cells and generate messages regarding meetings with nonstandard setup. These formulas are indicated in a light grey color. 
- During the `Admin Prep` you will be asked to confirm that there are formulas in the correct cells and columns, which will easily be recognizable by the light grey
- Please do not edit any cells that are indicated to have formulas</i>
</details>

<details><summary>Troubleshooting</summary>

_Please make sure you read through all instructions carefully. There are some errors that are expected and should be automatically resolved as you continue with the tasks outlined in each action item. Please review [Errors and How To Resolve Them](https://github.com/hackforla/admin-calendaring/wiki/Errors-and-How-To-Resolve-Them) to get an idea of what to expect.
If, while carrying out any of the tasks, there is still ambiguity or there are errors that are not listed with a solution on the page mentioned above, please [follow these instructions](https://github.com/hackforla/admin-calendaring/wiki/Reach-the-Admin-Team) to contact the Admin team._
</details>

### Action Items
_There are some action items below that are linked to a wiki page with instructions (they are displayed in blue). Open the link in a new tab, copy the instructions from the wiki page into a comment below and complete the tasks in the comment._

#### Prep
_During the first task you will be asked to add a link under Resources/Instructions, and that section is at the bottom of this issue (go view it now)._

- [ ] [Update Team Calendar](https://github.com/hackforla/admin-calendaring/wiki/Update-Team-Calendar) (open in new tab)
- [ ] [Create Meeting Data Audit and Reconciliation Spreadsheet](https://github.com/hackforla/admin-calendaring/wiki/Create-Meeting-Data-Audit-and-Reconciliation-Spreadsheet) (open in new tab)
- [ ] After the first 2 `Prep` items have been checked off, 
   - [ ] remove the `prep` label
   - [ ] add the `audit prep` label
   - [ ] remove the `Org Level Audits` folder from Starred
      - [ ] access https://drive.google.com/drive/starred (open in new tab)
      - [ ] look for the `Org Level Audits` folder that belongs to the project or CoP, it will be preceded by the initials
      - [ ] right click on the folder and select `Remove from starred`

If you are stopping here then do the following otherwise move to the `Audit Prep` tasks
- [ ] move issue to `Prioritized Backlog` on the project board
- [ ] unassign yourself


#### Audit Prep
If you are continuing right after completing the `Prep` tasks, skip the first two items and start from the third item, otherwise do all 
- [ ] Assign yourself to the issue
- [ ] Move the issue to `In progress (actively working)`
- [ ] [Set up Meeting Data Audit and Reconciliation Spreadsheet for the Audit](https://github.com/hackforla/admin-calendaring/wiki/Set-up-Meeting-Data-Audit-and-Reconciliation-Spreadsheet-for-the-Audit) (open in new tab)

If you are stopping here then do the following otherwise move to the `Audit` tasks
- [ ] move issue to `Prioritized Backlog` on the project board
- [ ] unassign yourself

#### Audit
If you are continuing right after completing the `Audit Prep` tasks, skip the first two items and start from the third item, otherwise do all
- [ ] Assign yourself to the issue
- [ ] Move the issue to `In progress (actively working)`
- [ ] [Perform Calendar Event Audit](https://github.com/hackforla/admin-calendaring/wiki/Perform-Calendar-Event-Audit) (open in new tab)
- [ ] [Perform Zoom Setup Spreadsheet Audit](https://github.com/hackforla/admin-calendaring/wiki/Perform-Zoom-Setup-Spreadsheet-Audit) (open in new tab)
- [ ] [Perform Zoom Accounts Audit]( https://github.com/hackforla/admin-calendaring/wiki/Perform-Zoom-Accounts-Audit) (open in new tab)
- [ ] [Perform hackforla.org/VRMS Audit](https://github.com/hackforla/admin-calendaring/wiki/Perform-hackforla.org-VRMS-Audit) (open in new tab)
- [ ] After the 4 `Audit` items have been checked off and their labels removed, 
   - [ ] remove the  `audit` label
   - [ ] add the `recommendations and next steps` label

_Add the next label according to role_
<details><summary>Admin Team</summary>

   - [ ] add the `status: needs post audit messaging` label
</details>
<details><summary>PMs</summary>

- [ ] add the `status: needs post audit updates` label
</details>

If you are stopping here then do the following otherwise move to the `Recommendations and Next Steps` tasks
- [ ] move issue to `Prioritized Backlog` on the project board
- [ ] unassign yourself

#### Recommendations and Next Steps
If you are continuing right after completing the `Audit` tasks, skip the first two items and start from the role specific item, otherwise do all
- [ ] Assign yourself to the issue
- [ ] Move the issue to `In progress (actively working)`
<details><summary>Admin Team</summary>

- [ ] [Create and Send Message to PMs via Slack](https://github.com/hackforla/admin-calendaring/wiki/Create-and-Send-Message-to-PMs-via-Slack)
- [ ] [Confirm Post Audit Updates](https://github.com/hackforla/admin-calendaring/wiki/Confirm-Post-Audit-Updates)
</details>
<details><summary>PMs</summary>

- [ ] [Perform Post-Audit Next Steps to Standardize All Meeting Data](https://github.com/hackforla/admin-calendaring/wiki/Perform-Post-Audit-Next-Steps-to-Standardize-All-Meeting-Data)
   - [ ] Taking a break. BRB
</details>

#### Resources/Instructions
1.0 [[Replace PROJECT NAME]: Meeting Data Audit and Reconciliation Spreadsheet]
