# LinkedIn Content Intelligence Agent

## Goal
Build an AI agent that analyzes successful LinkedIn content and helps create better LinkedIn posts based on real content patterns.

The main focus is:
- AI
- AI Agents
- Automation
- SAP
- SAP BTP
- Enterprise AI
- Technology

## Core Workflow

The system should:

1. Collect or receive LinkedIn posts.
2. Analyze each post.
3. Identify patterns in successful content.
4. Discover interesting topics and content opportunities.
5. Generate original post ideas.
6. Write LinkedIn posts.
7. Score posts and suggest improvements.

## Post Analysis

For each post analyze:
- Topic
- Hook
- Format
- Tone
- Writing style
- CTA
- Engagement
- Strengths
- Weaknesses
- Why the post may have performed well

## Main Components

### Research Agent
Organizes posts and creator data.

### Content Analyzer
Analyzes individual posts.

### Strategy Agent
Compares posts and identifies successful patterns, topics and opportunities.

### Post Writer
Generates original ideas and posts using insights from the analysis.

## MVP
The first version should be simple.

Input:

`data/posts.json`

The system should:

1. Read the posts.
2. Analyze them using AI.
3. Save structured results.
4. Compare high-performing posts.
5. Identify patterns.
6. Generate 10 content ideas.

Do not implement automatic LinkedIn scraping in the first version.

## Technology

- Node.js
- JavaScript
- OpenAI API
- JSON for initial data storage

Keep the architecture simple. Do not add a database or frontend until necessary.

## Security

API keys must use environment variables.
Never commit `.env` or credentials to GitHub.

## Important Principles

Use real data whenever possible.
Clearly separate data-based observations from AI assumptions.
Do not copy other creators' content. Analyze patterns and use them to create original content.
Human approval is required before publishing anything.

The priority is:

**Useful analysis > complex architecture**
