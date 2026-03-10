**Unofficial community snap package for the DuckDB CLI shell, built from source.**

DuckDB (https://duckdb.org) is an in-process SQL OLAP database management system designed to support analytical query workloads. It provides a rich SQL dialect with deep integrations for Python, R, Java, and more.

**Features:**
- Built from the official DuckDB release tarball (https://github.com/duckdb/duckdb) with SHA256 checksum verification
- Available for **amd64** and **arm64** architectures
- Strict confinement with minimal permissions
- Automatically updated when new DuckDB versions are released

**Prefer official installation?**
If you don't need the snap format, consider installing DuckDB directly from the official channels: https://duckdb.org/docs/installation

**Quick start:**
`duckdb` to launch the interactive shell, or `duckdb mydata.duckdb` to open a persistent database.

**Links:**
- DuckDB documentation: https://duckdb.org/docs
- Snap source: https://github.com/DataGoblin/duckdb-snap

*This package is not affiliated with or endorsed by the DuckDB Foundation. DuckDB is a trademark of the DuckDB Foundation.*

*Icon: Database icon created by srip - Flaticon (https://www.flaticon.com/free-icon/database_3630471)*