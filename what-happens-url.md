# What Happens When You Type a URL?

## 1. Intro

1. DNS
2. TCP 3-way handshake
3. HTTP upgrade
4. HTTP request, response
5. Browser rendering

## 2. DNS

**What**

Mapping from domain name to IP address

**Why**

Easy for human to remember

**How**

<div align="center"> <img src="./pics/how-dns.png" width="60%"/> </div><br>

## 3. TCP 3-way Handshake

**What**

A process used to establish a **reliable** connection between 2 devices before transmission begins

**Why**

1. Two parties keep track of what they sent by using *seq*
2. *TCP* is a bi-directional communication, both parties can "speak"

**How**

```
Alice ---> Bob    SYNchronize with my Initial Sequence Number of X
Alice <--- Bob    I received your syn, I ACKnowledge that I am ready for [X+1]
Alice <--- Bob    SYNchronize with my Initial Sequence Number of Y
Alice ---> Bob    I received your syn, I ACKnowledge that I am ready for [Y+1]
```

## 4. HTTP Upgrade

// todo

## References

- [Why do we need a 3-way handshake? Why not just 2-way?](https://networkengineering.stackexchange.com/questions/24068/why-do-we-need-a-3-way-handshake-why-not-just-2-way)
- [Public Key Cryptography - Computerphile](https://www.youtube.com/watch?v=GSIDS_lvRv4)
