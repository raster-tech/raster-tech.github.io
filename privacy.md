---
title: Privacy Policy
---

# Raster Tech Sheet — Privacy Policy

**Effective date: September 27, 2026**
**Operator: Raster Tech (Kevin Downing)**
**Contact: kevhdowning@gmail.com** (interim, until the company email is set up)

## What this app is

Raster Tech Sheet is a desktop application that runs on your own computer. It
checks the devices on your show's network against a Google Sheet you control, and
writes the results back into that sheet.

## What it can access

When you sign in with Google (the "Show Device" path), the app asks for Google's
**`drive.file`** permission. This is a narrow permission: it lets the app see and
use **only the specific spreadsheet you pick** in Google's own file picker. It
cannot see, list, or open any other file in your Google account.

If you use the "Engineer Device" path instead, you create your own Google service
account in your own Google Cloud project, and share your show sheet with it
directly. We never receive or hold that account or its key; it exists entirely
under your control.

## What it reads

From the one spreadsheet you've picked or shared:
- the device list, IP addresses and VLAN assignments (the GEAR INDEX and IP INDEX
  tabs)
- the current values in the sheet's status columns

## What it writes

Back into that same spreadsheet, and nowhere else:
- the **Status** column (Verified, Partial or Failed) for each device
- the **Audit Details** and **Last Check** columns
- a device's MAC address, only if that cell was previously blank
- a list of unexpected devices found on the network, on their own tab

The app never changes any other column, tab, or file.

## What leaves your computer

Only the Google Sheets API calls needed to read and write that one spreadsheet.
Nothing else leaves your machine or your Google account. We do not run a server
that stores your show data. We do not use analytics or tracking of any kind, and we
do not share your data with any third party.

## Data retention

Your show data lives in your own Google Sheet, under your own Google account, for
as long as you keep it there. The app also keeps a small local settings folder on
your computer (which show you last opened, cached status for offline use). Nothing
is retained by us; there is nothing on our side to retain.

## How to revoke access

- Remove the app's access to your Google account at
  [myaccount.google.com/permissions](https://myaccount.google.com/permissions).
- Delete the app's local settings folder on your computer to remove the local cache.

## Use of your data

We use the data the app reads and writes solely to provide the app's own
functionality to you: checking your devices and keeping your sheet's status
current. We do not use it for advertising, do not sell it, and do not transfer it
to anyone else, consistent with Google's Limited Use requirements for apps that use
Google user data.

## Changes to this policy

If this changes, we'll update the date at the top of this page.
