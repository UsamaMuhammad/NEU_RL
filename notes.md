# Lecture Notes - [Sptember 9, 2024]

## Introduction
- Announcements
    - Piazza: for understanding of RL.
    - read chapter 2
    - Chapter 1 is also worth reading
### Examples
- Chess problem
- gazelle calf learning to walk
- robot learning to pick uo trash
- stock market trading
- traffic light
    - any deployment in real case?
- 7 Days course on RL: [AI Studio Course on Baidu](https://aistudio.baidu.com/course/introduce/1335) (by Lijiao). 


## 1-Step case
- Just make 1 decision
- but don't know outcomes
   
### 1-arm Bandit Problem
- only one thing to do \=> pull lever


### k-armed bandit problem
- k-levers to pull
- at each time step , $t = 1,2,4,...,$, you choose one action form $k$ possible actions
- you receive real value reward
- **GOAL** : maximize expected reward

### How to act if distribution is unknown
- Exploration and Exploitation
    - given $Q_t(a) = arg \max $
    - two possibilities
        -greedy thing
        - do something else
- $\epsilon$-greedy
    - 1. with probability 1-$\epsilon$, take greedy action (exploit)
    - 2. with probability $\epsilon$, take action uniformly at random (explore; might pick greedy action too) 

    - pros and cons


### RL
    - RL is more autonomous learning


- Overview of today's lecture.
- Key concepts:
  - Concept 1
  - Concept 2

## Main Topic
### Subtopic 1
- Important details about subtopic 1.

### Subtopic 2
- Important details about subtopic 2.

## Summary
- Recap of key points.
- Questions or to-dos:
  - [ ] Review concept 1.
  - [ ] Complete related assignment.
