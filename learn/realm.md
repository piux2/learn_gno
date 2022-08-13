---
layout: default
title: realm
parent: Learn
nav_order: 1
---

# Realm


Realm is a very important concept in gnolang

Realm pacakge is the contract identifier of contract instance on in gno.land network. It is also a reusable gno codes libary pacakged togaher.  

Realm package path: 

    gno.lang/r/

Realm package: package path + contract name

    gno.lang/r/your_contract_name

A realm package is a smart contract with persistent state and usually exposing exteranl methods for other external account or contract to call. 


We can NOT have sub directory path after your contract name in the realm package

     gno.lang/r/your_contract_name/sub_contract_name NOT allowed. 

the contract name is also the folder and go package name that could contain one or multiple contract files.


