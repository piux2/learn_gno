---
layout: default
title: persistence
parent: Learn
nav_order: 3
---

# Persistence

Imagine we write programs on a computer; if the program exit, all the variables and objects we created are gone, same as if we turn the computer off. While executing the program, we must write the code to save the data to the disk as a file or database. 

What about the smart contract on a blockchain? 
Let's pause for a second and understand why we need to understand the persistence concept when we write smart contracts.

A blockchain that supports smart contracts is a distributed virtual machine. However, not many people worked on VM before. We use the language running on VM but do not interact with VM directly. From an application perspective, there is no different writing program executed on a VM and the one without using VM. 

Another analogy of intelligent contracts for application developers is middleware or a service layer library with a distributed database. People can modify the content of the database, but transaction logs for each update are immutable and replicated in the cloud permanently.

We can also think of deploying a smart contract on a blockchain like creating a stored procedure in a SQL database.

The whole purpose of writing a blockchain application is to provide transparency and immutability of transaction logs and business logic. Our application provides TRUST to the final state that most centralized applications and services can not offer.

We trade off the performance and efficiency with the TRUST. 

