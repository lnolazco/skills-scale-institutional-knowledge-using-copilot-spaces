# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted (coordinated by Technical Writer)
- Rollback / mitigation plan documented
- Smoke tests prepared
- Documentation updated and published (Technical Writer)
- Support team briefed on changes (Support Lead)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] Release notes published (Technical Writer)
- [ ] Support team notified of changes and known issues (Support Lead)

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - Support Lead monitors customer impact and communicates status
  - Technical Writer updates documentation if rollback affects published materials

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
