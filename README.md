# github-bootcamp-2023

Github bootcamp for 1st year student at CS CMU, Thailand (22 Nov 2023).

## more about CS-WIKI101

### Getting Started

Visit [my wiki](https://github.com/CSCMU-65s/cs-wiki101/tree/main/instructions) and follow the installation guides tailored to your course. If you're unsure about which course to follow, please reach out to your instructor or teaching assistant for guidance.

# [Explore the Wiki &#10148;](https://github.com/CSCMU-65s/cs-wiki101/tree/main/instructions)


## Workshop Title: Git and GitHub Essentials for Beginners

### Session 1: Introduction to Version Control and Git Basics (40 minutes)

1. **Introduction (5 minutes)**
   - Welcome participants
   - Brief overview of the agenda

2. **Version Control Basics (15 minutes)**
   - Explanation of version control concepts
   - Importance of version control in software development

3. **Introduction to Git (20 minutes)**
   - What is Git?
   - Basic Git commands:
     - `git init`
     - `git add`
     - `git commit`
     - `git status`
     - `git log`

**Break (10 minutes)**

*Issues and Discussions* about installation and setup of Git and GitHub Desktop (*optional for personal computers*)

### Session 2: GitHub Basics, Authentication, and Repository Management (50 minutes)

4. **Introduction to GitHub (15 minutes)**
   - What is GitHub? (*and what is it not?*) (5 minutes)
   - Creating a GitHub account (*if not already done*) (5 minutes)
   - Overview of GitHub features (5 minutes)
     - Repositories
     - Issues
     - Discussions
     - Pull requests
     - etc.

   > *Git and GitHub are not the same thing.*

5. **Authentication with Personal Access Tokens (PAT) and SSH (15 minutes)**
   - Creating a Personal Access Token (PAT) [(*more here*)](./docs/w01_lab_2_github_authentication.pptx)
     - Why PAT? and why not password?
     - How to create PAT?
     - How to use PAT? **(demo)** use as password
   - Setting up SSH keys for secure authentication
     - Why SSH? and why not PAT?
     - How to create SSH keys?
     - How to use SSH keys?

6. **Creating and Managing Repositories (20 minutes)**
   - Types of repositories
      - Public
      - Private
   - Creating a new repository
      1. Creating a repository from scratch (5 minutes)

        | Step | Command |
        | --- | --- |
        | 1. Create a new repository | `git init` |
        | 2. Add files to the repository | `git add .` |
        | 3. Commit the changes | `git commit -m "first commit"` |
        | 4. Add the remote repository | `git remote add origin <remote repository URL>` |
        | 5. Push the changes to the remote repository | `git push -u origin main` |

      2. Create some files (How to add files to Git?)

        | Step | Command |
        | --- | --- |
        | 1. Create a new file | `touch Hello.py` |
        | 2. Add files to the repository | `git add .` |
        | 3. Commit the changes | `git commit -m "first commit"` |
        | 4. push the changes to the remote repository | `git push |

      3. Special files and folders

        | File/Folder | Description |
        | --- | --- |
        | `.gitignore` | List of files and folders to ignore |
        | `.git` | Folder containing all Git-related information |
        | `README.md` | Description of the repository |
        | `.github` | Folder containing GitHub-related information |

   - Cloning an existing repository (5 minutes)
      - Clone this repository to your computer
      - Fork [this repository](https://github.com/AppleBoiy/cmu-gh-bootcamp-sample) to your account
      - Difference between cloning and forking
      - Contribute to the forked repository
        1. Create a `HelloWorld.java` file
            - [ ] `.class` file will be ignored
            - [ ] Push to your forked repository

**Break (10 minutes)**

*Questions and Discussions* about Git and GitHub (*for personal computers*) and take care of any technical issues and help participants with any problems they may have encountered.

### Session 3: Branching, Merging, and Collaborating on GitHub (50 minutes)

(*Nte: This session is not the main focus of the workshop. It is included to provide a brief overview of the concepts and to encourage participants to explore these concepts further on their own.*)

7. **Branching and Merging (15 minutes)**
   - Creating branches
   - Switching branches
   - Merging branches

8. **Collaborating on GitHub (15 minutes)**
   - Mention of issues and discussions
   - Collaborating with others on a project

9. **GitHub Workflow Without Pull Requests (10 minutes)**
   - Directly pushing changes to branches
   - Collaborative work without formal pull requests

### Q&A and Closing (10 minutes)

10. **Questions and Answers (10 minutes)**
    - Open the floor for participant questions
    - Provide additional resources for further learning

11. **Closing Remarks (5 minutes)**
    - Thank participants
    - Share contact information for follow-up questions
    - Encourage further exploration on GitHub

---

Need assistance? Please contact [AppleBoiy](mailto:contact.chaipat@gmail.com) or review the [GitHub status page](https://www.githubstatus.com).

&copy; 2023 AppleBoiy &bull; [Code of Conduct](<https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_c>
