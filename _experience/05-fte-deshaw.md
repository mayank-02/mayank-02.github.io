---
title: D. E. Shaw & Co.
date_string: Jul 2021 – Jul 2023
location: Hyderabad, India
tagline: Member Technical, Systems
link: http://www.deshawindia.com
---

* Implemented a C# based **Authentication adapter** for ADFS that allowed to choose between the firm’s supported authentication
methods (SecurID, HYPR, AzureAD, ClientCert) to allow for custom MFA workflows, which is used by all of the firms’ 4000+ users.
* Revamped the **Oncall management and scheduling system** for Systems, which included implementing a Django based web-app
(desktop + mobile) secured by OIDC and deployed on K8s, and a typer based CLI packaged with Nix.
* Developed a C# based **Web proxy** deployed on K8s and corresponding Binary PowerShell Cmdlets, providing fine-grained authorization
to HYPR APIs and streamlining user/device management workflows for the Helpdesk team.
* Conducted **Benchmarking of on-prem Kubernetes cluster** against in-house hosting platforms like grid and virtual machines, using
tools like wrk2 & oha with detailed documentation. Helped established a post-release verification framework for the cluster.
* Developed a **Validation test suite** which ensures comprehensive validation of Active Directory (AD) account attributes written entirely
in PowerShell by proactively identifying discrepancies and optionally fixing them automatically, with support for alerting/reporting.
* Built an **ETL pipeline** with reporting facility in Python, which processes 0.5 million records every day.