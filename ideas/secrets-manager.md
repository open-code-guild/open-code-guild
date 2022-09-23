# Secrets Manager

A simple way to manage secrets in a project using URL pointers instead of a file.

## Motivation

`.env` files suck. They are prone to human error, not easily shared between distributed teams, and are prone to being read by malicious actors.

## Proposed Solution

Utilize modern HTTP authentication methods to store secrets in a remote location. This allows for a single source of truth for secrets, and allows for easy sharing of secrets between team members. It also allows for easy revocation of secrets in the event of a security breach, and can even be used to rotate secrets on a regular basis to meet security requirements.
