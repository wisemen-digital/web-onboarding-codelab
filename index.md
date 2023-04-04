author: Danne Dullers
summary: Learn Android
id: index
tags: Android, Kotlin
categories:
environments: Android
status: Draft
feedback link: https://github.com/SolaceDev/solace-dev-codelabs/blob/master/markdown/android-test

# Wiselab Onboarding 1

## What you'll learn: Overview

Duration: 1:00:00

What is up bro?

Hello fellow developer! Welcome to **Wisemen**! We want to make sure you are soon up to speed with the core of Android development and our way of working.
Therefore we created this awesome series of **CodeLabs** for you. These are a constant work in progress, so please let us know if you have any feedback or suggestions!
This is what you will learn in this CodeLab:

### 1. Creating a new project with our Android Core Library
We have our own Android Core Library that we use in all our projects. This library contains a lot of useful classes and functions that we use in all our projects.

### 2. Folder structure
We have a specific folder structure that we use in all our projects. This is to make sure that we can easily find all the files we need.

### 3. AGILE
1. Work with **Jira**
2. Using **Bitbucket** for version control
3. Branching strategy
4. **Pull Requests**

### 4. Creating a first screen
* How to use **Figma**
* Write some code!
* Write some more code!
* Create your first **PR** (pull request)


### Let's get started!

![Soly Image Caption](img/hello.gif)

## What you need: Prerequisites

Duration: 0:55:00

Before we start, make sure you have everything you need to complete this **WiseLab**. You will need:

### Android Studio
Download the IDE here if you don't have it already!
[Android Studio](https://developer.android.com/studio)

### Figma
Our designers work with **Figma**. You can download it here:
* [Figma](https://www.figma.com/downloads/)

To access the designs you need to log in with your Wisemen account:
* [Figma wireframes](https://www.figma.com/file/hebgv4Qx8VanMAQkO1NFpa/Onboarding-to-do?node-id=407-4095&t=2qdyy89lKwN7dFw3-0)

### BitBucket repository
*ToDo: Add link to BitBucket repository*

### Jira access
*ToDo: Add link to Jira*

## Create the project

### Add Android core dependencies

```gradle
dependencies {
    // Core
    implementation "com.github.appwise-labs.AndroidCore:core:$android_core_version"
    implementation "com.github.appwise-labs.AndroidCore:room:$android_core_version"
    implementation "com.github.appwise-labs.AndroidCore:networking:$android_core_version"
    ...
}
```
## Custom Step 2
## Custom Step 3

## Takeaways

Duration: 0:07:00

✅ < Fill IN TAKEAWAY 1>   
✅ < Fill IN TAKEAWAY 2>   
✅ < Fill IN TAKEAWAY 3>   

![Soly Image Caption](img/soly.gif)

Thanks for participating in this codelab! Let us know what you thought in the [Solace Community Forum](https://solace.community/)! If you found any issues along the way we'd appreciate it if you'd raise them by clicking the Report a mistake button at the bottom left of this codelab.
