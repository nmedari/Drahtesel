### Quality Policy

**GitHub Workflow** (start Sprint 1)

Tools and Environments 
• Version Control: We use Git and GitHub for managing source code and collaborating across the team. We follow a branching strategy where each feature, bug fix, or enhancement is developed on separate branches. 
• Development Environments: Development is carried out in IntelliJ, with Gradle as the build tool. 
• Project Management: We use Taiga to track tasks, sprints, and project progress. Each sprint typically lasts two weeks, and tasks are assigned according to team roles.

Step-by-Step Process 
• Planning & Requirements Gathering: 
  o During the initial phase, the product owner or project lead gathers requirements and creates user stories or tasks. These are entered into a task management tool such as Jira. 
• Branching & Development: 
  o Developers create a feature branch based on the master or main branch for new features or bug fixes (git checkout -b feature/branch-name). 
  o Code is written according to the task description and committed regularly. 
  o The IDE or build tool Gradle is used for local builds and testing.
• Code Reviews: 
  o Once a feature is complete, developers push their branch to the remote repository and create a pull request (PR) for review. 
  o Team members review the PR for code quality, adherence to standards, and functionality. 
• Testing: 
  o After code is reviewed, it undergoes unit testing using frameworks like JUnit (for Java). Automated tests are run as part of the build pipeline. 
• Merging & Continuous Integration: 
  o Once tests pass and the review is approved, the feature branch is merged back into develop. 
  o Our CI/CD pipeline (GitHub Actions) automatically triggers after each merge, running tests and building the project.

Roles and Responsibilities Describe who is responsible for which parts of the workflow. For instance: 
• Developers: Work on feature branches, write code, conduct unit testing, and submit pull requests for review. 
• Git master: Leads review pull requests to ensure code quality and adherence to best practices. 
• Scrum master: Responsible for running manual or automated tests and ensuring the product meets the required quality standards.

Best Practices and Adaptability 
• Best Practices: 
  o We follow coding standards and use linters (Checkstyle) for code consistency. 
  o We ensure high code coverage with unit tests and strive for clear, meaningful commits. • Adaptability: 
  o Our workflow is flexible, allowing adjustments based on project complexity and team availability. For instance, if a critical issue arises, we can fast-track bug fixes using a hotfix branch and deploy immediately.

**Unit Tests Blackbox** (start Sprint 2)
  > Describe your Blackbox testing policy 

 **Unit Tests Whitebox** (online: start Sprint 2, campus: start Sprint 3)
  > Describe your Whitebox testing policy 

**Code Review** (online: start Sprint 2, campus: start Sprint 2)
  > Describe your Code Review policy for on campus it is ok to have a less formal process in Sprint 2, should be updated in Sprint 3 though

  > Include a checklist/questions list which every developer will need to fill out/answe when creating a Pull Request to the Dev branch. 

  > Include a checklist/question list which every reviewer will need to fill out/anser when conducting a review, this checklist (and the answers of course) need to be put into the Pull Request review.

**Static Analysis**  (online: start Sprint 3, campus: start Sprint 3)
  > Your Static Analysis policy   

**Continuous Integration**  (start Sprint 3, campus: start Sprint 3)
  > Your Continuous Integration policy
