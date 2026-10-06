# LangGraph Tutorials

A collection of hands-on notebooks and scripts for learning [LangGraph](https://langchain-ai.github.io/langgraph/), from basic graph workflows to chatbots, tools, RAG, human-in-the-loop, and subgraphs.

## Contents

| File | Topic |
|------|-------|
| `0_test_installation.ipynb` | Verify the environment is set up |
| `1_bmi_workflow.ipynb` | Basic sequential workflow (BMI calculator) |
| `2_simple_llm_workflow.ipynb` | Simple LLM workflow |
| `3_prompt_chaining.ipynb` | Prompt chaining |
| `4_batsman_workflow.ipynb` | Parallel workflow (batsman stats) |
| `5_UPSC_essay_workflow.ipynb` | Parallel LLM workflow (UPSC essay evaluation) |
| `6_quadratic_equation_workflow.ipynb` | Conditional workflow (quadratic equation) |
| `7_review_reply_workflow.ipynb` | Conditional workflow (review replies) |
| `8_X_post_generator.ipynb` | Iterative workflow (X post generator) |
| `9_basic_chatbot.ipynb` | Basic chatbot |
| `10_persistence.ipynb` | Persistence and checkpointing |
| `11_tools.ipynb` | Tools and tool calling |
| `12_mcp.py` | MCP (Model Context Protocol) integration |
| `13_rag.ipynb` | RAG with LangGraph (uses `intro-to-ml.pdf`) |
| `14_hitl.ipynb` | Human-in-the-loop |
| `15_subgraphs.ipynb`, `15_subgraph_shared.ipynb` | Subgraphs with shared and different state |
| `chatbot_with_hitl.py`, `chatbot_without_hitl.py` | Chatbot scripts with and without human-in-the-loop |

## Setup

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Create a `.env` file in the project root with your API keys:

```
OPENAI_API_KEY=your_key_here
```

Then open the notebooks in Jupyter or VS Code, starting with `0_test_installation.ipynb`.

## Tech stack

Python, LangGraph, LangChain, OpenAI, SQLite checkpointer.
