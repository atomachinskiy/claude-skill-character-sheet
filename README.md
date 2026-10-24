# character-sheet — лист персонажа для Higgsfield

Скилл для ИИ-ассистентов (Claude Code, Codex, Hermes) по бесплатному гайду GenHQ «Character Sheets / The Complete Workflow» для Higgsfield: одно фото лица → лист образа (5 ракурсов, линейка роста, 8 макро-деталей) → новые кадры (GPT Image 2.5 / Nano Banana 2.1) → видео с переносом движения (Higgsfield Genjutsu Motion transfer, Seedance 2.5).

Внутри `character-sheet/`:
- `SKILL.md` — порядок работы по-русски, кнопки Higgsfield, проверка, правки, пакет персонажа;
- `references/01-sheet-template.txt` — шаблон листа (дословно);
- `references/02-looks-genhq.md` — 6 готовых описаний образов (дословно);
- `references/03-video-and-fixes.md` — видео-промпт, формулировки правок, финальная проверка.

## Установка
```bash
git clone https://github.com/atomachinskiy/claude-skill-character-sheet.git /tmp/cs
cp -r /tmp/cs/character-sheet ~/.claude/skills/                 # Claude Code
cp -r /tmp/cs/character-sheet ~/.codex/skills/                  # Codex
mkdir -p ~/.hermes/skills/creative && cp -r /tmp/cs/character-sheet ~/.hermes/skills/creative/   # Hermes
```
Скилл подхватится после перезапуска сессии ассистента.
