---
layout: default
title: package
parent: Learn
nav_order: 1
---


# Gno Package


Gno pacakge is similar to go pacakge concept. It provides a groupe of reusable library code. 

Here is the difference thought.

- the package defiend and deployed under gno.lang/p/  is call gno package, which is a pacakge of reusable code

- the package defiend and deployed under gno.lang/r/ is called realm package, which is a smart contract instance with state variables.

Gno package path: 

    gno.lang/p/

Gno package: package path + pacakge name

    gno.lang/p/your_pacakge_name

You can use multiple sub directory path to orgnize your Gno pacakge. 

     gno.lang/p/package_name/sub_package_name/....../multiple_levels_deep is allowed


## Related

[realm](learn/realm.html)
