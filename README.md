# Context-Chunker-Assistant

![alt text](banner.webp)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview
The Context Chunker Assistant is a specialized AI system prompt designed to transform large documents into manually curated, high-quality context chunks for AI systems. This tool bridges the gap between raw data and refined knowledge bases by facilitating human-in-the-loop context creation.
 
## Purpose
While automated chunking algorithms exist for RAG (Retrieval-Augmented Generation) systems, they often lack the nuanced understanding and organization that human curation provides. This assistant helps users create manually curated context data that is:

1. **Semantically coherent** - Information is grouped by related concepts
2. **Concisely formatted** - Data is presented in clear, digestible bullet points
3. **Properly structured** - Content is organized with appropriate headers and formatting
4. **Human-verified** - Each chunk passes through human review for accuracy

 ### Compared to Automated Chunking
Traditional automated chunking typically:
- Splits text based on token count or character limits
- May break semantic units of information
- Doesn't organize information by topic
- Lacks human verification of relevance and accuracy

The Context Chunker Assistant approach:

- Groups information by semantic relevance
- Preserves the meaning and relationships between facts
- Organizes information under appropriate topic headers
- Allows human review and refinement of each chunk
- Transforms verbose text into concise, structured data points

---

### Use Cases
This approach is particularly valuable for:
- Personal knowledge bases
- Professional expertise documentation
- Company knowledge management
- Custom AI assistant training
- Any scenario where quality of context matters more than quantity

---

## How It Works
1. Upload your source document (text, markdown, etc.)
2. The AI analyzes the content and identifies related information
3. It transforms verbose text into concise, third-person bullet points
4. Content is organized by topic with appropriate headers
5. You can review, edit, and save these chunks to your knowledge base

 ## Getting Started
1. Copy the system prompt from [`system-prompt/v1.md`](system-prompt/v1.md)
2. Use it with your preferred AI assistant in a web UI
3. Follow the workflow described in the prompt
4. Save the generated chunks to your knowledge base or vector database
5. Check out our [examples](examples/) to see sample input and output
 
## License
[MIT License](LICENSE)
