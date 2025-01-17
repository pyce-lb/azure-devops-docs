---
title: Share your code with Git using Visual Studio 2013
titleSuffix: Azure Repos
description: Share code in Git using Visual Studio 2013
ms.assetid: d4d85217-1967-412d-b253-b6c6289dc459
ms.technology: devops-code-git 
toc: show
ms.topic: quickstart
ms.date: 08/29/2017
monikerRange: '<= azure-devops'
---


# Share your code with Visual Studio 2013 and Azure Repos Git

[!INCLUDE [temp](../includes/version-tfs-2015-cloud.md)]

> [!div class="op_single_selector"]
> - [Visual Studio 2017](share-your-code-in-git-vs-2017.md)
> - [Visual Studio 2015 Update 2](share-your-code-in-git-vs.md)
> - [Visual Studio 2013](share-your-code-in-git-vs-2013.md)   

 
Whether your software project is large, small, or brand new, 
in most cases you'll be better off if you use version control 
as early as possible. Here, we'll show you how to get started with 
Git, a distributed system. If you want to work in a centralized system, 
you can instead use [TFVC with Azure Repos](../../repos/tfvc/share-your-code-in-tfvc-vs.md).

[!INCLUDE [temp](includes/open-team-project-in-vs.md)]

## Clone your repository

1. Clone the repository onto your dev machine.

   ![Choose Clone Repository](media/share-your-code-in-git-vs/IC684063.png)

2. Store the repository locally.

   ![Choose Clone to store the repository locally](media/share-your-code-in-git-vs/IC682931.png)

## Create a new app
If you don't already have an app in the repo, create one.

1. Create a new project.

   ![New solution from team explorer](media/share-your-code-in-git-vs/team-explorer-git-new-solution.png)

2. Choose a template and add the new code project to version control.

   ![Choose a template](media/create-your-app-vs/IC687148.png)

## Confirm your settings and add the app

1. On the changes page (Keyboard: Ctrl + 0, G), if you haven't already done it,
   confirm your user name and email address.

   ![Configure settings from the changes page](media/share-your-code-in-git-vs/confirm-git-settings-from-changes-page.png)

   ![Confirm the default settings](media/share-your-code-in-git-vs/git-initial-settings-with-default-values.png)

2. Add a comment and commit your app to version control.

   ![Add app to version control on Changes page](media/share-your-code-in-git-vs/team-explorer-git-changes-add-app.png)


## Snapshot (commit) your code

With your code project stored in a local Git repository on your dev machine, 
you can commit as early and as often as you like.

1. As you write your code, your changes are automatically tracked by Visual Studio. 
   You can commit one or more specific changes to your local repository from Solution Explorer
   (Keyboard: Ctrl + Alt + L).

   ![When your changes are ready, select Commit](media/share-your-code-in-git-vs/IC683030.png)

2. On the Changes page, add a comment and then commit your changes.

   ![Add a comment and choose Commit](media/share-your-code-in-git-vs/IC683031.png)

   These changes are now committed.

   ![Your changes are now committed](media/share-your-code-in-git-vs/IC683032.png)

## Pull changes from your team

Pull changes on a regular basis to ensure your code integrates well with the latest code from the team.

1. From the commits page (Keyboard: Ctrl + 0, O), fetch the commits to see any changes that your team has made.

   ![Choose Fetch to see any changes that your team has made](media/share-your-code-in-git-vs/IC682939.png)

2. When you're ready, pull these commits into your local repository.

   ![Choose Pull to get these commits locally](media/share-your-code-in-git-vs/IC682942.png)

3. The changes from your team are now integrated in your local repository.

   ![The changes are now integrated](media/share-your-code-in-git-vs/IC682943.png)

## Push your local commits to the server

When the code you've written on your dev machine is ready, you can push your changes from your local Git repository to the project.

1. From the changes page (Keyboard: Ctrl + 0, G), make sure you've committed your changes.

   ![Committing from the Changes page](media/share-your-code-in-git-vs/IC682975.png)

2. Go to the commits page (Keyboard: Ctrl + 0, C).

   ![Go to the commits page.](media/share-your-code-in-git-vs/IC682976.png)

3. Push your changes.

   ![Push changes](media/share-your-code-in-git-vs/IC682977.png)


## Q&A

<!-- BEGINSECTION class="md-qanda" -->

[!INCLUDE [temp](includes/open-team-project-in-vs-qa.md)]

[!INCLUDE [temp](includes/qa-vs-launch-fail.md)]


#### Q: How can I see what I've changed?

A: To see what you've changed, compare your changes with the last commit.

 ![Choose Compare with Unmodified from the context menu](media/share-your-code-in-git-vs/IC685270.png)

#### Q: How can I get more information about the commits from my team before I pull them?

A: Sometimes you need to see the details about incoming commits from your team. That way you can understand how a change will integrate with your work.

 ![Choose View Commit Details](media/share-your-code-in-git-vs/IC682940.png)

 You can get details on the changes to each file.

 ![Choose Compare with Previous from the context menu](media/share-your-code-in-git-vs/IC685291.png)

#### Q: How do I associate my changes with related work items?

A: From the changes page you can run a query, and then drag a work item into the list of related work items.

 ![Associating a work item on the Changes page](media/share-your-code-in-git-vs/IC685315.png)

#### Q: Can I use Git command-prompt tools?

A: Yes. See [Use Git from the command prompt](command-prompt.md).

#### Q: Where can I learn more?

A: [Use Visual Studio and Team Foundation Server with Git](./index.yml)

<!-- ENDSECTION -->
