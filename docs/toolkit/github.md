---
layout: default
title: GitHub
parent: Toolkit
nav_order: 1
---

# Reach: GitHub
{: .no_toc }

GitHub is a very popular version control platform. One of the fundamental principles of data science is that code and results should be reproducible either by yourself at a future point in time or by others. Version control provides a mechanism to track and record changes to you work online.

We are going to give a brief intorduction of how to use GitHub and Git to perform the most common operations and to join our GitHub organization. For more information, see "[GitHub Docs](https://docs.github.com/en){:target="\_blank"}".

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Dependencies

At the heart of GitHub is an open-source version control system (VCS) called Git. Git is responsible for everything GitHub-related that happens locally on your computer. Tou can download [Git](https://git-scm.com/downloads){:target="\_blank"} based on your OS type.

If you want to work with Git locally, we will highly recommend downloading and installing the [GitHub Desktop](https://desktop.github.com/){:target="\_blank"} client. For more information, see "[Installing and configuring GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop){:target="\_blank"}".

If you want to work in production with all your codes and files, we will highly recommend downloading and installing the [Visual Studio Code](https://code.visualstudio.com/){:target="\_blank"} as your main IDE. For more information, see "[Setting up Visual Studio Code](https://code.visualstudio.com/docs/setup/setup-overview){:target="\_blank"}".

---

## Create an account

After you have installed GitHub Desktop, you can authenticate the application with your account on GitHub. Authenticating allows you to connect remote repositories on GitHub.

Before you can authenticate to GitHub, you will need an account. You can follow the below steps. For more information about creating an account, see "[Signing up for a new GitHub account](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account){:target="\_blank"}".

> - If you want to create a new personal account, make sure you are currently signed out of GitHub.
{: .fs-3 }
> - Go to GitHub's [Pricing](https://github.com/pricing){:target="\_blank"} page.
{: .fs-3 }
> - Choose the <span class="text-purple-100">free</span> subscription.
{: .fs-3 }
> - Follow the prompts to create your personal account.
{: .fs-3 }
>> - Username rules: `firstname+lastname-dentsu`, example: `johndoe-dentsu`.
{: .fs-3 }
>> Note: If your name has been taken, please add number after your last name, example: `johndoe1-dentsu`.
{: .fs-1 .text-purple-100 }
>> - Email rules: You must use your work email to create this account such as `@dentsu.com`, `@carat.com` or `@iprospect.com` example: `john.doe@dentsu.com`.
{: .fs-3 }

Congratulations! You've successfully created your GitHub account.

---

## Set up account

After you sign up your GitHub account, you can now log in to your main GitHub page. You will need to do some extra settings to join our organization.

> - Click your default profile photo in the upper-right conner of you page and then click <span class="text-purple-100">Your Profile</span> from the dropdown list.
{: .fs-3 }
> - Under the <span class="text-purple-100">Overview tab</span>, you will need to upload your beautiful photo by clicking the default avator.
{: .fs-3 }
> - You can also update your profile by clicking <span class="text-purple-100">Edit profile</span> button there. Please add your full name, company and location.
{: .fs-3 }
> - Next thing we need to do is to configure two-factor authentication using a TOTP mobile app. We recommend using cloud-based TOTP apps such as [Microsoft Authenticator](https://www.microsoft.com/en-us/security/mobile-authenticator-app){:target="\_blank"}. 
{: .fs-3 }
> - Download that app in your phone and click your profile photo in upper-right conner again, then click <span class="text-purple-100">Settings</span>. In the  <span class="text-purple-100">Access</span> section of the sidebar, click  <span class="text-purple-100">Password and authentication</span>. Under  <span class="text-purple-100">Two-factor authentication</span>, click  <span class="text-purple-100">Enable two-factor authentication</span>. Under  <span class="text-purple-100">Two-factor authentication</span>, select  <span class="text-purple-100">Set up using an app</span> and click  <span class="text-purple-100">Continue</span>. Under <span class="text-purple-100">Authentication verification</span>, scan the QR code with your mobile device's app. After scanning, the app displays a six-digit code that you can enter on GitHub. The TOTP mobile application saves your account on GitHub.com and generates a new authentication code every few seconds. On GitHub, type the code into the field under <span class="text-purple-100">Enter the six-digit code from the application</span>. Your recover codes should automatically display. The last step is to save your recovery codes to your local which can help you get back into your account if you lose access.
{: .fs-3 }
> - Once you finish all those steps, please inform your team lead to inviting you to our organization.
{: .fs-3 }

Congratulations! You've successfully set up your GitHub account.

---

## Create a repository

You can store a variety of projects in GitHub repositories, including open source projects and private projects. You can use repositories to collaborate with others and track your work. 

We recommend creating your repository online first and then clone it to your local to edit and commit.

> - In the main GitHub dashboard or your upper-right corner of any page, you will find a button to generate <span class="text-purple-100">New repository</span>.
{: .fs-3 }
> - Click that button, you now will be able to type your repository name under the <span class="text-purple-100">Owner</span>. If you have joined ou organization, you will be able to select <span class="text-purple-100">dentsu Media US Data Science</span> as your owner.
{: .fs-3 }
>>  - Repository name rules: `client-project`, example: `macys-forecasting`.
{: .fs-3 }
>> Note: If you don't know your category, please consult your team lead. We do have none client project such as `core-` represents our core R&D solutions and `hp-` represents our hyper relavence solutions.
{: .fs-1 .text-purple-100 }
>> - Visibility rules: Always private and organization owners can manage individual access to the organization's repositories.
{: .fs-3 }
> - Select <span class="text-purple-100">Initialize the repository with a README</span>, then click <span class="text-purple-100">Create repository</span>.
{: .fs-3 }

Congratulations! You've successfully created your first repository, and initialized it with a *README* file.

---

## Use GitHub Desktop

After you have installed GitHub Desktop, you can authenticate the application with your account on GitHub. Authenticating allows you to connect to remote repositories on GitHub.

> - In the GitHub Desktop drop-down menu, click <span class="text-purple-100">Preferences</span>. In the preferences window, click <span class="text-purple-100">Accounts</span> and follow the steps to sign in.
{: .fs-3 }
> - From the preferences window, you can choose a default text editor (we recommend <span class="text-purple-100">Visual Studio Code</span>) or shell, edit your Git configuration, change the appearance of GitHub Desktop, customize system dialog boxes, and set privary preferences.
{: .fs-3 }

Now you are ready to start using GitHub Desktop.

> - You can create a new repository by selecting the <span class="text-purple-100">File</span>) menu and clicking <span class="text-purple-100">New Repository</span>. For more information, see "[Creating your first repository using GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/creating-your-first-repository-using-github-desktop){:target="\_blank"}".
{: .fs-3 }
> - You can add a repository from your local computer by selecting the <span class="text-purple-100">File</span> menu and clicking <span class="text-purple-100">Add Local Repository</span>. For more information, see "[Adding a repository from your local computer to GitHub Desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/adding-a-repository-from-your-local-computer-to-github-desktop){:target="\_blank"}".
{: .fs-3 }
> - You can clone a repository from GitHub by selecting the <span class="text-purple-100">File</span> menu and clicking <span class="text-purple-100">Clone Repository</span>. For more information, see "[Cloning and Forking Repositories from GitHub Desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop){:target="\_blank"}".
{: .fs-3 }

Now you have learn some general use cases about GitHub and Github Desktop. Let's use a step-by-step example to learn how it fits to you day-to-day work.

> - You can create a folder named "<span class="text-purple-100">GitHub</span>" in your local drive.
{: .fs-3 }
> - Go to the GitHub repository page, click the repository you just created and click the <span class="text-purple-100">Code</span> dropdown button.
{: .fs-3 }
> - Copy the url from that clone window and open you GitHub Desktop, then click <span class="text-purple-100">File</span> and choose <span class="text-purple-100">Clone Repository</span>.
{: .fs-3 }
> - If you already sign in with your GitHub account, you should see that repository name in your repository selections. For example: `johndoe-dentsu/hello-world`.
{: .fs-3 }
> - Click that repository and make sure your <span class="text-purple-100">Local Path</span> is under the folder you just created. For example: `/Users/Jdoe/GitHub/hello-world`. Click <span class="text-purple-100">Clone</span>.
{: .fs-3 }
> - You can open your <span class="text-purple-100">Visual Studio Code</span> and open a new folder from it, choose <span class="text-purple-100">GitHub</span> folder and you will find the <span class="text-purple-100">hello-world</span> folder there.
{: .fs-3 }
> - You can find a <span class="text-purple-100">README.md</span> file there which is genreated when we did the reposority creation from GitHub. Let's make some edits on it. Write another line `## This is my test project` below the `# hello-world` and save the file.
{: .fs-3 }
> - Now if you go back to <span class="text-purple-100">GitHub Desktop</span>, you will see a change happened to your file. You can make a commit to keep track of your changes and push your commits to GitHub.
{: .fs-3 }
> - The default commit should already be there called <span class="text-purple-100">"Update README.md"</span> and you can click the <span class="text-purple-100">Commit to main</span> button to commit this change to your current main branch.
{: .fs-3 }
> - After the commit, you will now see a <span class="text-purple-100">Push origin</span> button. Click that and go back to your <span class="text-purple-100">GitHub repository page</span> to check, your change should have been updated there.
{: .fs-3 }