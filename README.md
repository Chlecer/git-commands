# What is Git? - A Simple Explanation

Imagine you are drawing pictures on paper. Git is like a magic wand that helps you save and keep track of all the changes you make to your drawings.

When you start drawing, you can use Git's magic wand to say, "Save my drawing, please!" Git makes a special copy of your drawing and stores it in a secret place called the "repository."

The coolest part is that every time you make a change to the drawing, Git remembers exactly what you changed! You can say, "Magic wand, show me what I changed!" and Git will note down the changes for you.

And here's the magical trick: if you don't like a change you made, you can ask Git to go back in time! It can erase a change you no longer want, as if it never happened!

Plus, if you want to work with your friends, Git can help you bring everyone's drawings together by combining the changes each one made.

With Git, you never lose your work, and you can draw with your friends in a magical and organized way!

In summary, Git is like a magic wand that helps you save, track, and even undo changes to your drawings (or code) in an incredible way!

# Git - A Version Control System

## Technical Explanation:

Git is a distributed version control system that helps developers manage and track changes in their software projects. It enables multiple developers to collaborate on the same codebase simultaneously, keeping track of all modifications, additions, and deletions made to the project's files over time.

Unlike traditional version control systems, Git is distributed, meaning each developer has their own complete copy of the entire project's history. This decentralization allows developers to work offline, commit changes locally, and later synchronize with the central repository or other team members.

Git uses a directed acyclic graph (DAG) data structure to represent the project's history. Commits in Git point to their parent commits, forming a chain that records the chronological sequence of changes. This graph-based model facilitates branching and merging, enabling the creation of multiple independent lines of development that can be merged back into the main codebase.

## Motivation:

The motivation behind creating Git was to address limitations in existing version control systems, especially in terms of performance, distributed collaboration, and data integrity. Linus Torvalds, the creator of Linux, developed Git in 2005 to manage the vast and decentralized development of the Linux kernel.

Before Git, centralized version control systems like Subversion (SVN) were common. However, they faced challenges when it came to scalability, network dependency, and branching. Linus wanted a version control system that could handle the massive codebase of Linux, allow developers to work offline, and provide robust branching and merging capabilities.

## Creator and Development:

Git was created by Linus Torvalds, the renowned software engineer best known for creating the Linux operating system. Linus initially developed Git for managing the Linux kernel's source code, which involves contributions from thousands of developers worldwide.

The development of Git is open-source, meaning its source code is freely available for anyone to view, modify, and contribute to. Over the years, a large community of developers has contributed to Git's ongoing improvement and widespread adoption.

## Key Features:

- Distributed version control: Each developer has their own complete copy of the repository.
- Fast and efficient: Git is designed to be lightning-fast, making it ideal for large projects.
- Branching and merging: Git's powerful branching model enables easy creation and management of branches, allowing developers to work on features in isolation and later merge them into the main codebase.
- Data integrity: Git uses cryptographic hash functions to ensure data integrity, making it difficult to alter or lose historical project data.
- Offline work: Developers can commit changes locally, even without an internet connection, and later synchronize with the central repository.
- Lightweight and minimalistic: Git's core design philosophy emphasizes simplicity and performance.

In summary, Git is a versatile and powerful version control system created by Linus Torvalds to address the specific needs of the Linux kernel development. Its distributed nature, speed, and robust branching capabilities have made it the de facto standard for version control in the software development community. Its open-source nature allows developers worldwide to contribute to its continuous improvement and adapt it for various projects and workflows.


# git-commands
Check the current origin configuration
> git remote show origin

Update the new origin url
> git remote set-url origin <url-to-uptade>
