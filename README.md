# Aetheris Analytics — Hardened Linux Server Infrastructure

An academic system administration project focused on configuring and hardening a Linux server environment.

## Project details

- **Course:** CIT6314 — System Administration
- **Institution:** Multimedia University (MMU)
- **Environment:** AlmaLinux 9.8 running in UTM/QEMU
- **Project type:** Academic lab / infrastructure configuration

The project report describes a multi-department server setup with 70 user accounts across five departments.

## Security and services covered

- **SELinux:** Mandatory access control and security policy enforcement
- **firewalld:** Host firewall configuration
- **SSH:** Key-based authentication, configured on port 2222
- **Apache HTTP Server:** Web service configured with TLS/HTTPS
- **Samba:** Network file sharing
- **POSIX ACLs:** Fine-grained file and directory permissions
- **Lynis:** Security auditing and hardening review

## Security approach

The lab emphasizes limiting exposed services, using SSH key authentication, enforcing SELinux, protecting web traffic with TLS, applying least-privilege file permissions, and reviewing configuration with a security auditing tool.

## Audit result recorded in the report

The report records a Lynis index change from **69 to 71**. This is a result documented by the project report, not an independent certification or guarantee of production security.

## Scope and safe use

This repository documents an academic lab. It should not be treated as a production-ready server blueprint without further review, testing, monitoring, and environment-specific hardening.

Do not commit passwords, private SSH keys, tokens, real user data, or other secrets to this repository.

## Author

Mubarak Raji — Information Systems student, Multimedia University.
