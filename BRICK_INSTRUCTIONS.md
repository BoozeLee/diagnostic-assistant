# BRICK INSTRUCTIONS
*Marco-o1 - 2026-02-20*

## What This Repo Does
Support medical diagnosis with pattern recognition.

## Price
$2,499/month

## Brick Type
Medical Diagnosis Support

## Gumroad Copy
Assist in medical diagnoses with our advanced AI support.

## Build
```bash
source ~/Energetic_Lexicon/.venv/bin/activate
pyinstaller --onefile --name diagnostic-assistantBrick --collect-all rich --copy-metadata rich codex_brick.py
```