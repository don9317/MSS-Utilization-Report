# MSS Utilization Dashboard v1.11

GitHub Pages package. Upload `index.html` to the repository root.

## Restored from v1.10
- MSS Reservations CSV upload
- Internal Bookings CSV upload
- Facility setup file load/export
- Browser-saved facility profiles
- Merge Files, date, sport, and multi-space filters
- Utilization, revenue, internal value, value heatmaps, and monthly trends

## New utilization engine
- Parent/child alternatives are consolidated into physical rentable assets.
- Court 1 / Court 1 West / Court 1 East count as one physical court asset.
- Courts 2-4 follow the same rule.
- Legacy a/b/c court labels remain recognized.
- Full Field blocks Tunnel 1-7 and Practice Turf; child rentals block Full Field.
- Overlapping reservations on the same physical asset count only once in utilization.
