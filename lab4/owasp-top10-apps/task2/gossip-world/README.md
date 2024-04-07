# Gossip World

<p align="center">
    <img src="images/banner.png"/>
</p>

Gossip World is a simple Flask app that contains an example of multiple Injection (XSS) vulnerabilities and its main goal is to describe how a malicious user could exploit them on this purposefully vulnerable app.

## Index

- [Definition](#what-is-cross-site-scripting)
- [Setup](#setup)

## What is Cross-Site Scripting?

XSS flaws occur whenever an application includes untrusted data in a new web page without proper validation or escaping, or updates an existing web page with user-supplied data using a browser API that can create HTML or JavaScript. XSS allows attackers to execute scripts in the victim’s browser which can hijack user sessions, deface web sites, or redirect the user to malicious sites.

The main goal of this app is to discuss how **Cross-Site Scripting** vulnerabilities can be exploited and to encourage developers to send Pull Requests on how they would mitigate these flaws.

## Setup

To start this intentionally **insecure application**, you will need [Docker][docker install] and [Docker Compose][docker compose install]. You must type the following commands to start:

```sh
cd owasp-top10-apps/task2/gossip-world
```

```sh
make install
```

Then simply visit [localhost:10007][app] ! 😆

## Get to know the app 💄

To properly understand how this application works, you can follow these simple steps:

- Create a new user
- Try leaving a comment on a gossip
- Try creating your gossip!
