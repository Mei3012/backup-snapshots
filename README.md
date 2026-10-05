# backup-snapshots

Periodic exports of small configuration bundles. Each snapshot is a
single opaque text file, kept for rollback only.

## Layout

- `export/<bucket>/` – one file per snapshot, never edited in place
