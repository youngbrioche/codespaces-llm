# KI für Architekt:innen Sandbox

GitHub Codespaces Umgebung mit LLM-cli und Zugriff auf GitHub Hosted Models via GITHUB_TOKEN.

Ausprobieren:

```bash
llm "Wer bist Du?"
```

Verfügbare Modelle auflisten, anderes Modell nutzen:

```bash
llm models
llm "Wer bist Du?" -m github/gpt-5-nano
```

LLM-cli wird mit dem [llm-github-models](https://github.com/tonybaloney/llm-github-models) Plugin konfiguriert.
