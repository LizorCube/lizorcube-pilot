---
name: hello-world-creator
description: Creates a simple and runnable Hello World program.
---

# Hello World Creator

## Goal

Create the simplest runnable Hello World program using the programming language specified by the user.

## Execution Rules

1. Identify the programming language requested by the user.
2. If the user does not specify a language:
   - Detect the primary language used by the current project.
   - Ask the user to choose a language if it cannot be determined.
3. Inspect the existing project structure and files before making changes.
4. Use the standard entry-point format for the selected language.
5. Do not introduce third-party dependencies.
6. Do not overwrite existing files unless the user explicitly allows it.
7. The program must print:

```text
Hello, World!
