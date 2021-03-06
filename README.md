
# Managed Instance code samples
This is a repository of code samples to use with Azure SQL Database Managed Instance (MI).

1. sp_readmierrorlog.sql is a stored procedure that provides a filtered and more readable version of the MI error log.
2. perf-counters-mi.sql is a script that collects performance counters on MI.
3. MIGP_storage_perf_limits.sql is a script that examines IOPS/throughput per database file over a period of time on MI General Purpose, and compares them against Azure Premium Storage limits. The script helps in determining if using larger files/blobs with higher limits would be beneficial for improving workload performance.
