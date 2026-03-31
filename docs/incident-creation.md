# Incident Creation Logic

A Business Rule automatically converts events into incidents.

## Mapping

Severity → Priority

1 → Priority 1 (Critical)
2 → Priority 2 (High)
3+ → Priority 3 (Moderate)

## Fields

- Short Description ← Event Description
- Description ← Event Source
- Priority ← Based on severity

After creation:
- Incident is linked to event
- Event status is updated to Processed
