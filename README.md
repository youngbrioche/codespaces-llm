# LLM CLI Sandbox

GitHub Codespaces Umgebung mit LLM-cli und Zugriff auf GitHub Hosted Models via GITHUB_TOKEN.

[Codespace starten](https://codespaces.new/youngbrioche/codespaces-llm?quickstart=1)

Ausprobieren:

```bash
llm "Wer bist Du?"
```

Default Model anzeigen:

```bash
llm models default
```

Verfügbare Modelle auflisten, anderes Modell nutzen:

```bash
llm models
llm "Wer bist Du?" -m github/gpt-5-nano
```

LLM-cli wird mit dem [llm-github-models](https://github.com/tonybaloney/llm-github-models) Plugin konfiguriert.
