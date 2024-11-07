# SurprisePartyPlanner 🎉

Welcome to the **SurprisePartyPlanner** repository! This project is part of the **CodeSignal** [Git Version Control for Beginners course path](https://codesignal.com/tba) — a hands-on series of courses designed to teach Git and GitHub collaboration workflows. 

In this repository, we follow Alice and Bob as they prepare for a surprise party, demonstrating key Git concepts we've covered throughout the course. This practical example helps illustrate branching, merging, and version control, giving you a real-world look at collaborative project management with Git.

## Table of Contents
- Overview
- Branch Structure
- Getting Started
- Exploring the Repository

---

## Overview

The purpose of this repository is to illustrate collaborative workflows in Git and GitHub, as discussed in our CodeSignal course. Using this example, you'll see how **Alice** and **Bob** work independently on different aspects of a party plan, each on their own branch, before combining their contributions into the main project. 

This repository serves as a learning tool for understanding:
- Branching strategies
- Merging processes
- Managing versions

## Branch Structure

The repository is organized into three main branches, each representing different stages of the project:

- **Main Branch (`main`)**: Contains the finalized party plan, where both Alice’s and Bob’s completed branches are merged.
  
- **Alice’s Branch (`alice_part`)**: Alice is responsible for creating the guest list and planning decorations. Her branch includes:
    - Task 1: Create guest list
    - Task 2: Plan decorations
    - Task 3: Merge the branch with both files into `main`
  
- **Bob’s Branch (`bobs_part`)**: Bob focuses on preparing the menu and playlist. His branch includes:
    - Task 1: Plan menu
    - Task 2: Create music playlist
    - Task 3: Update menu to accommodate vegetarian guests
    - Task 4: Merge the branch with all updates into `main`

## Getting Started

To explore the repository, clone it and navigate through each branch.

### Cloning the Repository

Clone the repository to your local machine using:
```bash
git clone https://github.com/CodeSignal/SupriseParty.git
```

Once cloned, you can switch between branches to see the specific contributions made by Alice and Bob.

### Checking Out Branches

To view Alice’s or Bob’s part of the project, switch to their respective branches:

```bash
git checkout alice_part
```
or
```bash
git checkout bobs_part
```

This will allow you to explore each collaborator’s work and see how their tasks come together for the final plan.

## Exploring the Repository

This repository includes practical examples of Git operations covered in the CodeSignal course, such as:
- **Branching**: Each contributor works independently on their own branch.
- **Merging**: Alice’s and Bob’s branches are merged into the `main` branch to form the complete plan.

Additionally, you can **explore the commit history** to gain insights into the step-by-step development of each task. Viewing the commits will show how individual tasks were handled, providing a clear picture of the contributions made by Alice and Bob over time. Use the following command to view all commits:

```bash
git log
```

Feel free to explore the branches, view the commit history, and examine how contributions from both collaborators are integrated in the `main` branch.

---

Enjoy exploring the repository, and happy party planning! 🎈

---

