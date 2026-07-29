# MSS Utilization Dashboard v1.12

## Included files
- `index.html` — GitHub Pages dashboard
- `facility_setup_template.mss` — editable template for each facility
- `README.md` — setup instructions
- `RELEASE_NOTES.md` — version changes

## Facility setup workflow
1. Copy `facility_setup_template.mss`.
2. Rename it for the facility, such as `hive-setup.mss`.
3. Open the copy in Notepad and change the facility name, operating hours, and parent/child space families.
4. In the dashboard, use **Load Facility Setup File**.
5. The easier alternative is to open **Space Setup**, configure the facility, and click **Export Setup**.

### Family modes
- `singleUnit`: the parent and all children represent one physical rentable asset. Example: Court 1 / Court 1 West / Court 1 East.
- `childUnits`: the parent blocks all children, but children may count as separate rentable units when the parent is not rented. Example: Full Field / tunnels / Practice Turf.
