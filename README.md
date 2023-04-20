# MTT-GH-Fundamentals

This document contains the instructions for the MTT GH Fundamentals lab. The lab is designed to teach the basics of GitHub and how to use it to contribute to the MOC content used by MTTs.

The scenarios proposed in this lab are based on the real-life scenarios that MTTs face when contributing to the MOC content. It is composed of the following components:

- An **Source Repo (also called "Upstream")** that contains a simulated MOC content (https://github.com/MS-ESI/MTT-GH-Fundamentals). As mentioned on the learning material, the original repo is the source of truth for the content. It is the repo that contains the latest version of the content. The original repo is owned by the Content Owner (Content Devs in a real life scenario). As MTTs or learners, we can report issues and propose changes to the content by opening a PR in the original repo, **but we are not allowed to change it directly**.
- A **Forked repo (also called "Origin")** that contains a copy of the original repo. The forked repo is owned by the contributor (MTT in a real life scenario). The forked repo is used to **make changes to the content and propose them to the original repo**.

![Upstream and Fork](media/upstreamandfork.png)

You could also involve a local clone (copy) of the repo in your local machine. **This is not required for the lab, it will try to teach the easiest way to collaborate with GitHub, only using web interface tooling**. 

You can perfectly collaborate in the MOC content without cloning the repo to your local machine. You can use the GitHub web interface to open issues, create PRs, review PRs, etc. This is the most common way to collaborate in GitHub as MTTs.

## Lab Instructions

### Lab 1: Create a GH Issue
In this lab you are going to report an existing issue in the content by opening a new issue in the original repo. This is the most common way to report an issue. Providing:

- A descriptive title linked to the Lab and Issue
- Clear issue description
- Include screenshots or other media
- (In lab 4) Include a link to the PR that fixes the issue

### Lab 2: Create your first Pull Request (Beginner)
Create a PR directly from the GitHub UI in the original repo. This is the easiest way to create a PR. You can also create a PR from a forked repo, but that is a bit more complicated.

**ISSUE**: Simple typo in the `Lab1.md` file, for example, bold text is not closed.

### Lab 3: Create a Pull Request (Intermediate)
Create a PR from a forked repo. This is the most common way to create a PR. You will need to create a fork of the original repo, make changes to the fork, and then create a PR from the fork to the original repo.

**ISSUE**: Multiple formatting issues in the `Lab1.md` file. Tables with wrong formatting, NOTE with incorrect indentation, etc.
### Lab 3: Create a Pull Request (Advanced)
Create a PR from the forked repo, proposing a image update.

**ISSUE**: The image in the `Lab1.md` file is outdated and contains trainer personal data. The image should be updated to reflect the latest UI changes. Use tools like Snagit to capture the new image and propose the change in the PR.

### Lab 4: Review a Pull Request (Intermediate)
Imagine you are the Content Owner/Courseware Lead. Review and collaborate with the contributor to make sure the PR is ready to merge.

You will include a reference to the GH Issues that are fixed by this PR.

## Lab 5: Review a Pull Request (Advanced)
Imagine you are the Content Owner/Courseware Lead. Review and collaborate with the contributor to make sure the PR is ready to merge.

You will suggest a change to the proposed PR. The contributor will need to accept the change and update the PR.