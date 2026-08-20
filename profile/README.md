# About

**TrustChain** is an AI-powered software supply chain security platform designed to assess the trustworthiness of open-source dependencies before they are integrated into software projects.

Modern applications rely heavily on third-party packages, making compromised dependencies a significant software supply chain risk. TrustChain aims to provide a unified and readable assessment of these dependencies by combining multiple sources of security evidence.

## What TrustChain Does

TrustChain analyzes dependencies using multiple layers of security analysis, including:

* **Static Security Checks:** signature and provenance verification, vulnerability auditing, project health evaluation, and package analysis.
* **Threat Intelligence:** collects and summarizes security information from vulnerability databases, security advisories, repositories, and other sources.
* **AI Risk Assessment:** evaluates the collected evidence to produce a risk score, confidence level, and human-readable explanation.
* **Behavioral Analysis:** suspicious or low-confidence packages can be escalated to an isolated sandbox for dynamic analysis of their runtime behavior.

The goal is to combine these sources of evidence into a single, actionable security assessment rather than relying on a single vulnerability database or detection technique.

## Planned Interfaces

TrustChain is designed to support:

* **CLI** for local dependency scanning
* **CI/CD integration** for automated security checks
* **REST API** for external integrations
* **Web Dashboard** for viewing and managing scan results

## Project Status

**IN PROGRESS**

TrustChain is being developed as a graduation project at the **Faculty of Computers and Artificial Intelligence - Cairo University**.