# UAPM – Unified AI Project Manifest

UAPM is a structured, machine-readable document that acts as a contract between a software project and its AI collaborators. It defines rules, context, and expectations so that AI systems can contribute consistently, predictably, and effectively.

## Why UAPM?

As AI becomes increasingly integrated into software development, teams need a clear and standardized way to communicate project intent to AI systems. UAPM solves this by offering:

- Consistency: All AI agents follow the same rules  
- Clarity: Design and logic are measurable and unambiguous  
- Source of truth: AI always reads the latest and most accurate information  
- Versionable & shareable: Changes are tracked like any other configuration file  
- Fewer bugs: Built-in constraints reduce errors  
- Faster onboarding: Humans and AI understand the project quickly  

## Creating a UAPM

UAPM files can be created directly with AI assistance: describe the project, its components, workflows, and rules, and AI will generate a correct UAPM file.  

To work correctly, the file must follow the structure in `uapm.json`.  
AI can also fill in missing sections, generate sample data, or expand the manifest for new projects.

## Using an Existing UAPM

You can also upload an existing `uapm.json` and let AI fill in or update missing sections, generate sample data, or suggest improvements. This makes it easy to keep your manifest up-to-date and complete without writing everything from scratch.

## Structure Overview

A UAPM can include sections such as:

- Metadata  
- Components & responsibilities  
- Design specifications  
- Workflow & rules  
- Data model  
- Testing & QA  
- Dependencies & build  
- Accessibility & localization  
- Implementation order  
- Environment variables  
- Resources & assets  
- External integrations  
- Version history  
- Developer notes  

## Example

See [`uapm.json`](./uapm.json) for a complete example of a manifest.  

This file can be used as a starting point:  
- Upload it to an AI assistant to fill in missing sections  
- Update existing information  
- Generate sample data for testing  
- Adapt it for new projects without writing everything from scratch

## License

This project is licensed under the MIT License.
