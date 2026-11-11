
# Active Directory Security Group Management

## Overview

This repository covers security group management in Microsoft Active Directory.

Security groups help administrators manage user access to shared resources, applications and systems.

## Common Administration Tasks

- Creating security groups
- Adding users to groups
- Removing users from groups
- Reviewing group memberships
- Checking group scope and type
- Troubleshooting access issues

## Security Group Types

Active Directory supports two main group types:

- Security groups: Used to assign permissions.
- Distribution groups: Used mainly for email distribution.

## Group Scopes

### Global Groups

Typically used to organize users with similar roles within a domain.

### Domain Local Groups

Commonly used to assign permissions to resources within a domain.

### Universal Groups

Can contain members from multiple domains in the same forest, depending on group membership rules.

## Adding a User to a Security Group

1. Open Active Directory Users and Computers.
2. Find the required security group.
3. Open the group's Properties.
4. Select the Members tab.
5. Click Add.
6. Search for the required user.
7. Verify the user and confirm the change.
8. Check that the membership was updated.

## Access Management

Before changing group memberships:

- Verify the approved access request.
- Check the correct group.
- Review the access level provided by the group.
- Follow the principle of least privilege.
- Document the completed change.

## Basic Troubleshooting

| Issue | What to Check |
|---|---|
| User cannot access a resource | Group membership and resource permissions |
| Group not found | Domain and search location |
| Membership change not reflected | Sign-in session and replication status |
| Incorrect access | Nested groups and assigned permissions |
| Cannot update membership | Administrative permissions |

## Security Considerations

- Avoid unnecessary privileged group memberships.
- Review access regularly.
- Follow approved change procedures.
- Do not publish real user accounts or internal group names.

## Note

This repository contains general Active Directory documentation without company-specific information.
