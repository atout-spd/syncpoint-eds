# Adobe Cloud Manager - external repositories (beta)



| Section Metadata | |
|---|---|
| Style | Adobe Cloud Manager - external repositories (beta) |

## Adobe Cloud Manager - external repositories (beta)

The Point:
Adobe is rolling out external GIT repository integration, we are ready to help you implement it.

In the evolving world of Adobe Experience Manager (AEM), both AEM as a Cloud Service (AEMaaCS) and Adobe's AEM Managed Services (AMS) have long required code to be deployed to Adobe's hosted Git repository before reaching any Adobe-hosted environments.

This requirement stems from Adobe's Cloud Manager CI/CD framework, which performs necessary checks on the code, executes builds via containerized build services, and facilitates the tagging of releases in the repository once the production deployment is completed.

The Need for Private Repositories in AEMaaCS and AMS
AEMaaCS and AMS customers have faced various complexities and limitations when using Adobe's hosted Git repository, prompting many to seek the ability to use private Git repositories with Adobe's cloud-hosted AEM. Several key challenges have made this highly desirable:

1. Managing Multiple Repositories
The Adobe-hosted Git repository serves solely as a deployment repository and is not intended to be the primary source for developing an AEM site. It does not offer Service Level Agreements (SLAs) for availability or backups, meaning developers must maintain their own internal repository in parallel with the Adobe repo. This dual-repository approach requires careful management to keep the two repositories in sync, adding complexity to the development workflow.

2. Limitations in Key Git Features
Adobe's Git repository lacks several key features, such as pull requests and thread management, which are essential for certain stages of development. For example, in a typical development workflow, developers would open a pull request (PR) to review and validate new features. However, Adobe's repository does not support PRs, which can create challenges for quality assurance and code collaboration.

Without the ability to run full test suites outside of the Adobe CI/CD pipeline, developers must rely on their own internal processes to identify issues like security violations or performance degradation. This can lead to situations where a new feature is approved based on an incomplete or untested build, resulting in potentially costly failures once the code is committed to Adobe's Git repository.

3. Challenges with Security and User Management
Adobe's Git repository also lacks fine-grained user management and access control features. This forces teams to implement their own security measures in their internal Git repositories, relying on custom-built automation to control which branches, commits, and changes make it into Adobe's hosted Git. While this is achievable, it adds another layer of complexity and potential for error, which can hinder a smooth, secure deployment process.

The Road Ahead
For organizations looking to streamline their workflows, the push for private repositories in AEMaaCS and AMS represents a significant opportunity to enhance collaboration, improve security, and simplify the development process. By enabling private Git repositories, Adobe is offering a more flexible, integrated solution that better meets the needs of modern development teams and supports efficient, reliable deployments across the board. read more here


| Metadata | |
|---|---|
| Title | Adobe Cloud Manager - external repositories (beta) |
| Description | AEMaaCS and AMS customers have faced various complexities and limitations when using Adobe's hosted Git repository |
| Canonical | https://www.syncpointdigital.com/post/adobe-cloud-manager---external-repositories-beta |
| og:description | AEMaaCS and AMS customers have faced various complexities and limitations when using Adobe's hosted Git repository |
| og:image | /media/insights__67c3cc96d95b150d2afa9c1d_git-repo.jpg |
| og:title | Adobe Cloud Manager - external repositories (beta) |
| og:type | website |
| twitter:card | summary_large_image |
