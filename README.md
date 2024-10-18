# EeazyCRM

#### Python-based open-source CRM developed using the Flask framework.

##### It's still WORK IN PROGRESS (I'm still building the modules).
##### But I have a small DEMO image below:
![Demo Image](https://i.ibb.co/BsWm9Kf/eeazycrm-demo1.gif)

## Features List

EeazyCRM contains the following modules (along with the completion progress report):

1. Leads (99% complete)
2. Accounts (90% complete)
3. Contacts (99% complete)
4. Deals (with Pipeline view) (90% complete)
5. Activities (still building) (Not started as yet)
6. Reports (with charts and graph) - (60% complete)
7. Settings (50% complete)
   1. Roles Management (100% complete)
   2. User Management (100% complete)
   3. Profile Management (100% complete)
   4. Company Management (Not started)
   5. Configuration Management (Not started)
      - Deal Stage
      - Lead Stage
      - Lead Source
      - Activity Types
      - Email Templates
   6. Application Settings (100% complete)
8. Invoice (Not started)
9. Dashboard (10% complete)

**Future Plans**:
Depending upon the demand for this application, I'm also planning the following integrations:
- Integration with WordPress Contact Form 7 (Lead Capture).
- Integration with Google Contacts.
- Integration with Dropbox or Google Drive for Automatic Backups.
- Integration with Email Service such as MailChimp.

## Installation Requirements

1. Python 3
2. PostgreSQL (version 11+ or greater)
3. pip3
4. virtualenv

**Make sure that the PostgreSQL instance is up and running.**

Open the command prompt or terminal and create a new database with the following commands:

```bash
psql
create database eeazy_crm;
