# VentureZero Architecture

## Guiding Principles
- Single deployable application for V1.
- API-first.
- Deterministic analysis before LLM reasoning.
- Pluggable AI providers.
- Explainable findings with evidence.

## Layers
1. Ingestion
2. Parsing & Normalization
3. Engineering Intelligence Reference Layer (EIRL)
4. Rule Engine
5. Semantic Dependency Graph
6. AI Reasoning
7. Report Generation
8. REST API

## Primary API
POST /review

Input:
- Git repository
- PR diff
- ADR
- API spec
- Design document
- Architecture diagram metadata

Output:
- Findings
- Severity
- Confidence
- Evidence
- Recommended fixes
- Executive summary

## Core Components
- Parser Registry
- Knowledge Store
- Rule Engine
- AI Orchestrator
- Prompt Library
- Findings Engine
- Report Renderer

## Future Repositories
- venturezero-engine
- venturezero-web
- venturezero-rules
- venturezero-examples
