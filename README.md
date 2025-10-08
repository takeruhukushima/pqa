# Quickstart with CLI
### Installation
```bash
pip install paper-qa>=5
```
### OpenAI (default)
```bash
pqa ask 'What is PaperQA2?'
```

### Geminiを使う場合
```bash
pqa --llm "gemini/gemini-1.5-pro-latest" \
    --summary_llm "gemini/gemini-1.5-flash-latest" \
    --agent.agent_llm "gemini/gemini-1.5-flash-latest" \
    ask "what is paperqa2"
```
note:
429 error（exceeded your current quota）が起きた。

# Quickstart with Library
### Installation
```bash
pip install paper-qa>=5
```
### run main.py
```bash
python main.py
```

note:
上手くいっている。のでこちらを推奨。