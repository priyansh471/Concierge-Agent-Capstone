#**Secure Concierge Agent**

**Project Overview**

This project is an Agentic Concierge System developed for the Google & Kaggle AI Agents hackathon. It functions as a secure, modular personal assistant that orchestrates tasks through a multi-agent framework, ensuring data privacy and efficient workflow management.

**Core Architecture**

The system is built on a modular design with three distinct components:
Security Module (secure_data_mask): Acts as a gateway to sanitize user input and mask Personally Identifiable Information (PII) before any processing occurs.
Research Tool (ResearchTool): An MCP-style interface that retrieves context or system-level data (e.g., current date) based on user queries.
**Multi-Agent System:**
**TaskPlanner:** Analyzes the context and derives a structured plan.
**ActionExecutor:** Executes the final steps defined by the planner, completing the agentic loop.

**Technical Implementation**

The project demonstrates core "Vibe Coding" principles:
Object-Oriented Design: Clean separation of agents and tools using Python classes.
Agentic Flow: Orchestrates a pipeline from input to execution, simulating real-world task delegation.
Data Privacy: Proactive masking of sensitive inputs within the processing pipeline.

### **How to Run**
1. Ensure Python 3.x is installed.
2. Clone this repository.
3. Run the script in your terminal:
   ```bash
   python main.py
4. Follow the interacive prompts to interact with the Concierge Agent.
