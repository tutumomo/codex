# Codex Knowledge Graph Report

## Summary
- **Nodes**: 26,150
- **Edges**: 53,191
- **Communities**: 500

> **Note**: AST extraction only - semantic relationships skipped.

## Corpus
- Total files: 2,543
- Code files: 1,946
- Document files: 586
- Images: 11

## Method
AST extraction on all code files:
- Function and type definitions as nodes
- Import relationships as edges
- Type references and calls as edges

## Next Steps
To add semantic relationships:
`/graphify D:/TOMO/codex --update`