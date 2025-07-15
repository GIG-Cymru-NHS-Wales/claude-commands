# Claude commands

This repository contains Anthropic Claude commands as markdown files.

## Syntax

Each command uses the format:

```text
@command.md <TASK_DESCRIPTION>`
```

## Setup

In this repository, see the directory `commands`.

Read the command markdown files and decide which ones you want to use.

In your project top directory, create a directory `.claude`.

In your directory `.claude`, create a directory `commands`.

Copy any of the command markdown files from this repository directory `commands` to your project directory `commands`.


## Usage Examples


### Complete Development Workflow

Ask an architect:

```text
@ask.md How to design a microservices architecture for an e-commerce platform handling 10M+ users
```

Implement a new feature:

```text
@code.md Implement user authentication system with login, registration, and password reset
```

Review the code:

```text
@review.md user authentication module
```

Generate tests:

```text
@test.md user authentication functionality
```

Optimize performance:

```text
@optimize.md login API response time
```

Check deployment:

```text
@check-deploy.md production environment
```

### Bug Fix Workflow

Debug a problem:

```text
@debug.md User login returns intermittent 500 errors
```

Code a fix:

```text
@code.md Fix login service concurrency issues
```

Test the fix:

```text
@test.md login concurrent scenarios
```

Check deployment:

```text
@check-deploy.md hotfix branch
```

### Architecture Consultation Workflow

Architecture guidance:

```text
@ask-architect.md Should we use event sourcing or traditional CRUD for our order management system
```

System design consultation:

```text
@ask-architect.md How to handle data consistency across microservices in a distributed transaction
```

Technology strategy:

```text
@ask.md Comparing GraphQL vs REST API for our mobile-first application
```

Implementation planning:

```text
@code.md Implement API gateway pattern with rate limiting and circuit breaker
```

### Refactoring Workflow

Refactoring analysis:

```text
@refactor.md user service module with high complexity
```

Review code:

```text
@review.md refactored user service
```

Optimize performance:

```text
@optimize.md refactored service performance
```

Test supplementation:

```text
@test.md refactored user service
```
