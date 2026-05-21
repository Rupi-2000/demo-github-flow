# GitHub Flow Demo Repository

## Purpose

This repository demonstrates GitHub Flow using a small Python FastAPI task management application.

## Application Scope

Initial version `v1.0.0` contains:

- task creation through REST API
- task completion through REST API
- listing all tasks
- listing open tasks
- SQLite database persistence
- version output
- automated tests
- GitHub Actions CI

Feature branches for priority, due dates, users, assignment, task status, bugfixes, and merge-conflict scenarios will be added later.

## Branching Strategy

GitHub Flow keeps `main` stable. New work is developed in short-lived feature or bugfix branches and merged back after validation.

## Branch Overview

Current initial setup:

- `main`

Planned later:

- `feature/add-task-priority`
- `feature/add-due-date`
- `feature/add-user-service`
- `feature/add-task-assignment`
- `feature/add-task-status`
- `bugfix/fix-task-completion`

## CI Setup

The GitHub Actions workflow runs on `push` and `pull_request`.

It installs Python dependencies and runs the test suite with `pytest`.

## Tags / Releases

- `v1.0.0`: initial base application
