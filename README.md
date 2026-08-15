# Microsoft 365 Admin Lab

## Overview

This project documents a hands-on **Microsoft 365 administration lab**
designed to simulate common tasks performed by a Help Desk or Service
Desk technician. The lab combines the **Microsoft 365 Admin Center**
with **Spiceworks Help Desk** so that administrative changes are handled
through a realistic ticket-based workflow rather than as isolated
technical exercises.

------------------------------------------------------------------------

## Table of Contents

-   [Project Goals](#project-goals)
-   [Lab Environment](#lab-environment)
-   [Tasks Covered](#tasks-covered)
-   [Task 1 - Create a User and Assign a
    License](#task-1---create-a-user-and-assign-a-license)
-   [Task 2 - Reset a User Password](#task-2---reset-a-user-password)
-   [Task 3 - Add a User to a Microsoft 365
    Group](#task-3---add-a-user-to-a-microsoft-365-group)
-   [Task 4 - Disable and Delete a
    User](#task-4---disable-and-delete-a-user)
-   [Task 5 - Access Outlook, OneDrive, and Teams
    Settings](#task-5---access-outlook-onedrive-and-teams-settings)
-   [Task 6 - Change OneDrive Sharing
    Permissions](#task-6---change-onedrive-sharing-permissions)
-   [Spiceworks Help Desk
    Integration](#spiceworks-help-desk-integration)
-   [What I Learned](#what-i-learned)
------------------------------------------------------------------------

## Project Goals

The goal of this lab is to practice Microsoft 365 administration in a
way that reflects the workflow of an entry-level IT support environment.


Key objectives include:

-   Practice common Microsoft 365 Help Desk responsibilities.
-   Become comfortable navigating the Microsoft 365 Admin Center.
-   Practice user provisioning, access management, password
    administration, group management, and offboarding.
-   Apply basic security concepts such as identity verification and
    least privilege.
-   Practice documenting technical work through a ticketing system.

------------------------------------------------------------------------

## Lab Environment

  -----------------------------------------------------------------------
  Technology                          Purpose
  ----------------------------------- -----------------------------------
  **Microsoft 365 Admin Center**      User, license, group, service, and
                                      account administration

  **Microsoft 365 Business Basic**    Licensing used for the lab users

  **Spiceworks Help Desk**            Simulated ticket intake, technician
                                      updates, user communication, and
                                      ticket closure

  **Microsoft Teams / Groups**        Collaboration and group membership
                                      administration

  **OneDrive**                        File access and sharing
                                      administration

  **Outlook / Exchange settings**     Mail-related administrative
                                      settings
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Tasks Covered

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  \#                Task              Status            Documentation
  ----------------- ----------------- ----------------- ----------------------------------------------------------------------------------------------------------------------
  1                 Create a new user ✅ Complete       [View
                    and assign a                        Lab](https://github.com/Yahyak-05/Microsoft365-Admin-Lab/blob/main/User%20Creation%20%26%20License%20Assignment.pdf)
                    Microsoft 365                       
                    license                             

  2                 Reset a user's    ✅ Complete       [View Lab](https://github.com/Yahyak-05/Microsoft365-Admin-Lab/blob/main/Password_Reset.pdf)
                    password                            

  3                 Add a user to a   ✅ Complete       [View Lab](https://github.com/Yahyak-05/Microsoft365-Admin-Lab/blob/main/Add-user-to-group.pdf)
                    Microsoft 365                       
                    group                               

  4                 Disable and       ✅ Complete       [View Lab](https://github.com/Yahyak-05/Microsoft365-Admin-Lab/blob/main/Offboarding-User-guide.pdf)
                    delete a user as                    
                    part of                             
                    offboarding                         

  5                 Access Outlook,   🚧 In Progress    **[Documentation Link - Coming Soon](#)**
                    OneDrive, and                       
                    Teams settings                      
                    from the Admin                      
                    Center                              

  6                 Change sharing    🚧 In Progress    **[Documentation Link - Coming Soon](#)**
                    permissions on a                    
                    OneDrive folder                     
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------

# Lab Tasks

## Task 1 - Create a User and Assign a License

The first task covers the **user provisioning process** in Microsoft
365. I reviewed available licenses, created a new employee account,
configured the user's profile, and assigned a **Microsoft 365 Business
Basic** license.

The account was configured with an automatically generated password that
must be changed at first sign-in. I also configured the employee's
organizational information and kept the account as a standard user with
no administrative access, following the **principle of least
privilege**.

➡️ **[View the full user creation and license assignment
walkthrough](https://github.com/Yahyak-05/Microsoft365-Admin-Lab/blob/main/User%20Creation%20%26%20License%20Assignment.pdf)**

------------------------------------------------------------------------

## Task 2 - Reset a User Password

This scenario simulates a common Help Desk request: a user who cannot
remember their password.

The request begins as a **high-priority Spiceworks ticket**. Before
making the account change, the ticket is placed into a waiting state
while the user's identity is verified. After verification, the password
is reset through **Microsoft 365 Admin Center → Users → Active users**.

The lab also distinguishes between **Self-Service Password Reset
(SSPR)** and an **admin-assisted password reset**. For this scenario,
the admin-assisted method is used, with the user required to change the
temporary password after signing in.

➡️ **[View the full password reset
walkthrough](https://github.com/Yahyak-05/Microsoft365-Admin-Lab/blob/main/Password_Reset.pdf)**


------------------------------------------------------------------------

## Task 3 - Add a User to a Microsoft 365 Group

This scenario begins with a Spiceworks request to add an employee to the
**Finance Department's Microsoft 365 group**.

Because the Finance group did not yet exist in the lab, I created a new
**Microsoft 365 Group**, configured its settings, assigned an owner, and
added the requested employee as a member. The group was designed for
collaboration so members could share resources such as group email,
calendars, files, and Microsoft Teams resources.

After verifying the membership, the Help Desk ticket was updated and
closed following user confirmation.

➡️ **[View the full group creation and membership
walkthrough](https://github.com/Yahyak-05/Microsoft365-Admin-Lab/blob/main/Add-user-to-group.pdf)**


------------------------------------------------------------------------

## Task 4 - Disable and Delete a User

This task simulates an **employee offboarding request** received through
Spiceworks.

The workflow includes blocking the user's sign-in, resetting the
password, considering active sessions, reviewing OneDrive and mailbox
data for possible company retention, removing departmental group access,
reclaiming the Microsoft 365 license, deleting the account, and
verifying that the user appears under **Deleted users**.

The lab also demonstrates an important distinction between **removing a
user's identity** and **preserving company data**. In this practice
environment there was no OneDrive data to back up, but in a production
environment company files and required mailbox content would normally be
reviewed for preservation or transfer before final account disposal.

After confirming that the account was removed and the license returned
to the available pool, the Spiceworks ticket was closed.

➡️ **[View the full Microsoft 365 offboarding
walkthrough](https://github.com/Yahyak-05/Microsoft365-Admin-Lab/blob/main/Offboarding-User-guide.pdf)**

------------------------------------------------------------------------

## Task 5 - Access Outlook, OneDrive, and Teams Settings

> 🚧 **This section is currently in progress.**

This task will document how an administrator can access and review
user-specific **Outlook, OneDrive, and Teams-related settings** from
Microsoft 365 administration interfaces.

➡️ **[Documentation Link - Coming Soon](#)**

Planned areas include:

-   Locating service-specific user settings
-   Reviewing mailbox administration options
-   Reviewing OneDrive administration options
-   Reviewing Teams and collaboration settings
-   Understanding which settings are appropriate for Help Desk
    administration and which may require escalation

------------------------------------------------------------------------

## Task 6 - Change OneDrive Sharing Permissions

> 🚧 **This section is currently in progress.**

This task will demonstrate how to review and modify **sharing
permissions for a OneDrive folder**, including how access can be
granted, restricted, or removed based on a support request.

➡️ **[Documentation Link - Coming Soon](#)**

Planned areas include:

-   Reviewing current sharing permissions
-   Identifying who has access to a folder
-   Modifying or removing access
-   Applying appropriate sharing settings
-   Verifying the final permissions

------------------------------------------------------------------------

## Spiceworks Help Desk Integration

A major part of this project is the integration of **Spiceworks Help
Desk** into the Microsoft 365 scenarios.

The purpose is to simulate the complete lifecycle of a real support
request:

**User Request → Ticket Review → Identity/Authorization Check →
Microsoft 365 Administration → Verification → User Update → Ticket
Closure**


------------------------------------------------------------------------

## What I Learned

Through this project, I gained a better understanding of how Microsoft
365 administration connects to day-to-day Help Desk operations.

I learned that account administration is not simply about knowing where
a button is located in the Admin Center. Changes such as password
resets, group membership updates, licensing, and offboarding should be
tied to a valid business request and performed through a controlled
process.


------------------------------------------------------------------------

