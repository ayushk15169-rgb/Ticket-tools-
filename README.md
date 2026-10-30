# IT Help Desk & Ticket Management System Web Template

A responsive IT help desk and support ticket management system built with **HTML5, CSS3, and Vanilla JavaScript**.

The project provides a complete front-end administration interface for managing support tickets, users, technicians, priorities, categories, ticket assignments, SLA deadlines, activities, analytics, and reports.

The application runs entirely in the browser using `localStorage` and does not require a backend or database.

## Features

### Dashboard

View important help desk information in one place.

- Total Tickets
- Open Tickets
- In Progress Tickets
- Resolved Tickets
- Closed Tickets
- Overdue Tickets
- Urgent Tickets
- Unassigned Tickets
- Average Resolution Time
- SLA Compliance
- Recent Tickets
- Technician Workload
- Tickets by Priority
- Tickets by Status
- Recent Activity

### Ticket Management

Create and manage support tickets.

Ticket information can include:

- Ticket Number
- Title
- Description
- Requester
- Assigned Technician
- Category
- Priority
- Status
- Created Date
- Due Date
- Resolved Date
- Closed Date
- Tags
- Notes

Ticket statuses:

- New
- Open
- In Progress
- Waiting
- Resolved
- Closed
- Cancelled

Priorities:

- Low
- Medium
- High
- Urgent

### Ticket Details

Ticket details can display:

- Ticket Information
- Requester
- Technician
- Status
- Priority
- Category
- SLA Deadline
- Activity Timeline
- Internal Notes
- Resolution Information
- Related Tickets

### User Management

Manage support requesters.

User information can include:

- Name
- Email
- Phone
- Department
- Company
- Status
- Notes

User profiles can show:

- Open Tickets
- Resolved Tickets
- Ticket History
- Recent Activity

### Technician Management

Manage support technicians.

Technician information can include:

- Name
- Email
- Phone
- Role
- Specialization
- Status

Technician profiles can show:

- Assigned Tickets
- Open Tickets
- Resolved Tickets
- Overdue Tickets
- Average Resolution Time
- Workload

### Categories

Organize tickets into categories.

Examples:

- Hardware
- Software
- Network
- Account
- Email
- Printer
- Security
- Access
- Other

### Priorities

Support four standard ticket priorities:

- Low
- Medium
- High
- Urgent

Priority badges make important tickets easier to identify.

### Ticket Assignment

Tickets can be:

- Unassigned
- Assigned to a Technician
- Reassigned to another Technician

Assignment changes should be stored in ticket activity history.

### SLA Tracking

Track ticket response and resolution deadlines.

SLA settings can depend on ticket priority.

Example:

- Low: 72 hours
- Medium: 48 hours
- High: 24 hours
- Urgent: 8 hours

The interface can show:

- SLA Deadline
- Remaining Time
- Overdue State
- SLA Compliance

### Ticket Activity

Track important ticket actions.

Examples:

- Ticket Created
- Technician Assigned
- Status Changed
- Priority Changed
- Note Added
- Ticket Resolved
- Ticket Reopened
- Ticket Closed

### Internal Notes

Add internal notes to tickets.

Notes can include:

- Author
- Message
- Date
- Time

### Ticket Resolution

Resolved tickets can store:

- Resolution Summary
- Resolution Date
- Technician
- Resolution Notes

Resolved tickets can later be:

- Reopened
- Closed

### Search

Search tickets using:

- Ticket Number
- Title
- User Name
- Technician
- Category

### Filters

Filter tickets by:

- Status
- Priority
- Category
- Technician
- SLA State
- Date

### Sorting

Sort tickets by:

- Created Date
- Updated Date
- Priority
- Due Date
- Ticket Number

### Analytics

Analyze help desk performance.

Metrics can include:

- Ticket Volume
- Resolution Rate
- SLA Compliance
- Average Resolution Time
- Open vs Closed Tickets
- Tickets by Priority
- Tickets by Category
- Technician Performance

Charts can include:

- Tickets Over Time
- Tickets by Status
- Tickets by Priority
- Tickets by Category
- Technician Workload
- SLA Compliance

### Reports

Reports can include:

- Ticket Report
- Open Ticket Report
- Overdue Ticket Report
- SLA Report
- Technician Report
- Category Report
- Resolution Report

### Activity Log

View recent system activity.

Examples:

- Ticket Created
- Ticket Assigned
- Ticket Updated
- Ticket Resolved
- User Created
- Technician Created

### Import & Export

Application data can be managed locally.

- Export JSON Backup
- Import JSON Backup
- Merge Data
- Replace Data
- Validate Imported Data

### Settings

Settings can include:

- Organization Name
- Default Priority
- SLA Rules
- Date Format
- Time Format
- Theme
- Compact Mode
- Default Table Page Size

## Light & Dark Mode

Includes:

- Light Theme
- Dark Theme

Theme preference can be stored in the browser.

## Responsive Design

Designed for:

- Smartphones
- Tablets
- Laptops
- Desktop Computers

Tables, ticket cards, forms, filters, dialogs, charts, and navigation adapt to different screen sizes.

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Browser localStorage
- Chart.js
- Lucide Icons

No backend, framework, database, authentication server, or API key is required.

## Suggested Project Structure

```text
it-help-desk-ticket-management-system-web-template/
│
├── index.html
├── tickets.html
├── users.html
├── technicians.html
├── categories.html
├── activity.html
├── analytics.html
├── reports.html
├── settings.html
│
└── assets/
    ├── css/
    │   ├── variables.css
    │   ├── base.css
    │   ├── layout.css
    │   ├── components.css
    │   ├── forms.css
    │   ├── tables.css
    │   └── responsive.css
    │
    └── js/
        ├── core/
        ├── ui/
        ├── data/
        └── modules/
```

## Data Storage

Application data can be stored using browser `localStorage`.

Stored information may include:

- Tickets
- Users
- Technicians
- Categories
- Ticket Notes
- Ticket Activities
- SLA Settings
- Application Settings

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Erhanalp35/it-help-desk-ticket-management-system-web-template.git
```

Open the project:

```bash
cd it-help-desk-ticket-management-system-web-template
```

Then open:

```text
index.html
```

No backend setup is required.

## Demo Data

The first launch may include realistic demo data such as:

- Support Users
- Technicians
- Categories
- Open Tickets
- Urgent Tickets
- Resolved Tickets
- Overdue Tickets
- Activity Records

Demo data should never overwrite valid existing user data.

## Privacy

All application data can remain inside the browser.

No remote server or cloud database is required.

## Future Improvements

Possible future additions:

- Real Authentication
- Role-Based Permissions
- Email Ticket Creation
- Knowledge Base
- Customer Portal
- Automated Assignment
- File Attachments
- Real Notifications
- Backend Database
- Cloud Synchronization

## Contributing

Contributions, bug reports, and feature suggestions are welcome.

## License

This project is licensed under the MIT License.
