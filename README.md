# AddJenkinsAgentWithScript

## Why
- Jenkins relieved our daily routine workload a lot
- Add agents to master node is boring
- We are developing apps for mobile & console & server, which makes we have to support different kinds of agent
- GieOps is a trend these years
- Java runtime pre-installation for different platforms is error prone, at least for me
- Master may have public ip, while agent inside office may not. So agent initiated connection is a preferred way.

## How
- with native scripts (as less requirements as possible)
- support agents types we encountered.
- Jenkins Api could do a lot
- What we need to add an agent
  - an installed master paired with an account which have satisfied authority
  - an agent of any type listed bellow, paired with an account with sufficient permission.


## What
- Win10
  [] power script
  
- Mac
  [] bash
  
- Docker
  [] bash (baseed with official image)