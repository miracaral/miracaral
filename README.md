# Hi, I'm Miraç 👋

Computer Engineering student from Türkiye, currently on an Erasmus+ exchange at the Czech Technical University in Prague. Most of my free time goes into offensive security and software engineering: breaking things on purpose, figuring out why they broke, and writing it down.

## What I work on

- **Offensive security.** Top 3% on TryHackMe, plus a lot of evenings on Hack The Box and Proving Grounds. I'm preparing for the OSCP.
- **Homelab.** Three mini PCs and a switch running a Kubernetes cluster that I harden control by control and then attack from inside, each step with a before/after result. It's where I try out network policies, runtime enforcement, AI agent sandboxing and anything I'd rather not try on a real network.
- **Code.** Mostly Python, C/C++ and Java, with some Go for networking tools.

## Projects

- [homelab-k8s-security](https://github.com/miracaral/homelab-k8s-security): securing my Kubernetes homelab control by control, then attacking it from inside: 7 of 7 container-breakout pods refused, a path from a pod to my home network found and closed, and a security audit before publishing.
- [k8s-agent-sandbox](https://github.com/miracaral/k8s-agent-sandbox): runs an AI coding agent (Gemini CLI) as short-lived Kubernetes pods where a misbehaving agent can do as little as possible, controlled by one CLI with a kill switch and a daily limit. Tested against prompt injection hidden in a repository.
- [openssl-pki-homelab](https://github.com/miracaral/openssl-pki-homelab): a multi-tier PKI built with OpenSSL, plus an mTLS demo that turns away revoked certificates.
- [Foothold](https://github.com/miracaral/foothold): a pentest and CTF companion that fills your target into every command. A vanilla JS front end that works offline, plus an optional Java / Micronaut API on Oracle Database, tested in CI against a real Oracle container and deployed to my Kubernetes homelab.
- [go-network-tools](https://github.com/miracaral/go-network-tools): port scanners, an echo server and a port forwarder, written in Go to understand TCP properly.
- [software-engineering-fundamentals](https://github.com/miracaral/software-engineering-fundamentals): my study projects in C, C++, Java, Scala and Python, organised by topic.

## Writing

- [I built a Kubernetes security lab on three mini PCs and tested every control](https://medium.com/@mmirac.aral/i-built-a-kubernetes-security-lab-on-three-mini-pcs-and-tested-every-control-880165566133)
- [Foothold: a CTF command reference that fills itself in](https://medium.com/@mmirac.aral/foothold-a-ctf-command-reference-that-fills-itself-in-b7caef8d9675)
- [HTTP request smuggling: PortSwigger labs 1–10](https://medium.com/@mmirac.aral/http-request-smuggling-complete-portswigger-web-security-academy-labs-1-10-178841002c28)
- [TryHackMe Buffer Overflow Prep, step by step](https://medium.com/@mmirac.aral/tryhackme-buffer-overflow-prep-step-by-step-stack-based-exploitation-5d7d7d231bfd)
- [Advent of Cyber 2025 side quest: Hoppers Origin](https://medium.com/@mmirac.aral/tryhackme-advent-of-cyber-2025-hoppers-origin-complete-walkthrough-a5f7e39de8f7)

## Right now

- Vaigil: an open-source security layer for AI agents that checks every tool call an agent makes.
- Studying for the OSCP.
- Version 2 of k8s-agent-sandbox: a Claude Code runner, an ops agent you can ask about the cluster, and agents that review each other's work.

## Contact

[Website](https://miracaral.com) · [LinkedIn](https://www.linkedin.com/in/mira%C3%A7-aral-848520332/) · [Medium](https://medium.com/@mmirac.aral) · [TryHackMe](https://tryhackme.com/p/mmirac.aral) · mmirac.aral@gmail.com

Turkish (native), English (C2).
