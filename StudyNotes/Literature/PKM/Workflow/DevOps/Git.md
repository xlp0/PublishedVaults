---
Aliases: Git, git
---
#Git #version_control #order #time #content_addressable

[[Git]] is a distributed version control system that allows developers to track changes in their codebase and collaborate with others. It is commonly used in software development projects to manage source code and ensure efficient collaboration among team members.

In the context of Data Asset Management (DAM), Git can be utilized to manage data assets along with the associated code. This means that not only can developers track changes made to the code, but they can also track changes made to the data files. By storing and versioning data assets in Git repositories, teams can ensure that everyone is working with the same dataset and easily roll back to previous versions if needed. This becomes particularly useful in scenarios where data pipelines or machine learning models are involved, as it allows for better reproducibility and traceability of results.

Regarding [[DevOps]], Git plays a crucial role in facilitating the [[CICD|continuous integration and continuous delivery]] (CI/CD) practices. [[CICD|CI/CD]] is an essential part of DevOps methodology that emphasizes frequent code integration, testing, and deployment. Git enables developers to maintain different branches for separate features or bug fixes, allowing them to work on isolated tasks without disrupting the main development branch. These branches can then be merged back into the main branch through pull requests after thorough review and testing.

Moreover, Git integrates seamlessly with various CI/CD tools like Jenkins, Travis CI, or CircleCI. These tools automate build processes, run tests, and deploy applications based on changes detected in the Git repositories. By leveraging Git's version control capabilities within a DevOps workflow, teams can achieve faster iterations, improved collaboration between developers and operations teams, and ultimately deliver higher-quality software products.

## Who invented GIt?

Git was invented by [[Linus Torvalds]], the same person who created the Linux operating system. He developed Git in 2005 as a distributed version control system to manage the Linux kernel development process.

In summary, Git serves as an integral tool for both [[Data Asset Management]] and DevOps practices. It enables efficient version control of both code and data assets in DAM scenarios while supporting collaborative development workflows and facilitating CI/CD processes in DevOps environments.

## Tips on Obsidian
When working with Obsidian Git, it is important to avoid automatic commits. It can be done by setting the default cycle time for updates to 0.

## References

![[@d-i-ryGitGraphEasiest2021|Git Graph: the easiest way to start using git]]
