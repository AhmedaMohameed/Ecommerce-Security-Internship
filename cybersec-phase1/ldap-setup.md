# LDAP Setup

Configured centralized directory-based authentication using **OpenLDAP** and a web interface for management via **phpLDAPadmin**.

### 🛠️ Setup Details:

- Installed required LDAP packages:
  - `slapd` (OpenLDAP server)
  - `ldap-utils` (LDAP command-line tools)
- Configured directory domain: `dc=example,dc=com`
- Set up **admin password** during installation for secure access
- Installed and configured **phpLDAPadmin** for GUI-based LDAP management
- Created:
  - A **test organizational unit (OU)**
  - A **sample user entry** within the directory
  - A **test group** to validate group-based access control

> 📷 Refer to `screenshots/ldap-setup/` for installation output and entry creation confirmation.
