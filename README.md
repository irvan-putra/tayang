# Tayang

AI-written Python experiments: hands-free voice commands with Whisper, and a `pysentation` slide deck shown as a train journey.

## Contents

- `background_listening.py` listens in the background and turns speech into screen actions: saying "next" clicks, saying "back" presses the left arrow. It uses OpenAI Whisper (local, `base` model) through `SpeechRecognition`, plus `pyaudio` and `pyautogui`. Based on [this Medium tutorial](https://medium.com/@dominique.heer/controlling-your-computer-with-voice-commands-by-using-openai-whisper-09c867c635b2). Untested beyond the original experiment.
- `train_journey.py` is the guide deck from the [`pysentation`](https://github.com/mimseyedi/pysentation) project (GPL-3.0): slides styled as train wagons that introduce the module's keyboard navigation and `rich` formatting.

## Run

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python background_listening.py
```

## License

GPL-3.0 - see [LICENSE](LICENSE). Licensed to match [`pysentation`](https://github.com/mimseyedi/pysentation) (GPL-3.0), whose guide deck `train_journey.py` reproduces; that deck remains the work of the pysentation authors.

## Authorship

The code and documentation in this repository are AI-written. Irvan confirmed their AI-generated origin on 24 November 2026. This is an authorship disclosure, not a claim that he reviewed every file.

---

Built with AI assistance (Instinct, Windsurf and others). Not everything has been reviewed by Irvan. No Fenrir usage in this repo.
