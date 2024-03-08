# CCO (Collective Communication Optimizations) Side Meeting in IETF 119
Colletive Communication Offloading and In-Network Computing in AI/HPC network

**Time: 15:00-16:00 Monday (March 18, 2024), Brisbane (AEST)**
  - UTC 05:00 - 06:00
  - CET (UTC+1) 06:00 - 07:00
  - CST (UTC+8) 13:00 - 14:00
  - PST (UTC-8) 21:00 - 22:00 (Sunday)
  - EST (UTC-5) 00:00 - 01:00

**Location: P6-7**

**Remote Access Link:  https://ietf.webex.com/meet/ietfsidemeeting2**

Information also available on side meeting wiki: https://wiki.ietf.org/meeting/119/sidemeetings#meeting-monday

Organizers: Kehan Yao (yaokehan@chinamobile.com), Yizhou Li (liyizhou@huawei.com) 

## Agenda
1.	Admin 
2.	Use cases, problem space and requirements: kehan Yao (China Mobile) 
3.	In-Network Data Consistency: Yang Tian (Huawei)
4.	RoCEv2-based Collective Communication Offloading: Feng Liu (H3C) 
5.	The Requirements of a Unified Transport Protocol for INC in Support of RPC-based Applications: Haoyu Song (Futurewei) 


## Introduction
Collective communication plays a key role in high performance computing and the modern distributed AI training workloads such as recommender systems and natural language processing.
It involves a group or groups of processes participating in collective operations like AllReduce or AllGather. The communication model can be one-to-all, all-to-one or all-to-all and is usually realized by a sequence of unicast messages. Communication and computation is coordinated among a group of processes. 

In-network computing, in recent years, has been being discussed to improve the overall performance in terms of the bandwidth consumed and/or latency when collective communications are used. Designing the network assissted collective communication primitives to execute one or some key steps in the process and/or to provide the more efficient group communication model are drawing some special attentions as the ways for collective communication optimizations (CCO). They also impose some challenges and requirements for both the network transport and forwarding, and co-design of protocols and distributed learning frameworks.

It is a continuation of CCO side meeting from IETF 118. The primary goals are to refresh and update the requirements, analysis and new technologies to optimize collective communications and to explore some usage expansion like data consistency to leverage the in-network computing capabilities. Your participation is welcome. We hope to foster the open discussions to stimulate the innovative engineering work in this area.
