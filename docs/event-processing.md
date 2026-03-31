# Event Processing

Each incoming alert is stored in the event table.

Fields include:
- Event ID
- Source
- Severity
- Description
- Status
- Related Incident

Status Flow:
New → Processed

Processed events are linked to incidents.
