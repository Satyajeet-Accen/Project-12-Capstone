# Project 12: Infrastructure CI Trigger (Terraform Plan)

## Overview
This repository demonstrates continuous integration (CI) for Infrastructure as Code by automating plan validation on every push.

## Automated Pipeline Tasks
* **Terraform Init:** Initializes the working directory and downloads required providers.
* **Terraform Plan:** Generates a speculative execution plan (`satyajeet-tfplan`) to preview infrastructure changes.
* **Artifact Upload:** Securely uploads the generated plan as a pipeline artifact for review.

## Infrastructure Tracked
* AWS SNS Topic (`satyajeet-infrastructure-updates`)
