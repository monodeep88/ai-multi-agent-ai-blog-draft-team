# Generation Notes

            Mode: ai

            Model: groq / llama-3.1-8b-instant

            Fallback reason: OpenAI limit reached. Automatically switched to Groq.

            Architecture: Research Team Assistant

            Template path: templates/multi-agent-ai/research-team-assistant

            Short description:

            A multi-agent AI system for collaborative blog post drafting

            Architecture notes:

            - Use a microservices architecture for scalability and maintainability
- Implement a knowledge graph for storing and retrieving domain-specific knowledge
- Use a message broker for agent communication

            Project planner agent workflow:

            - Content Generator: Define app boundaries, data flow, runtime stack, and integration points. Outputs: 
- Editor: Design FastAPI modules, service contracts, validation, and error handling. Outputs: 
- Reviewer: Design React screens, state flow, controls, and user feedback states. Outputs: 
