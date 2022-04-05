<h1 style="text-align: center; font-weight: 700;">GIT x GITHUB</h1>
Repository for Git and Github functionality records for beginners. Everything registered here can be found in the classes at the link below.

<br>

<p style="border: 1px solid cyan; text-align:center;">Curso: <a href="https://www.udemy.com/share/101s5U3@49TeKcyEDj_VAKO87TlHy6UtPv-n4hgr-rgovUApR-LT9MScTkIOBfUxZQEA2-rw_Q==/">Git e Github para iniciantes.</a></p>

## ⚠️ Some Cares
**If you want to delve a little deeper into the features of git or just get an idea of ​​a visual representation, [click here](learngitbranching.js.org) and visit the Learn Git Branching website.**

<br>

## **Index**

### **Introduction**

- [Version Control](#version-control)
- [Git History](#git-history)
- [What is Github](#what-is-github)

---

### **Settings**

- [Git Install](#git-install)
- [Git Settings](#git-settings)

---

### **Basic Commands**

- [...](#...)

---

<br>

## **Version Control**

Before we delve deeper into **Git and Github** let's reflect a bit. 🤷‍♂️

At some point in your life, you must have had copies and more copies of a project to have several versions of it, probably with minor modifications, that is, kind of a backup of the previous versions in case there was a problem, right? And with that, probably having a lot of files and memory space taken up.

So the idea of ​​**version control** was born, but what is it?

> **Version Control**, this is a system for managing different versions of a document. That is, a system that takes the different modifications of your document and creates versions of it, giving you the possibility to advance or return to them.

One of the systems that works with version control is Git. Before we talk more about it, it's important to know how it works.

> While other systems work with file differences, git works with **states** of files. You could say that git takes pictures/snapshots of the file states, storing them in versions and taking them from version to version. If any file has not changed from one version to another, it creates a symbolic link to the previous version.

<br>

![Git System](https://ik.imagekit.io/helderhsilva/Git/gitsystem_bOgsjqFj1UX.jpeg?updatedAt=1634739461844)

<br>

---

<br>

## **Git History**

Given how git works above, you can see that it is very useful, right, even more so if you work with something that needs these versioning features, for example a frontend or backend developer.

But beauty! So, why was this tool really created? What is your history? Let's go for a little culture hehehe...

> There was a company called BitKeeper that kept all the Linux kernel code, that is, all Linux was versioned within that system. However, there was a breach between the company and the Linux Foundation that caused Bitkeeper to withdraw Linux's right to be exempt, that is, not to pay for the uses of the tool...

Damn huh... Imagine if they weren't upset 😂. Continuing.

> In view of the event, the creator of Linux (Linus Torvalds) informed Bitkeeper that he would not continue using their system. However, at that time this system was the only one that existed, but as Linix needed version control, Linus, in fact, broke the partnership with Bitkeeper and created his own system to be able to use on Linux, thus giving birth to Git, a version control system with all the improvements that Bitkeeper didn't offer and free.

Wow, what a twist. Finally, we can also list the improvements that Git came to offer compared to the BitKeeper system, among them:

- Improved speed: as it hears the change from file-by-file verification to snapshots;
- Simple design;
- Robust support for non-linear development (thousands of parallel branches);
- Fully distributed; and
- Able to efficiently handle large projects like the Linux kernel.

<h3 style="text-align: center; font-weight: 700;">That's it guys. Dale Linus Torvalds. 😎</h3>

<br>

---

<br>

## **What is Github**

Great, but so far we've only talked about Git... So, what is Github?

> **Github** is a shared web service for projects using Git for versioning. That is, a location in the cloud that stores the versioned projects.

Pretty simple right?

So, if someone tells you that they are versioning using Github... Well, she is wrong hehehe. It actually uses Git for versioning and just shares it on Github.

Of course, without Git, Github wouldn't exist. So think of Github as a social network where you can make your code available.

Remember then: **GIT ≠ Github**.

<br>

---

<br>

## **Git Install**

Okay, cool. We know what Git, Github is, how they work and such, but how do you use these tools there?

To start this journey, then, we need to install Git, just follow the steps:

1. Go to the [Git website](https://git-scm.com/downloads) under downloads.

<br>

![Downlaod Git](https://ik.imagekit.io/helderhsilva/Git/downloadgit_TzwecIr0S.png?updatedAt=1634759773252)

<br>

2. Download it to your operating system and just run the downloaded setup. This installation is very intuitive.

NOTE: This Git installation is more for those who use Windows, if you use Linux or macOS, Git is usually already installed.

<br>

---

<br>

## **Git Settings**

Very good. Git installed, but before actually starting to use it for versioning, we should adjust the settings in the tool.

    Git stores your information in three places.
      1. Git config of the system as a whole;
      2. User git config; and
      3. Git config of the repository-specific project.

As we are going to define information that we want to be passed to all user repositories, we are going to use the global config that is the user's. The information that must be verified is:

1. Configuring the username:

```c
git config --global user.name "Seu nome"
```

2. Configuring email:

```c
git config --global user.email "Seu email"
```

3. Configuring the main git editor:

```c
git config --global core.editor code //caso seu editor seja o vsCode
```

NOTE: Your data must be enclosed in quotation marks. git will not return a response if successful, just a clean return.

Show. These settings are enough for us to proceed. But how to check these settings?

For example: What is the username, email or any other registered information? Just follow the commands.

```c
git config user.name //retorna o username
```

```c
git config user.email //retorna o email
```

```c
git config --list //retorna todas as configurações do git
```

<br>

---

## **...**

<br>

## 👨‍💻 Author

<table align="center">
    <tr>
        <td align="center">
            <a href="https://github.com/helderhsilva">
                <img src="https://ik.imagekit.io/helderhsilva/myAvatar_1RkEQbhir.png?ik-sdk-version=javascript-1.4.3&updatedAt=1643634706178" width="150px;" alt="Helder's Image" />
                <br />
                <sub><b>Helder Henrique</b></sub>
            </a>
        </td>    
    </tr>
</table>
<h4 align="center">
   By: <a href="https://www.linkedin.com/in/helderhsilva/" target="_blank"> Helder Henrique </a>
</h4>
