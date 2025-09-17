# AI Agents & Anomaly Detection 

This repository is a curated collection of presentations and resources exploring the core concepts of AI Agents, various frameworks for building them, and the application of Anomaly Detection in cybersecurity and data analysis. It serves as a knowledge base and reference guide for these advanced AI topics.

## 📁 Repository Structure

The repository is organized into several main branches, each focusing on a specific theme:

### 1. `main` / `AI-Agents-Full-Introduction`
This branch contains the foundational presentation on AI Agents.
*   **File:** `Introduction_of_AI_Agents.pptx`
*   **Contents:**
    *   **What are LLMs?** Introduction to Large Language Models and Transformer architectures (Encoder, Decoder, Seq2Seq).
    *   **What are AI Agents?** Systems that extend LLM capabilities by granting them access to tools and knowledge.
    *   **Components & Cycles:** Breakdown of an agent's structure (Environment, Sensors, Actuators) and its operational cycle (Thought, Action, Observation).
    *   **Types of Agents:** From Simple Reflex to sophisticated Multi-Agent Systems (MAS).
    *   **Agentic AI & Design Patterns:** Principles and patterns like Reflection, ReAct, Planning, and Tool Use that enable autonomous agent behavior.
    *   **Guardrails:** Essential concepts for safely deploying agents (Input, Tool, and Output Guardrails).
    *   **Frameworks Overview:** High-level introduction to key frameworks like LangChain and AutoGen.

### 2. `Anomaly-Detection-Application`
This branch focuses on identifying unusual patterns in data, featuring a practical Streamlit application.
*   **File:** `Anomaly_Detection.pptx`
*   **Contents:**
    *   **What is Anomaly Detection?** Definition and key concepts (Outliers vs. Novelty).
    *   **Core Algorithms:**
        *   **Isolation Forest:** An efficient algorithm that isolates anomalies through random partitioning.
        *   **Local Outlier Factor (LOF):** A density-based method for detecting local deviations.
        *   **One-Class SVM:** A model that learns a decision boundary around normal data.
    *   **Libraries & Datasets:** Overview of Python libraries (e.g., Scikit-learn) and relevant datasets for cybersecurity (intrusion detection), finance (credit card fraud), and IoT (room occupancy).
    *   **Python Strategy:** Insights into the coding and UML design strategy for building an anomaly detection system.
*   **Application:** Includes a traditional Streamlit app demonstrating the implementation of these algorithms on sample datasets.

### 3. `HuggingFace-Frameworks`
This branch dives into the Hugging Face ecosystem and modern frameworks for building powerful AI agents.
*   **File:** `Hugging Face.pptx`
*   **Contents:**
    *   **Introduction to Hugging Face:** A platform providing pre-trained models and libraries for NLP, vision, and more.
    *   **Smolagents:** A lightweight, code-first framework from Hugging Face for building agents with simplicity and flexibility. Covers model types (Transformer, InferenceClient) and agent types (Code Agent, Tool Calling Agent).
    *   **LlamaIndex:** A data framework for building LLM applications. Focuses on its RAG capabilities, tool creation (`FunctionTool`, `QueryEngineTool`), and building single/multi-agent workflows.
    *   **LangGraph:** A framework for building stateful, multi-agent applications as graphs. Explains its core components: **State**, **Nodes**, **Edges**, and the **StateGraph** container.
    *   **Advanced Concepts:** Covers Agentic RAG, Vision Agents, and Multi-Agent orchestration within these frameworks.

### 4. `AI-Agents-Resume`
This branch provides a concise summary that synthesizes the key points from all other presentations.
*   **File:** `AI_Agents.pptx`
*   **Contents:** A high-level resume of the entire repository, perfect for a quick refresher:
    *   Definition of an AI Agent (LLM + Tools + Memory).
    *   Core Components (Sensor, Environment, Actuators).
    *   Key Design Patterns (Reflection, ReAct, Tool Use, Planner, Multi-Agent).
    *   Real-world examples (Siri, Self-driving Cars).
    *   Concise overviews of the main frameworks: **Smolagents**, **LangChain**, **LangGraph**, **LlamaIndex**, and **AutoGen**.
    *   Recap of **Guardrails** and **Anomaly Detection** algorithms.

### 5. `Mermaid_charts`
This branch contains visual diagrams that map out the concepts covered in the presentations.
*   **Contents:** Mermaid code files (`.mmd`) and exported images (`.png`/`.svg`) for:
    *   **AI Agent Component Cycle:** Visualizing the interaction between Thought, Action, and Observation.
    *   **LangGraph State Graph:** Illustrating the flow of a stateful agent workflow with nodes and edges.
    *   **Multi-Agent Architectures:** Diagrams for patterns like Sequential, Hierarchical, Supervisor, and more.
    *   **Anomaly Detection Algorithm Flowcharts.**
    *   **RAG System Workflows.**

## 📚 Key Technologies & Concepts

*   **AI Frameworks:** Smolagents, LangChain, LangGraph, LlamaIndex, AutoGen
*   **AI Concepts:** LLMs, Agents, RAG, Tool Use, Multi-Agent Systems, Prompt Engineering
*   **Anomaly Detection:** Isolation Forest, LOF, One-Class SVM, Scikit-learn
*   **Visualization:** Mermaid.js
*   **Application Deployment:** Streamlit, Python
