****# Helpful Prompts

An in-browser organizer for AI prompts. Search, filter, favorite, and manage prompts with import/export support.

## Features
- Search by title, purpose, or prompt text
- Filter by category, LLM, and tags
- Favorite prompts for quick access
- Add, edit, delete prompts with modal forms
- Import/export prompt collections as JSON
- Manage category/tag/LLM lists

## Getting Started
1. Open `index.html` in your browser.
2. Use the search bar and filters to find prompts.
3. Click a card to expand/collapse the full prompt.

## Data Storage
All data is stored locally in your browser via `localStorage`. Export JSON to back up or transfer your prompts.

## Files
- `index.html`: The full app (HTML, CSS, JS)

## Template Version

A blank template version is available at `prompt-template.html` for others to use as a starting point.

### Using the Template
1. Copy or rename `prompt-template.html` to your own `index.html`
2. Open in any browser - no server or build step required
3. The template includes 2 example prompts demonstrating the data structure
4. Delete the example prompts and add your own via the "Add Prompt" button
5. All data is stored in your browser's localStorage

### Prompt Data Structure
Each prompt has the following fields:
- **Prompt Title**: Display name for your prompt
- **Purpose**: Brief description of what the prompt does
- **The Prompt**: The actual prompt text to copy/use
- **Category**: Organize prompts (e.g., "Writing", "Coding", "Research")
- **Tags**: Keywords for filtering (comma-separated)
- **LLM**: Target AI model (ChatGPT, Claude, Gemini, etc.)
- **Notes**: Additional tips or usage guidance

### Customization
- Edit the `<script id="promptsData">` JSON block to pre-load your own prompts
- Modify CSS variables in `:root` to change the color theme
- The app works entirely offline after initial load

## Notes
This project is a single-file HTML app with no build step and no server required.
