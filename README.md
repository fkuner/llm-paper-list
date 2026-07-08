# LLM Paper List

This repository tracks my LLM paper reading plan, notes, and follow-up ideas.

## Workflow

- Add candidate papers to `papers/papers.csv`.
- Move the `status` field through `backlog`, `reading`, `read`, and `reviewed`.
- Keep detailed notes in `notes/` using `templates/paper-note.md`.
- Use GitHub issues for reading tasks, questions, and follow-up experiments.

## Status

| Status | Meaning |
| --- | --- |
| `backlog` | Paper is worth reading later. |
| `reading` | Paper is currently being read. |
| `read` | First pass is complete. |
| `reviewed` | Notes, takeaways, and follow-ups are complete. |

## Repository Layout

```text
papers/
  papers.csv        # Structured paper tracker
notes/
  README.md         # Notes index
templates/
  paper-note.md     # Note template for each paper
```

## Paper Tracker Columns

- `title`: Paper title.
- `year`: Publication year.
- `venue`: Conference, journal, workshop, or preprint source.
- `topic`: Main topic or tag.
- `status`: `backlog`, `reading`, `read`, or `reviewed`.
- `priority`: `high`, `medium`, or `low`.
- `url`: Paper URL.
- `notes`: Link to a note file or short context.
