# Class 8 notes - Access Control

## 5 steps to RBAC

**What is Role Based Access Control (RBAC) and why do we care?**
Assigning system access to users based on their role in an organization.

**Describe a Role/Permission heirarchy that you might implement using RBAC.**
Admin rights to developers, user rights to most other employees.

**What approach might you take to implement RBAC?**
The system needs of a given workforce are analyzed, with users grouped into roles based on common job responsibilities and system access needs. Access is then assigned to each person based strictly on their role assignment.

## wiki - RBAC

**If Authentication is “you are who you say you are,” what is Authorization?**
Are you allowed to access based on who you are.

**Name three primary rules defined for RBAC.**
1. Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
2. Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
3. Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

**Describe RBAC to a non-technical friend.**
Assigning access rights based on what you need to be able to access to complete your work.

## RBAC tutorial

**What Are access rights Associated with? The User? or The Role? Explain.**
Role, the user gets associated with the role as well. This makes it easier to control the access rights.

**Access Rights, or Authorization, is activated after a user successfully does what?**
Authenticates themselves

**Explain how RBAC might benefit a business.**
Policy wont need to change when personnel does.
