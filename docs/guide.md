# How to Use UAPM

UAPM is designed to help both humans and AI systems understand the structure, rules, and expectations of a software project.

## For Developers

- Use `uapm.json` to document your project’s components, design, workflow, and testing.
- Keep it updated as the project evolves.
- Share it with collaborators to ensure consistency.

## For AI Systems

- Load `uapm.json` as context before generating code or making decisions.
- Follow instructions in `workflow.aiInstructions` and respect design specs.
- Use `dataModel` to validate inputs and outputs.

## Tips

- Start with a minimal version and expand over time.
- Use version control to track changes.
- Consider creating a JSON schema for validation.
