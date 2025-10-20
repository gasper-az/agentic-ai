# Agentic Design patterns

## Reflection

It's a design pattern where we ask an LLM to examine its own outputs or bring in some external sources of information, and use that as feedback to interate again and come up with a better version of its output.

In the case of multi-agent, we can evan have one `Coder` agent and one `Critic` agent, which act as the human that points out errors, or requests improvements over the first agent.

## Tools use

LLMs can be given tools, i.e., functions that they can call to perform an specific task.

## Planning

See paper `Hugging GPT`.

An LLM decides what is the sequence of actions it needs to take.

> NOTE: These kind of agent are more experimental.

## Multi-agentic workflows

Multiple agents, some of them might be specialized in a different role, which work together to accomplish a complex task.
