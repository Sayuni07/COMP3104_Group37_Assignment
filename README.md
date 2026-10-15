# COMP3104_Group37_Assignment

## Group Members
- **Leader:** Sayuni Wimaladharma (101563313) - [Github](https://github.com/Sayuni07)

- **Member 2:** Tanzeem Shaikh (101585484) - [GitHub](https://github.com/Tanzeem240)
- **Member 3:** Daviti Sidana (101540372) - [GitHub](https://github.com/Daviti891)
- **Member 4:**

## Project Description
This repository hosts the group assignment for COMP3104 DevOps. It focuses on collaborative Git workflows, branching strategies, pull requests, merge conflict resolution, and CI/CD integration using GitHub Actions.

## Setup Instructions
1. Clone the repository: `https://github.com/Sayuni07/COMP3104_Group37_Assignment`
2. Move into the folder: `cd COMP3104_Group37_Assignment`
3. Create your branch: `git checkout -b STUDENTID-Name`
4. Push your branch: `git push -u origin STUDENTID-Name`

## CI/CD Pipeline
The project uses GitHub Actions for continuous integration. The workflow is defined in `.github/workflows/ci.yml` and runs on every push using an `ubuntu-latest` runner. It checks out the repository code and runs simple echo commands to confirm the pipeline is working. Results can be viewed in the Actions tab.

## Branching Strategy
We use a per-developer branching strategy. Each member works on their own branch named `STUDENTID-Name`, and all changes are merged into `main` through Pull Requests. This protects `main` from untested code, lets members work independently, and allows peer review before merging.
