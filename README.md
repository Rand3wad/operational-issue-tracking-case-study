# Operational Issue Tracking System — Case Study

> Sanitized portfolio case study based on a real internal system developed during my Software Engineering Co-op. Organizational details, internal data, production endpoints, and proprietary source code are intentionally excluded.

## Overview

This project digitized an operational issue-reporting workflow that had previously relied on manual follow-up. The system provides a structured way to report issues, assign responsibility, track progress, notify relevant users, and document resolution.

## Problem

The existing process made it difficult to consistently:

- Capture issues in a standard format
- Route issues to the right responsibility
- Track status and priority
- Follow up on unresolved items
- Keep supporting images and notes together
- Maintain visibility across the issue lifecycle

## Solution

The system introduced a centralized ticket workflow:

```text
Report Issue
    ↓
Assign / Route
    ↓
Notify Responsible User
    ↓
Track Status & Priority
    ↓
Add Updates / Evidence
    ↓
Resolve Issue
    ↓
Validate Closure
```

## Key Capabilities

- User authentication
- Ticket creation
- Priority and status tracking
- Location and responsibility fields
- Assignment and referral workflows
- Image attachments
- Notifications
- Search and filtering
- User-specific views
- Resolution notes and follow-up

## Technology

- HTML
- CSS
- JavaScript
- Firebase Authentication
- Cloud Firestore
- Firebase Hosting
- External email/notification integration

## My Role

I contributed across the project lifecycle, including:

- Understanding the operational workflow and user needs
- Translating requirements into ticket and routing logic
- Contributing to frontend and backend-related implementation
- Supporting authentication and role-related behavior
- Working with ticket fields, statuses, priorities, assignment, and resolution flows
- Functional testing and user validation
- Troubleshooting issues after deployment
- Iterating on the system based on user feedback

## Requirements & Workflow Analysis

The system was shaped around real operational needs such as:

- Who reports the issue
- Which location it belongs to
- Which responsibility owns it
- Who should be notified
- How priority affects follow-up
- How issue status changes over time
- What information is required before closure

This required connecting user needs to system behavior rather than treating each screen as an isolated feature.

## Testing & Validation

Testing included:

- Authentication flows
- Ticket creation and editing
- Required-field validation
- Role and permission checks
- Assignment/referral behavior
- Search and filter behavior
- Notification behavior
- Status transitions
- User validation and retesting after changes

## Post-Deployment Support

After deployment, I also contributed to troubleshooting and improvements based on real user feedback.

One example involved email delivery to protected corporate inboxes. Multiple configurations and providers were investigated until a working and validated approach was identified.

## What This Project Demonstrates

This project demonstrates experience with:

- Requirements analysis
- Workflow design
- Full-stack web development
- Firebase-based application development
- Role-based workflows
- Functional testing
- User validation
- Troubleshooting
- Post-deployment support
- Iterative improvement

## Confidentiality

The original implementation remains private because it contains organization-specific details.

This public case study uses generalized terminology and intentionally excludes:

- Internal email addresses
- Production endpoints
- Real employee information
- Internal organizational structure
- Proprietary screenshots
- Production credentials
