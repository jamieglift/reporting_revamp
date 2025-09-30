## Reporting Revamp Ingest

Ingests relevant reporting data from Beeswax & Ipon APIs.
Writes reporting data to staging tables in workarounddb to be cleaned, normalised, and joined.

### Potential To-Dos

- Pull all from Performance report, exclude common columns from subsequent reports (these are likely unecessary, will reduce api fetch and cleaning job time)
- Reduce polling times on report fetch
- Ipon report export takes over a minute due to large number of dimensions included. Try to reduce fetch time.

