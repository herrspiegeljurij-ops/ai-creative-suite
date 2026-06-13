# Contributing Guide

Danke, dass du zur AI Creative Suite beitragen möchtest! 🎉

## Code of Conduct

Bitte lies unseren [Code of Conduct](CODE_OF_CONDUCT.md), bevor du anfängst.

## Wie kann ich beitragen?

### Bugs berichten

1. Überprüfe, ob der Bug bereits gemeldet wurde
2. Erstelle ein neues [Issue](https://github.com/herrspiegeljurij-ops/ai-creative-suite/issues)
3. Beschreibe:
   - Wie das Bug reproduziert werden kann
   - Was erwartet wurde
   - Was tatsächlich passiert ist
   - Dein System (OS, Python Version, etc.)

### Features vorschlagen

1. Erstelle ein neues [Issue](https://github.com/herrspiegeljurij-ops/ai-creative-suite/issues) mit dem Label "enhancement"
2. Beschreibe die gewünschte Funktionalität und den Use-Case
3. Erkläre, warum das Feature hilfreich wäre

### Pull Requests einreichen

1. **Fork** das Repository
2. Erstelle einen **Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Committe** deine Changes (`git commit -m 'Add AmazingFeature'`)
4. **Pushe** zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen **Pull Request**

## Development Setup

```bash
# Repository klonen
git clone https://github.com/herrspiegeljurij-ops/ai-creative-suite.git
cd ai-creative-suite

# Dev Dependencies installieren
pip install -e ".[dev]"

# Pre-commit Hooks einrichten (optional)
pre-commit install
```

## Code Style

Wir verwenden:
- **Black** für Code Formatting
- **isort** für Import Sorting
- **flake8** für Linting
- **mypy** für Type Checking

```bash
# Code formatieren
black src/ tests/
isort src/ tests/

# Linting
flake8 src/ tests/
mypy src/

# Tests laufen
pytest
```

## Commit Messages

Wir folgen dem [Conventional Commits](https://www.conventionalcommits.org/) Standard:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

Types:
- `feat`: Eine neue Feature
- `fix`: Ein Bug Fix
- `docs`: Dokumentation Änderungen
- `style`: Code Style (Formatting, etc.)
- `refactor`: Code Refactoring
- `test`: Tests hinzufügen oder ändern
- `chore`: Build, Dependencies, etc.

Beispiele:
```
feat(audio): add music generation module
fix(3d): resolve mesh optimization issue
docs: update installation guide
```

## Pull Request Checkliste

- [ ] Ich habe den [Contributing Guide](CONTRIBUTING.md) gelesen
- [ ] Mein Code folgt den Code Style Richtlinien
- [ ] Ich habe relevante Tests hinzugefügt
- [ ] Alle Tests bestehen lokal
- [ ] Ich habe die Dokumentation aktualisiert
- [ ] Meine Commits haben aussagekräftige Messages

## Questions?

Zögere nicht, ein [Issue](https://github.com/herrspiegeljurij-ops/ai-creative-suite/issues) zu erstellen oder uns zu kontaktieren.

Danke für deinen Beitrag! 🚀
