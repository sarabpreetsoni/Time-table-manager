# Timetable Manager

This repository previously contained a standalone single-file HTML app (using Supabase via CDN and vanilla JS).

That file has been moved to [`archive/Timetable Manager.html`](./archive/Timetable%20Manager.html) for historical reference.

## Active Project

The active, production-grade version of the Timetable Manager is the **React + TanStack Start + Supabase** app located at:

```
../easy-store-backend/
```

It features:
- Cloud-synced data via Supabase (PostgreSQL + Realtime)
- Role-based access control (view = anon, edit = authenticated)
- CSV & PDF export
- Conflict detection for schedule overlaps
- Adjustment history log
