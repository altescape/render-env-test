# render-env-test
A test repo for Render blueprint deployment for staging and prod environments to determine problems.

- M: Determine headers (any simple header should be fine) are updated when merging staging to main branch
- M: Determine env vars are updated
- M: Document any problems or idiosyncrasies


## Results
- Blueprint is based on main (or whatever branch you pulled in the blueprint project in on originally), so any env settings will only change when blueprint is updated on main branch.
- If updating something in staging then only staging is deployed.
- If updating something in main then only main is deployed.
