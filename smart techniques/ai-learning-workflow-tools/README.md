# AI Learning Workflow

A lightweight prompt-based workflow for learning technical topics with AI while continuously building a personal knowledge base.

## The Problem

AI conversations often contain valuable explanations, clarifications, and follow-up questions, but the knowledge remains scattered across chat history and is difficult to revisit later.

## The Solution

This repository contains four prompts that work together as a learning and knowledge-management workflow:

1. **Stay Brief Prompt**
   - Keeps responses concise.
   - Reduces context-window bloat.
   - Encourages fast, iterative learning through follow-up questions.

2. **Topic Collector (New Topic)**
   - Creates a structured topic document from a conversation.
   - Produces a standalone knowledge base entry rather than a chat summary.

3. **Topic Collector and Enhancer**
   - Updates an existing topic document with newly acquired knowledge.
   - Maintains a single source of truth as understanding evolves.

4. **Raw Markdown Formatter**
   - Returns output in a format that can be copied directly into a `.md` file.
   - Simplifies storing generated documentation in a repository.

## Typical Workflow

```text
Learn topic with AI
        ↓
Use Stay Brief Prompt
        ↓
Ask questions and follow-ups
        ↓
Generate initial topic file
        ↓
Save as Markdown
        ↓
Continue learning later
        ↓
Enhance existing topic file
        ↓
Maintain a growing personal knowledge base
```

## Example Use Cases

- .NET and C#
- Software architecture
- Cloud technologies
- System design
- Algorithms and data structures
- DevOps and infrastructure
- Any topic learned incrementally through AI conversations

## Goal

Transform AI conversations into durable, structured knowledge that can be reviewed, refined, versioned, and shared through Git.
