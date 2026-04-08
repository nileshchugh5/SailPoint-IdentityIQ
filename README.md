#  SailPoint IdentityIQ End-to-End Project

##  Overview
This project demonstrates a complete implementation of Identity Governance using SailPoint IdentityIQ.

It includes:
- Identity Lifecycle Management (Joiner, Mover, Leaver)
- Application Onboarding
- Access Certification
- Role-Based Access Control (RBAC)
- Segregation of Duties (SoD)
- Automated Provisioning

---

##  Architecture

HR System (CSV File)
        ↓
SailPoint IdentityIQ
        ↓
Business Application (Entitlements)
        ↓
Database Application (Provisioning)

---

## 🟢 HR Authoritative Application

- Created HR-App using CSV file
- Imported employee data
- Configured identity mappings
- Aggregated identities

### Output:
- Identities created
- Manager hierarchy established
- HR accounts linked

---

##  Business Application

- Created Business-App
- Configured correlation
- Defined entitlements

### Output:
- Accounts linked to identities
- Entitlements visible

---

##  Lifecycle Events

- Created Joiner event
- Triggered workflow

### Output:
- Log message for new joiners

---

## 🟣 Certification

- Manager certification configured
- Admin entitlement excluded

### Output:
- Certification campaigns launched
- Access reviews completed

---

##  Policy (SoD)

- Defined conflicting entitlements
- Executed violation task

### Output:
- Violations detected
- Work items generated

---

##  Database Application

- Configured JDBC application
- Created provisioning rules

### Output:
- Accounts provisioned
- Access managed automatically

---

##  RBAC

- Business Role created
- IT Role assigned
- Auto provisioning enabled

---

##  Lifecycle

### Joiner
- Account created automatically

### Mover
- Certification triggered

### Leaver
- Access revoked

---

##  Screenshots

Refer /screenshots folder

---

##  Tools Used

- SailPoint IdentityIQ
- Java
- MySQL
- Apache Tomcat

---

## Author
Chugh Nilesh 
