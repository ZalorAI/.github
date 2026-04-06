# Zalor

Catch broken AI agents before your users do.

AI agents create records, trigger workflows, and run on real systems. We test them automatically by simulating real user personas against your agent and scoring the results, so you can ship with confidence.

```python
from zalor.agents import test_agent

test_agent(
    agent_name="my-assistant",
    api_key="zal-...",
    run_agent=my_agent,
)
```

- **[Website](https://zalor.ai)** - Learn more
- **[Docs](https://agents.zalor.ai/docs)** - Get started in minutes
- **[Get Started](https://agents.zalor.ai)** - Start testing your agent
- **[GitHub Action](https://github.com/marketplace/actions/zalor-agent-test)** - Test your agent on every PR
