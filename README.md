# Oracle Pluggable Database (PDB) Administration Assignment

## Student Information

**Name:** Rudasingwa Felix

**Student ID:** 31599/2025

**Course:** Database Programming (DPR400210)

**Assignment:** Oracle Pluggable Database (PDB) Administration Assignment II

---

# Assignment Overview

The objective of this assignment was to practice Oracle Database Administration using Oracle Multitenant Architecture. The tasks included creating and managing a Pluggable Database (PDB), creating users inside the PDB, granting privileges, creating and deleting a temporary PDB, accessing Oracle Enterprise Manager Database Express, and documenting all practical activities using GitHub.

---

# Oracle Environment

- Oracle Database Version: Oracle Database 21c Express Edition (21.3.0.0.0)
- Operating System: Windows 10
- Tools Used:
  - Oracle SQL*Plus
  - Oracle Enterprise Manager Database Express
  - GitHub

---

# Task 1: Create and Configure a Pluggable Database

A new Pluggable Database named **RU_PDB_31599** was created successfully.

The PDB was opened in **READ WRITE** mode.

A database user named **rudasingwa_plsqlauca_31599** was created inside the PDB.

The following privileges were granted:

- CREATE SESSION
- CONNECT
- RESOURCE
- UNLIMITED TABLESPACE

The user successfully connected to the database.

---

# Task 2: Temporary PDB

A temporary Pluggable Database named **RU_TO_DELETE_PDB_31599** was created.

The temporary PDB was opened successfully.

It was then deleted using the DROP PLUGGABLE DATABASE command with INCLUDING DATAFILES.

The deletion was confirmed using the SHOW PDBS command.

---

# Task 3: Oracle Enterprise Manager (OEM)

Oracle Enterprise Manager Database Express was accessed successfully.

The Oracle environment and database information were verified through the OEM dashboard.

---

# Challenges and Solutions

### Challenge 1

While opening the PDB, the error **ORA-65104: operation not allowed on an inactive pluggable database** occurred.

### Solution

The incomplete PDB was dropped and recreated successfully.

### Challenge 2

During OEM login, the message **Invalid Container Name** appeared.

### Solution

The correct container name (**XEPDB1**) was used, allowing successful login.

---

# Lessons Learned

Through this assignment I learned how to:

- Create Oracle Pluggable Databases.
- Open and manage PDBs.
- Create Oracle users.
- Grant database privileges.
- Delete Pluggable Databases.
- Use Oracle Enterprise Manager Database Express.
- Document database practical work using GitHub.

---

# Integrity Statement

I confirm that this assignment represents my own practical work, screenshots, and documentation. All external resources consulted have been properly acknowledged.
