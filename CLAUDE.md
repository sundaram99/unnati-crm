# Unnati Bot — Claude Code Instructions

## Permissions
You have full permission to:
- Run any bash/shell commands without asking
- Run any Python commands (pip install, python, etc.)
- Run any Node/npm commands
- Create, edit, delete any files in this project
- Make directory changes freely
- Install packages via pip or npm
- Read and write .env files (except committing them to git)

## Never ask permission for:
- cd commands
- mkdir commands
- pip install --break-system-packages
- npm install
- Running bot.py or any python files
- Creating new files or folders
- Editing existing files

## Project context
This is a Telegram CRM bot for Indian B2B founders.
Stack: Python, python-telegram-bot v21, Groq API, Supabase.
Always use python with --break-system-packages flag for pip.
Always handle errors gracefully.