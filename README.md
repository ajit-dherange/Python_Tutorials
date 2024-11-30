# Python_Tutorials

## How to install jdbc driver for python offline on windows 2019 server:
```
1) Download Python 3.13:
https://www.python.org/downloads/

2) Download get-pip.py:
https://bootstrap.pypa.io/get-pip.py

3) Download Python Libraries:
pip download JayDeBeApi JPype1

3) Download Microsoft JDBC Driver 12.8 for SQL Server:
URL https://learn.microsoft.com/en-us/sql/connect/jdbc/download-microsoft-jdbc-driver-for-sql-server?view=sql-server-ver16
download ZIP file directly: https directly://go.microsoft.com/fwlink/?linkid=2283744

4) Move downloaded files to the Server and Place JDBC .jar file in a directory on the server (e.g., C:\jdbc\drivers\).

5) Install the libraries using pip:
pip install JPype1‑<version>.whl
pip install JayDeBeApi‑<version>.whl

```
