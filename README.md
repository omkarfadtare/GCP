___`Cloud Console`___ is an in-browser UI that lets you access and manage Google cloud services.
A Google Cloud project is an organizing entity for your Google Cloud resources. It often contains resources and services; for example, it may hold a pool of virtual machines, a set of databases, and a network that connects them together. Projects also contain settings and permissions, which specify security rules and who has access to what resources.
A Project ID is a unique identifier that is used to link Google Cloud resources and APIs to your specific project.
 credentials represent an identity in the Cloud Identity and Access Management (Cloud IAM) service. This identity has access permissions (a role or roles) that allow you to work with Google Cloud resources in the project you've been allocated.
 The Google Cloud console title bar also contains the Navigation menu icon, which appears as three lines:
 Google Cloud also contains a collection of permissions and roles that define who has access to what resources.Cloud Identity and Access Management (Cloud IAM) service to inspect and modify these roles and permissions.

| Role Name    | Permissions                                                                                                                                                                                                                                               |   |
|--------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| roles/viewer | Permissions for read-only actions that do not affect state, such as viewing (but not modifying) existing resources or data.                                                                                                                               |   |
| roles/editor | All viewer permissions, plus permissions for actions that modify state, such as changing existing resources.As an editor, you can create, modify, and delete Google Cloud resources. However, you can't add or delete members from Google Cloud projects. |   |
| roles/owner  | All editor permissions and permissions for the following actions: manage roles and permissions for a project and all resources within the project; set up billing for a project.                                                                          |   |

Google Cloud APIs are a key part of Google Cloud. Like services, the 200+ APIs, in areas that range from business administration to machine learning, all easily integrate with Google Cloud projects and applications.
APIs are application programming interfaces that you can call directly or via the client libraries. Cloud APIs use resource-oriented design principles


