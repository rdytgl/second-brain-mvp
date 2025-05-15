# Second Brain

An AI-powered, mobile-first "second brain" app that helps users turn unstructured journal entries into a dynamic knowledge base of ideas, goals, emotions, and personal projects. Built for clarity, reflection, and intelligent self-coaching — without the need to configure complex tools like Obsidian or Notion.

## Vision

To create a tool that feels like writing in a journal, but with the intelligence to help users organize thoughts, track evolving goals, and gain insight from their own mind — ultimately serving as a general-purpose life mentor.

## Core Features (Planned for MVP Alpha)

- **Thought Dump Input:** Journal freely via mobile — online or offline.
- **AI Sorting into Tiles:** Automatically organizes entries into topic-based tiles (e.g. Projects, Ideas, Emotions, To-Dos).
- **Tile Dashboard:** Home screen shows evolving tile cards, each reflecting a theme, summary, or task list.
- **Auto-Tagging:** Tags are inferred based on content; used to enable cross-linking and future graph view.
- **Context-Aware AI:** Model follows up on evolving goals, asks for clarification, and detects tone/emotion.
- **Offline Mode:** Users can journal offline; syncing and processing occurs once back online.
- **Memory Simulation:** Embedding-based memory for tracking evolving concepts over time.
- **User-Controlled Editing:** Users can edit tile content or let AI organize and update it.
- **Project Awareness:** Tasks mentioned in journals are turned into checkboxes under relevant tiles.

## Future Features

- Graph view (à la Obsidian) based on tag relationships
- Calendar/task integration
- Smart reminders (e.g. “You mentioned Project X 2 weeks ago—want to revisit it?”)
- Paid AI Life Mentor (in-app guidance/coaching feature)
- Team/collaborative version for professional use

## Tech Stack (Planned)

- **Frontend:** Expo (React Native)
- **Backend:** Supabase (auth, storage, sync)
- **Local Storage:** SQLite via Expo for offline journal entries
- **AI/LLM:** Claude/OpenAI API (for online), lightweight local models for tagging (TBD)
- **Memory:** Embedding-based vector search (TBD solution)
- **Payments:** Stripe (for future mentor feature)

## Timeline

- **Week 0 (May 13–19):** Orientation & tool exploration
- **Week 1–8:** Build towards working MVP Alpha

## Status

Currently in research, planning, and prototyping. Active development starts Week 1 (May 19, 2025).

## Contributions

Currently a solo project. Will open source parts of the stack and invite feedback as the prototype stabilizes.
