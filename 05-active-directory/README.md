# 🏢 Active Directory Fundamentals & Administration

## Overview

This repository documents my learning journey into Microsoft Active Directory (AD), focusing on how Windows domain environments are structured, managed, and secured.

Through theoretical learning and hands-on lab exercises, I am exploring how Active Directory manages users, computers, groups, permissions, authentication, and access to network resources within an organization.

My goal is to develop a better understanding of enterprise Windows environments and build practical IT administration skills while exploring the security concepts behind Active Directory.

## 🧠 1. Understanding Active Directory

I have been learning the fundamental concepts that make up an Active Directory environment, including:

- **Domains:** Understanding how domains provide a centralized way to manage users, computers, authentication, and resources within an organization.

- **Domain Controllers (DCs):** Learning the role of domain controllers in managing authentication, enforcing directory policies, and maintaining Active Directory data.

- **Active Directory Objects:** Understanding how users, computers, groups, and other resources are represented and managed as objects within the directory.

- **Organizational Units (OUs):** Learning how OUs help organize directory objects into logical structures, making administration and Group Policy management easier.

- **Access Control Lists (ACLs) & Access Control Entries (ACEs):** Exploring how permissions are assigned to directory objects and how access rights determine what users and groups can do.

## 🌳 2. Active Directory Structure

I have also been exploring how multiple domains can be organized and connected within larger Windows environments.

- **Domain Trees:** Understanding how multiple domains can share a contiguous DNS namespace and form a hierarchical structure.

- **Forests:** Learning how forests provide a larger Active Directory structure containing one or more domain trees that share a common schema and configuration.

- **Trust Relationships:** Understanding how trust relationships allow authentication and access between different domains or forests, depending on the trust configuration and permissions.

## 🔐 3. Authentication & Kerberos

One of the areas I find particularly interesting is how Active Directory handles authentication.

I have been learning about **Kerberos**, the primary authentication protocol used in Active Directory domain environments.

Topics explored include:

- The purpose of Kerberos authentication.
- The role of the Key Distribution Center (KDC).
- Authentication through Ticket Granting Tickets (TGTs).
- Service Tickets (STs) and their purpose.
- How Kerberos helps users access network resources without repeatedly submitting their passwords.

## 👤 4. User, Group & Organizational Management

I am exploring how administrators manage users and groups within an Active Directory environment.

Practical learning areas include:

- Creating and managing domain user accounts.
- Adding users to Organizational Units.
- Creating and managing security groups.
- Adding users to appropriate groups.
- Understanding group membership and assigned permissions.
- Exploring user roles and access based on group membership.
- Managing account properties and enabling or disabling accounts.

These exercises help me understand how organizations structure user accounts and control access to internal resources.

## 💻 5. Managing Active Directory Using PowerShell

I have been learning how PowerShell can be used to interact with and manage Active Directory.

My practical exercises focus on understanding commonly used Active Directory cmdlets and how they simplify routine administrative tasks.

Areas explored include:

- Importing and using the Active Directory PowerShell module.
- Retrieving information about domain users and groups.
- Creating new Active Directory users.
- Modifying user account properties.
- Creating and managing security groups.
- Adding users to groups.
- Searching for directory objects.
- Enabling and disabling user accounts.
- Understanding how PowerShell can make repetitive administrative tasks easier.

**Example commands explored:**

```powershell
# Import the Active Directory module
Import-Module ActiveDirectory

# Retrieve domain information
Get-ADDomain

# List domain users
Get-ADUser -Filter *

# Find a specific user
Get-ADUser -Identity username

# List Active Directory groups
Get-ADGroup -Filter *

# Retrieve information about a domain controller
Get-ADDomainController -Filter *
```

These commands form part of my ongoing practice with PowerShell and Active Directory administration.

## 🎯 6. Learning Objectives

Through this project, I aim to:

- Understand how Active Directory supports centralized administration.
- Become familiar with Windows domain environments.
- Understand how authentication and authorization work.
- Learn how users, groups, and permissions are managed.
- Explore the relationship between Active Directory administration and cybersecurity.
- Become more comfortable using PowerShell for everyday administrative tasks.
- Be comfortable enough to be able to do Active Directory Penetration testing (you can't break what you don't understand)

## 📸 7. Lab Evidence & Screenshots

Screenshots and supporting evidence from my practical exercises will be added to the `screenshots/` directory as I progress through the lab.

The evidence will document different aspects of Active Directory configuration, user and group management, authentication concepts, and PowerShell administration.

---

## 📚 Learning Approach

I believe understanding technology requires more than memorizing commands. I want to understand what happens behind the scenes, why certain configurations exist, and how they affect the security of an environment.

This repository is part of my continuous learning journey into IT infrastructure, Windows administration, and cybersecurity.

**Areas of Interest:** Active Directory | Windows Administration | PowerShell | Authentication | Access Control | Cybersecurity

*Learning, experimenting, documenting, and improving one step at a time.*
