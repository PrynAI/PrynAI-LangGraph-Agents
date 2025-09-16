# Copilot Instructions for PrynAI-LangGraph-Agents

Welcome to the PrynAI-LangGraph-Agents repository! This document provides essential guidelines for AI coding agents to be productive in this codebase. It highlights the architecture, workflows, conventions, and integration points specific to this project.

## Big Picture Architecture
- **Purpose**: This repository is a living library of agentic AI demos, ranging from simple prototypes to production-ready agents.
- **Structure**:
  - `All-Agents-Notebooks/`: Contains Jupyter notebooks for various agent demos, such as conversational agents, data analysis agents, and question-answering agents.
  - `images/`: Visual assets related to agent designs and workflows.
  - `Production-Ready-Architectures/`: Organized subdirectories for advanced topics like data processing, deployment, evaluation, and security.
- **Key Concept**: The repository emphasizes modularity and reusability, with each agent or architecture serving as a standalone example.

## Critical Developer Workflows
- **Environment Setup**:
  - Install dependencies using `pip install -r requirements.txt`.
  - Ensure Jupyter Notebook is installed for running `.ipynb` files.
- **Running Notebooks**:
  - Navigate to `All-Agents-Notebooks/` and open the desired notebook in Jupyter.
  - Execute cells sequentially to explore agent functionality.
- **Testing**:
  - Currently, testing is manual via notebook execution. Ensure outputs match expected results.

## Project-Specific Conventions
- **Notebook Organization**:
  - Each notebook focuses on a specific agent or concept.
  - Use markdown cells for detailed explanations and code cells for implementation.
- **File Naming**:
  - Descriptive names (e.g., `conversational_agent.ipynb`) to indicate the notebook's purpose.
- **Documentation**:
  - Inline comments and markdown cells are critical for clarity.

## Integration Points and Dependencies
- **External Libraries**:
  - Common dependencies include `langchain`, `openai`, and `pandas`.
  - Refer to `requirements.txt` for the complete list.
- **Cross-Component Communication**:
  - Agents are designed to be modular; reuse components across notebooks where applicable.

## Examples and References
- **Key Files**:
  - `All-Agents-Notebooks/conversational_agent.ipynb`: Example of a conversational agent.
  - `All-Agents-Notebooks/data_analysis_agent_notebook.ipynb`: Demonstrates data analysis capabilities.
- **Visual Aids**:
  - Refer to `images/` for diagrams and workflows that complement the notebooks.

## Contribution Guidelines
- Follow the existing structure and naming conventions.
- Ensure new notebooks are well-documented with markdown explanations.
- Update `requirements.txt` if adding new dependencies.

By adhering to these guidelines, you can effectively contribute to and extend the capabilities of the PrynAI-LangGraph-Agents repository. If you encounter any ambiguities or have suggestions for improvement, please provide feedback!
