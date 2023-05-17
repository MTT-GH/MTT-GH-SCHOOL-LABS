### Lab 1: Create a GH Issue
In this lab you are going to report an existing issue in the content by opening a new issue in the source repo (Upstream). This is the most common way to report an issue. 

GitHub Issues are used not only to report bugs, but also to propose new features, ask questions, etc (you can use labels for categorizing). It is something similar to work items used by Azure DevOps.

When creating a new issue, you should provide:
- A descriptive title linked to the Lab and Issue
- Clear issue description
- Include screenshots or other media (if that helps to understand the issue)
- (Done in [Lab 2](#lab-2-create-a-pull-request-intermediate)) Include a link to the PR that fixes the issue.

#### Exercise

1. Make sure you are in the MS-ESI/MTT-GH-Fundamentals repo. You are going to use the source repository to report an issue found in the lab.
1. Go to the [WebApp-Lab.md](Instructions/WebApp-Lab.md) file.

1. On Exercise 1 > Task 1 you can see there is an issue with the table format. You will be reporting this issue in the source repo (Upstream).

    ![Table issue](media/table-issue.png)

1. Click on the **Issues** tab in the repo (make sure you are in the MS-ESI/MTT-GH-Fundamentals repo). Click on the **New issue** button.

1. Provide a descriptive title for the issue. For example: **Lab 1: E1T1 - Table format is not correct**.
1. Provide a description to the issue. For example:

    ```The table format is not correct. The table is not rendered correctly in the GitHub UI.```
1. Include an image of the issue. You can use the Snagit tool (or others) to capture the image and pointing the problem. You can attach it just by **pasting** into the issue description.

1. Click on the **Submit new issue** button. Your issue should be created and look similar to the following [issue](https://github.com/MS-ESI/MTT-GH-Fundamentals/issues/2)  (some exercises to be done still ):

    ![Reference issue](media/reference-issue.png)

1. You may need to collaborate further using the **comment section** of the issue, which is used fo conversation with other users and content owners (you can tag people using "@").
1. Content Owners may also add labels to the issue to categorize it. For example, adding the **bug** label to the issue.

1. Once reviewed and fixed, the issue will be closed by the Content Owner. You will still work on the issue during next labs. 