# 🤖 Agents

Agent and multi-agent workflows for research, content, and operations.

## 📂 Modules

- `basics/` – Simple single-agent examples to get started.
- `advanced/` – Multi-agent orchestration, tools, and more opinionated setups.

## ⚙️ Setup

```bash
cd Agents/basics
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env  # add your keys (OpenAI / Anthropic / etc.)
python main.py
```

## 🧪 Example: Research agent

1. Edit `config.yaml` (topic, tone, output format).
2. Run:

```bash
python research_agent.py --topic "AI automation for small businesses"
```

3. Check the `outputs/` folder for the generated brief.

## 🛠️ Customization

- Swap models via `.env`.
- Add tools in `tools/` and wire them into the agent config.
- Use this as a template for your own domain-specific agents.
