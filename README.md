## Current - Folder Structure
```plaintext
zerocom/
  app/
    main.py
    core/        (config, security, logging, exceptions)
    db/          (session, base, models)
    routers/     (auth, documents, ask, agent, runs)
    services/    (auth_service, ingestion_service, rag_service, agent_service)
    repositories/
    agent/       (loop.py, tools.py, prompts.py, langchain_agent.py)
    schemas/     (pydantic models)
  README.md
  ```