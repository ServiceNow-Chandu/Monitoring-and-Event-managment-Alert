# Deduplication Logic

Duplicate alerts can overwhelm systems and create unnecessary incidents.

To prevent this, a Business Rule checks:

- Event ID
- Status = New

If a duplicate event is found:
- Insert is aborted
- Event is ignored

This ensures only unique alerts are processed.
