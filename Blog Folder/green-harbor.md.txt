Green-harbor.md

# Green Harbor Sanitation IAM Portfolio. 
## CEO dash Olivia Bennett. 
![Olivia Bennett dash CEO] (images/olivia-ceo.png)

## User Creation
[all users] (screenshots/allusers.png)

Created fictional Green Harbor sanitation users across exec, HR, IT, finance, and operations, and set manager relationships for identity governance scenarios.

## Security Groups
![all groups] (screenshots/all-groups.png)

Created security groups for departments and job functions to support conditional access and app assignments.

## Application Developer role assignment 
![Application Developer] (screenshots/applicationdeveloper.png)

Assigned the Application Developer role to Louis Sanchez to let him register and manage apps without broader admin rights, following least privilege.

## Custom HR Role
![HR Helpdesk Admin] (screenshots/HRHelpdeskrole.png)

Created a custom HR help desk role with limited permissions to update basic user profiles, reset passwords, and manage group memberships, demonstrating RBAC and least privilege.

## Policies
![Policies] (screenshots/policies.png)

Configured multiple conditional access policies to strengthen identity security. Blocked legacy authentication protocols in report-only mode. Required MFA for members of the IT staff group, and required MFA for administrators, which together protect accounts and organizational resources by enforcing modern authentication and role-based controls.

## Identity Governance 
![Catalogs] (screenshots/Catalogs.png)
![Access package] (screenshots/accesspackage.png)

Created the Green Harbor Employee Resources catalog to organize company groups in a central location. Created the IT staff onboarding access package to automate access requests for new IT employees, streamlining onboarding through a governed approval process. 

## Privileged Identity Management (PIM)
![Daniel Kim Conditional Access Admin] (screenshot/DanielKimConditional.png)
![Eligible Admin Status] (screenshot/Eligible.png)

Assigned the Conditional Access Administrator role to Daniel Kim. This allows him to create and manage conditional access policies without granting broader admin permissions. Also, updated Daniel Kim’s role assignment from active to eligible using Microsoft Entra Privileged Identity Management. This enables just in time access, so he activates the role only when he needs to perform admin tasks.

## Access Review
![Access Review for Conditional Access Admin] (screenshot/accessreview)

Created a quarterly access review for users eligible for the Conditional Access Administrator role, ensuring privileged access is periodically validated and unnecessary permissions are removed.

This project demonstrates the implementation of a secure IAM environment using Microsoft Entra ID for the fictional Green Harbor Sanitation. It includes user and group management, RBAC, custom roles, conditional access policies, identity governance with catalogs and access packages, privileged identity management, and access reviews, all aligned to least privilege and Zero Trust principles. This hands-on project demonstrates the ability to design, implement, and document core Microsoft Entra ID IAM solutions applying best practices for enterprise environments.











