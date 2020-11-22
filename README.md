# AddJenkinsAgentWithScript

## Why
- Jenkins relieved our daily routine workload a lot
- Add agents to master node is boring
- We have to support different kinds of agent
- GitOps is a trend these years
- Java runtime pre-installation for different platforms is error prone, at least for me
- Master may have public ip, while agent behind firewall may not. So agent initiated connection is a preferred way.

## How
- With native scripts (as less pre requirements as possible)
- Support agent types we used
- Jenkins Web Api could help a lot

## What
- What we pre-required to add an agent
  - an installed master paired with an account which have satisfied authority
  - an agent of any type listed bellow, paired with an account with sufficient permission.

- For Win10
  - [] power script
  - [] Setps instruction
  
- Mac
  - [] bash
  - [] Setps instruction

- Bare Linux
  - [] bash
  - [] Setps instruction
  
- Linux with Docker
  - [] bash (few lines based on official image)
  - [] Setps instruction