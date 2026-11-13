# Monthly Employee Promotion Eligibility & HR Notification Automation

## Overview

This Zapier automation checks employee records in Google Sheets each month and notifies HR about staff who meet the company’s promotion eligibility rule.

The policy used by this workflow is that an employee becomes eligible for promotion after completing **10 years of service**.

## Workflow

1. **Schedule by Zapier** starts the workflow every month.
2. **Google Sheets** retrieves employee rows from the staff spreadsheet.
3. **Looping by Zapier** processes the retrieved records one at a time.
4. **Filter by Zapier** continues only for records that meet the configured eligibility conditions.
5. Eligible employees’ details are sent to HR, and their promotion status is updated.

## Information used

For each eligible employee, the workflow uses:

- Employee name
- Staff ID
- Email address
- Promotion eligibility status

## Purpose

The automation helps HR review promotion-eligible employees without manually checking every staff record. It can reduce repetitive work and make monthly eligibility checks more consistent.

## Requirements

- A Google Sheet containing employee records
- A Zapier account with access to the required apps and features
- A configured HR notification destination
- Consistent employee start-date and status data in the spreadsheet

## Setup notes

The exact column names, eligibility calculation, notification destination, and status update depend on the connected Google Sheet and the Zap’s configured steps. Review those settings before adapting this workflow for another organization.

## Privacy

Employee names, staff IDs, email addresses, and employment records are personal information. Do not include real employee data, private spreadsheet links, credentials, or API keys in this public repository. Use sample or anonymized data in screenshots and examples.

## Project status

The screenshot shows this Zap in **Draft** status. Confirm the steps and test the workflow with sample data before publishing it.
