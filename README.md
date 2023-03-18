---
description: >-
  This page outlines (and in some cases, details) the major and minor feature
  releases made to the JustOrg Design Tables application.
---

# Release & Feature Notes

### Release Version 1.5.0 (03/01/2023)

<details>

<summary>View Release Details </summary>

* Database: User table, added new database items for user table: On\_Page\_ID and On\_Page\_Timestamp to track when a user is present in an agenda
* Capture Board: Disabled copy topic notes button when there are no responses
* Agenda Builder: Create popup with Strat details
* Profile: Ability for users to add a profile picture
* Agenda Builder: added a feature for showing participants who are IN the agenda. (Presence Bubble)
* Capture Board: added a feature for showing participants who are IN the Capture Board. (Presence Bubble)
* Agenda Builder: Confirm Delete of Agenda Topics
* Active Users: Update logged in screen
* Agenda Builder: Added calculated local Target Start Time to agenda item
* Agenda Builder: Updated Agenda Topic Sort functionality



#### **How to add an image to the new Presence Bubble feature...**&#x20;

<img src=".gitbook/assets/Presence Bubble.gif" alt="" data-size="original">

</details>

### Release Version 1.5.1 (3/1/2023)&#x20;

* Fixed pop up criteria for agenda builder, show strats&#x20;

### Release Version 1.5.2 (3/2/2023)&#x20;

* Agenda builder: strats pop up, removed count from Strat Name.
* Active Users: added time-based filter for list :-)
* Capture Board: added count of response at topic level"

### Release Version 1.5.3 (3/5/2023)

* Added Heap functionality to Dev and Live.
* I'm Here bubbles -- Support full\_screen\_notes
  * Support for concurrent multiple open tabs
* added exit/close window/tab plugin
* Created new data fields in the User table (to support I'm Here bubbles) -- ab\_IDs -- cb\_IDs

v.1.5.3.a - small fix v.1.5.3.b - triggered update to user table to clear ab and cb\_IDs "

### Release Version 1.5.4 (3/7/2023)

* Capture Board: Modified delete response feature: -- Convener can now delete any response -- Confirm delete functionality ""
* Capture Board: Conveners can make edit to CB Topics
* Agenda Builder: Fixed Remove agenda topic functionality -- the user can now only delete one topic at a time (user was able to delete multiple topics at a time which was causing errors)"&#x20;

### Release Version 1.5.5 (3/13/2023)

* Agenda Builder: Make Note Taker drop-down visible to all
* Capture Board: Bug fix, ""Back to Agenda"" button not visible on CB"&#x20;

### Release Version 1.5.6 (3/15/2023)

* Plugins: Plugin Updates - Phase 1 of 2
  * RT Editor: from 2.0.4 to 2.0.5 PDF Converter: from 1.77.0 to 1.82.0 >> And... reverted back to 1.77.0 again. same issue of file format change. Logged a bug on the ZeroQode forum: https://forum.zeroqode.com/t/pdf-plugin-file-format-change-post-v1-77-0-to-is-causing-issues/10074
* Plugins: Plugin Updates - Phase 2 of 2
  * Air database diagram: from 1.6.0 to 1.8.0 Down for maintenance: from 1.3.0 to 1.5.0 ZQ Countdown: from 1.7.0 to 1.9.0"&#x20;

### Release Version 1.5.7 (3/15/2023)&#x20;

* Login: Create an Email Sent for "Forgot Password"&#x20;

### Release Version 1.5.8 (3/16/2023)

* Agenda Builder: Fix workflow for real-time decision >> namely, clearing information as the user toggles between Table vs. Individual decision methodology.
* Agenda Builder: Fixed layout and Notes Section -- Issues with wrapping
* Agenda Builder: Added pdf downloads to emails being sent for agendas
* Org Admin - Org Members: Enable Search only when ""View Active Only"" selected "

### Release Version 1.5.9 (3/18/2023)

* Strategies & Values: Set ""N/A"" as default for Closed Reason values/strats
* Values: Fixed closed Value view - showing as Closed instead of Active.
* Agenda Builder: Updated the Alerts popup on the Agenda Builder
