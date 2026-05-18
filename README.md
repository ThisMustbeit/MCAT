# MCAT Focus Notes

This repo is a lightweight static notes site for tracking:

- topics to revisit
- weakness points
- concepts that were only partially understood
- quick review summaries

## Structure

- `index.html` - homepage for the note system
- `styles.css` - shared styling
- `notes/index.html` - note directory
- `notes/templates/topic-note-template.md` - template for future notes

## How to use this repo

Each time a topic comes up in chat, we can add a new note in `notes/` or expand an existing one.

Recommended note sections:

1. What the topic is
2. What felt confusing
3. High-yield takeaways
4. Common traps
5. What to practice next

## Cloudflare Pages

Because this repo is plain static HTML/CSS plus markdown notes, it is a good fit for Cloudflare Pages without any build step.
