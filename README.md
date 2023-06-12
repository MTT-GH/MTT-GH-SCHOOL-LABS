# MTT-GH-SCHOOL-LABS

This document contains the instructions for the MTT GH School labs. The labs are designed to teach the basics of GitHub and how to use it to contribute to the MOC content used by trainers.

The scenarios proposed in these labs are based on the real-life scenarios that MTTs face when contributing to the MOC content. It is composed of the following components:

- An **Source Repo (also called "Upstream")** that contains a simulated MOC content (https://github.com/MTT-GH/MTT-GH-SCHOOL-LABS). As mentioned on the learning material, the original repo is the source of truth for the content. It is the repo that contains the latest version of the content. The original repo is owned by the Content Owner /Maintainers (Content Devs in a real life scenario). As MTTs or learners, we can report issues and propose changes to the content by opening a PR in the original repo, **but we are not allowed to change it directly** (only maintainers can).
- A **Forked repo (also called "Origin")** that contains a copy of the original repo. The forked repo is owned by the contributor (MTT or learner in a real life scenario). The forked repo is used to **make experiment making changes to the content and propose them to the original repo**.

![Upstream and Fork](media/upstreamandfork.png)

You could also involve a local clone (copy) of the repo in your local machine. **This is not required for the lab. The labs will try to teach the easiest way to collaborate with GitHub, only using web interface tooling (no local repository involved, all done in GitHub)**. 

You can perfectly collaborate in the MOC content without cloning the repo to your local machine. You can use the GitHub web interface to open issues, edit code, create PRs, review PRs, etc. This is the most common way to collaborate in GitHub as MTTs, as we mainly propose "easy" code changes (no need to build/run/test code).


## Pre-requisites
- Make sure you have a **GitHub account**. If you don't have one, you can create one for free at https://github.com/join. Identify yourself as Microsoft MTT in your Profile (TODO guidelines?).
- Review the Learning material in [MTT GitHub School](https://mttghreadiness.azurewebsites.net/).

## Repository Structure
The repository is composed of the following files/folders:
- **README.md**: This file. Contains the instructions for the lab.
- **Instructions** folder: Contains the instructions for the **demo lab files** we will modify .
    - **media** folder: Contains the images used in the instructions.
    - **WebApp-Lab.md**: Instructions for the first demo lab.

## Lab Instructions

- [Lab 1 - Create a GH Issue](Lab1-Create-GH-Issue.md)
- [Lab 2 - Create a Pull Request (Beginner)](Lab2-Create-PR-Beginner.md)
- [Lab 3 - Create a Pull Request (Intermediate)](Lab3-Create-PR-Intermediate.md)
- [Lab 4 - Review a Pull Request (Beginner)](Lab4-Review-PR-Beginner.md)
- [Lab 5 - Review a Pull Request (Intermediate)](Lab5-Review-PR-Intermediate.md)
