# Git and Gitlab practical assignment

## Part 1: GitHub Tasks

### Subtask 1: Repository Setup

* Create two repositories on GitHub:
![img1](img/Screenshot%20(109).png)

### Subtask 2: Local Development

* Clone both repos on your local machine using HTTPS
![img2](img/Screenshot%20(111).png)

* In the private repo:

1) Create a branch called dev.

2) Add a few files (e.g., index.html , readme.md ) and make at least two commits.

3) Push the dev branch to GitHub.

![img3](img/Screenshot%20(113).png)
![img4](img/Screenshot%20(114).png)

### Subtask 3: Collaboration Workflow

* On GitHub, create a Pull Request (PR) to merge
dev into main .
![img5](img/Screenshot%20(118).png)

* Review and merge the PR.
![img6](img/Screenshot%20(119).png)

* Verify that changes are reflected in the main branch after merging.
![img7](img/Screenshot%20(121).png)

## Part 2: GitLab Tasks

### Subtask 4: GitLab Repository Setup

* Create a private repository on GitLab.
![img8](img/Screenshot%20(122).png)

* Clone it on your local machine using SSH (not HTTPS).
![img9](img/Screenshot%20(123).png)

* Create a simple project structure (e.g., src/app.py , docs/guide.md)
![img10](img/Screenshot%20(130).png)

### Subtask 5: Repository Mirroring

* Create a mirror setup:
1) Set the GitHub private repo as the mirror of your GitLab repo.
![img11](img/Screenshot%20(127).png)

2) Push some changes to GitLab and verify if the changes reflect in GitHub
automatically.
![img12](img/Screenshot%20(128).png)
![img13](img/Screenshot%20(129).png)
![img14](img/Screenshot%20(130).png)

### Subtask 6: Access Control

* Invite your friend to the GitLab private repository:

1) Assign them the Guest role initially, observe the access.
![img15](img/Screenshot%20(131).png)

2) Then change their role to Developer, and let them push one file
![img16](img/Screenshot%20(132).png)
![img17](img/Screenshot%20(133).png)