# Programming Languages and Concepts Repository

This repository serves as a learning platform for various programming languages and concepts. Each course has its dedicated folder containing assignments submitted by students.

## Purpose
The primary goal of this repository is to provide a structured environment for students to explore and practice different programming languages and concepts.

## How to Submit an Assignment

### Prerequisites
1. **Install Git:** Download and install Git from [Git's official website](https://git-scm.com/downloads).

### Submission Steps
1. **Fork the Repository:** Click on the "Fork" button at the top right corner of the repository page to create your copy of the repository.
   
2. **Clone the Forked Repository:** Open your terminal or command prompt and use the `git clone` command to clone the forked repository to your local machine.
   
    ```bash
    git clone https://github.com/doudgaya/codingdocx.git
    ```
   
3. **Create a Branch:** Move into the repository directory on your local machine and create a new branch for your assignment.
   
    ```bash
    cd codingdocx
    git checkout -b assigment
    ```
   
4. **Navigate to the Course Directory:** Enter the directory for the specific course (e.g., `Javascript`) where you want to submit the assignment.
   
5. **Create Your Assignment File:** Create a new file with an appropriate name for your assignment within the course directory. Write your code or content in this file.
   
6. **Save and Commit Changes:** Add your changes to the staging area and commit them with a meaningful commit message.
   
    ```bash
    git add .
    git commit -m "Add your assignment message"
    ```
   
7. **Push Your Changes:** Push your committed changes to your forked repository.
   
    ```bash
    git push origin your-branch-name
    ```
   
8. **Create a Pull Request:** Visit your forked repository on GitHub. Click on the "New Pull Request" button, review your changes, and submit the pull request for review.

Remember to replace `your-username` with your GitHub username and `your-branch-name` with a descriptive name for your assignment branch.

### Course Directories
- [HTML/CSS](./HTML_CSS)
- [Javascript](./Javascript)
- [Python](./Python)
