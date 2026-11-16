# MDRRMO San Vicente Operations Log

A lightweight, browser-based recordkeeping app for the Municipal Disaster Risk Reduction and Management Office (MDRRMO), San Vicente, Palawan. It includes a call log, dispatch log, and daily situation reports (SITREPs) for emergency, operations, and travel activities.

## Run the app

Open `index.html` in a current desktop or mobile browser. No installation, server, or external libraries are required.

## Features

- Dashboard totals for today's calls and SITREPs, open incidents, and active dispatches.
- Call log: received time, caller and callback, incident, category, priority, location, details, action/referral, status, and operator.
- Dispatch log: linked call ID, assignment, unit/team, vehicle, destination, lead, status, return time, and field notes.
- Daily SITREPs categorized as Emergency, Operations, or Travel, with reporting period, summary, actions/resources, impact, needs, outlook, preparer, and status.
- Search and filter records, edit or delete entries, export each log as CSV, and print reports.

## Data storage and important limitations

Records are saved in the browser's `localStorage` on the device where the page is opened. They are **not synced** across users or devices and are not automatically backed up. Clearing browser data or changing browsers/devices may remove access to the records. Use the CSV exports for regular backups and follow MDRRMO records-retention procedures.

This is a starter tool, not a secure, multi-user incident-management system. Do not store passwords, highly sensitive personal information, or details that should only be shared through approved government channels. Restrict access to the device and use an organization-approved hosting, authentication, backup, and data-protection solution before deploying for official or multi-user use.

## Suggested next steps for an official deployment

1. Confirm required fields, incident categories, status terms, report formats, and retention requirements with MDRRMO San Vicente.
2. Decide on an approved hosting and database platform with authenticated, role-based access and audit history.
3. Set up scheduled backups, access reviews, and a tested recovery process.
4. Review privacy, security, and records-management requirements with the LGU before entering operational data.
