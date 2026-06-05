---
name: verify-documentation
description: Verifies documentation accuracy against the codebase and corrects discrepancies.
---
Check that the content of the specified documentation file is correct by verifying it against the actual codebase implementation. 

1.  Read the documentation file to understand the claims made about the project structure, technology stack, API endpoints, and features.
2.  Explore the codebase (file structure, project manifest files such as `package.json`, `pyproject.toml`, `Cargo.toml`, `go.mod`, `pom.xml`, or similar, and source code files) to validate these claims.
3.  Identify any discrepancies between the documentation and the actual code (e.g., deprecated libraries, changed API paths, missing features, incorrect installation instructions).
4.  Adjust the existing text in the documentation file to match the reality of the codebase.
5.  Avoid adding new sections unless required to correct false information or provide essential missing context.
6.  Ensure code examples in the documentation are up-to-date and functional based on the current implementation.
