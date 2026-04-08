\# Hybrid Data Migration \& Storage Integration on AWS



\## Overview

This project demonstrates a hybrid data migration pattern from an on-premises NFS source to Amazon S3 using AWS DataSync.



\## Goal

Show how large-scale hybrid data transfers can be structured with YAML-based Infrastructure as Code and documented migration patterns.



\## Current Scope

\- Amazon S3 destination bucket

\- IAM role for DataSync access

\- AWS DataSync NFS source location

\- AWS DataSync S3 destination location

\- AWS DataSync task



\## Hybrid Migration Context

This project is designed as part of a broader migration approach that can also include:

\- AWS Direct Connect for high-bandwidth private connectivity

\- AWS Site-to-Site VPN for secure network connectivity

\- AWS Snowball Edge for very large offline data transfers

\- AWS Storage Gateway for ongoing hybrid storage integration



\## Files

\- `cloudformation/datasync-migration.yaml` – CloudFormation YAML template

\- `docs/` – notes and later architecture diagrams



\## Services Covered

\- AWS DataSync

\- Amazon S3

\- AWS IAM

\- AWS Snowball Edge

\- AWS Direct Connect

\- AWS Site-to-Site VPN

\- AWS Storage Gateway



\## What I Learned

\- How to model hybrid migration workflows in YAML

\- How to connect on-premises storage to AWS migration targets

\- How to define IAM access for managed data transfer services

\- How to present migration architecture professionally on GitHub

