# Kali-User-Management-Project
Learn how to create, update, and delete users and groups for Linux distribution! 

---

## 🚀 Features
- **Step-by-Step Instructions**: Learn how to manage users and groups in Kali Linux.
- **Hands-On Exercise**: Replicate an organizational chart to test your skills.
- **Ready-to-Use Commands**: Copy and paste commands to get started quickly.

---

## 📋 Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Steps By Step Implementation](#StepsByStepImplementation)
4. [Conclusion](#conclusion)
5. [What's Next?](#whatsNext)
6. [Challenge (Optional)](#challenge)

---

## 🎯 Introduction
Managing users and groups is a fundamental skill for anyone working with Linux systems. Whether you're a system administrator or a Linux enthusiast, understanding how to create, update, and delete users and groups manually is essential. In this guide, we’ll walk you through the process step by step.

In Linux, every action is tied to a user or group. Proper user and group management ensures security, organization, and efficient system administration. This guide will teach you how to:
- **Create users and groups**.
- **Assign users to groups**.
- **Update user details**.
- **Delete users and groups**.
  
By the end of this guide, you’ll be able to manage users and groups confidently in Kali Linux.

---

## 🛠️ Prerequisites
- Kali Linux installed (or any Debian-based distribution).
- Root or Sudo access.
- Basic understanding of Linux commands and Linux terminal.

---

## 🚦 Steps By Step Implementation:
Breaking the project into clear, actionable steps:
In this project, we will leverage the following organizational chart as a reference to guide our User and Group management. This chart outlines the structure of users, groups, and their respective roles, ensuring a clear and systematic approach to user management in Kali Linux. 

<p align="center">
  <img src="images/orgChart.png" alt="Project Banner" width="500">
  <br>
  <em>Img1: Organization Chart</em>
</p>

### Step 1. Create Users
To be able to create a new user, we will need to use the "**adduser**" command. This command is an interactive way that will prompt you for additional details like the user’s full name and password. Then follow the prompts to set the remaining details. Enter "**Y**" when you are ready to add in the user or else enter "**N**" to adjust the information:

<p align="center">
  <img src="images/Picture2.png" alt="useradd" width="500">
  <br>
  <em>Img2: User Details</em>
</p>

Example:

```markdown
sudo adduser alice

### Step 2. Create Groups

