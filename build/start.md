---
layout: default
title: Build
description: Make a change and see what happens.
nav_order: 4
sidebar: true
has_children: true
---


## The best way to learn is to build
    
 - step 1
 
        git clone https://github.com/gno
        cd gno
        make
        
 - step 2
    
        ./build/gnokey add test1 --recover 
   
   provide mnemonic to import test1 wallet 
   
         source bonus chronic canvas draft south burst lottery vacant surface solve popular case indicate oppose farm nothing bullet exhibit title speed wink action roast

 - step 3: start gnoland node and website in two terminal windows. 

        ./build/gnoland
        ./build/website
        
 - step 4: explore your local node and the website
 
      [local node - http://localhost:26657 ](http://localhost:26657)
  
      [website - http://localhost:8888 ](http://localhost:8888)
      
 - step 5: optional, setup your local faucet
 
    By default, the faucet sends out 1,000,000ugnot (1gnot) per request. --send flag overwrites it. 
    
       ./build/gnofaucet serve test1 --chain-id dev --send 5000000000ugnot
    
   
    
## Let's create tutorials 
