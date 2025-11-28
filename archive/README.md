# Grafana Dashboard Archive

This directory contains archived dashboard versions that have been superseded by newer implementations.

## Archived Dashboards

### `app_dashboard_v6_archived_20251128.json`
- **Archived**: November 28, 2025
- **Reason**: Superseded by `app_dashboard_v7.json`
- **Changes in v7**:
  - Enhanced panel layouts
  - Improved metric queries
  - Updated visualization settings
  - Better dashboard organization

The v6 dashboard is preserved here for historical reference and rollback purposes if needed.

## Restoration Instructions

If you need to restore an archived dashboard:

1. Copy the archived file back to the root directory
2. Rename to remove the `_archived_YYYYMMDD` suffix
3. Import into Grafana via the UI or API

```bash
# Example restoration command
cp archive/app_dashboard_v6_archived_20251128.json ../app_dashboard_v6.json
```

---

**Archive Policy**: Dashboard versions are archived (not deleted) when superseded to maintain historical record and enable quick rollbacks if issues are discovered with newer versions.
