# How Remo handles employee and organization data.

Effective date: May 14, 2026

Remo is a workforce management application provided by ZTensor for organizations that need transparent, session based work-zone verification. This Privacy Policy explains what information Remo collects, why it is collected, how it is protected, and how users can request deletion.

**Background location disclosure:**
Remo collects location data to verify your presence in the work zone even when the app is closed or not in use. This occurs only while you have an active work session running. Remo does not track location after a work session is stopped or ended.

## Information We Collect

* **Account information:** name, email address, role, organization, department, phone number when provided, and account status.
* **Organization information:** company name, work zones, geofence assignments, retention settings, and admin-managed configuration.
* **Work session information:** session start and end times, assigned geofence, break periods, session notes, end reason, and summary durations.
* **Precise location data:** latitude, longitude, accuracy, ping time, and related session metadata collected during active work sessions.
* **Device and app information:** device platform, app version, battery level when reported, push token records when notifications are configured, and diagnostic logs.
* **Support and privacy requests:** messages or details submitted when requesting help, export, correction, or deletion.

## How We Use Information

* Authenticate users and route them to employee or admin features.
* Verify that employees are inside assigned active work zones before and during a work session.
* Display active sessions, alerts, reports, and attendance summaries to authorized organization admins.
* Give employees visibility into their own active sessions, session history, and recorded ping trail.
* Maintain audit logs, security controls, and tenant separation.
* Support legal, payroll, compliance, troubleshooting, and abuse-prevention needs.

## When Location Is Collected

Remo requests location permission because the app must verify employee presence in assigned work zones. Location is collected only after an employee starts a work session and accepts the required disclosures and permissions. During an active session, the app may collect location in the background so that geofence compliance remains accurate if the app is closed or the screen is locked. A persistent session notification is shown while tracking is active.

Tracking stops when the work session ends, when the employee manually stops the session, or when server-side rules end the session after a geofence exit.

## How Information Is Shared

Remo does not sell personal information and does not use employee data for advertising. Information may be shared with:

* Authorized admins within the user's organization.
* Service providers used to operate Remo, including Supabase for backend infrastructure, Google Maps for maps, and diagnostic providers when configured.
* Legal, regulatory, or security parties when required to comply with law or protect the service.

## Security

Remo uses encrypted network connections, Supabase Row Level Security, organization scoped database policies, server-side RPCs for protected business logic, and audit logging for sensitive actions. No service role keys are embedded in the mobile app.

## Retention

Detailed location pings are retained according to the organization's retention setting, with a default target of 90 days. Work session summaries, payroll-related records, audit logs, and compliance records may be retained longer when required by the employer, law, or legitimate business needs.

## Your Choices and Deletion Requests

Employees can review recorded session history in the app and can request account deletion from **Settings > Request account deletion**. Users can also submit a request through the public deletion instructions at [delete-account.md](delete-account.md).

When an employee requests deletion, Remo disables access, purges detailed location pings, disables push tokens, removes geofence assignments, and records an audit event. Session and payroll summaries may be retained by the employer for compliance.

## Children

Remo is intended for workplace use and is not directed to children.

## Changes to This Policy

We may update this Privacy Policy as Remo changes. Updates will be posted on this page with a new effective date.

## Contact

For privacy questions or deletion requests, contact [support@ztensor.com](mailto:support@ztensor.com).
