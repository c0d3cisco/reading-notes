# Access Control (ACL)

## [5 steps to RBAC](https://www.csoonline.com/article/3060780/security/5-steps-to-simple-role-based-access-control.html)

1. What is Role Based Access Control (RBAC) and why do we care?\
RBAC is the idea of assigning system access to users based on their role within an organization and we care because it makes the software infrastructure of large organizations more secure.
2. Describe a Role/Permission hierarchy that you might implement using RBAC.\
Depends on the organization, but you might have something like System Admin which has access to everything, Project Admins which would have access to specific projects, and User roles, which could have a subset of permissions within projects.
3. What approach might you take to implement RBAC?\
Improve your systems, analyze your workforce and create roles, assign people to roles, never make one-off changes, and audit.

## [Wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

1. If Authentication is “you are who you say you are,” what is Authorization?\
"You do/do not have permission to be here"
2. Name three primary rules defined for RBAC.

>1. Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
>2. Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
>3. Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

3. Describe RBAC to a non-technical friend.\
It is a system for setting up accounts in a software system to restrict access to certain features or areas. Think of parental control on Netflix. You have the main account which has permissions to make new accounts and manage the permissions of those, i.e assigning an account as a kid's account. The kid account has restrictions that prevent viewing of certain shows and managing account settings.

## [RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)

1. What are Access Rights associated with? The User? or The Role? Explain.\
Access Rights are associated with the Role.
2. Access Rights, or Authorization, is activated after a user successfully does what?\
After they authenticate themselves.
3. Explain how RBAC might benefit a business.

>* Policy doesn't need to change when a person leaves the organization.
>* New employ is easy to add.
>* Easy to manage access as only action required is changing roles.

## Reflection

1. What are your learning goals after reading and reviewing the [class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-08/)?\
My goal is to understand how roles are assignment permissions.
