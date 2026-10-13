# System Process & Workflow Architecture

1. **User Input:** The student pastes assignment text or syllabus content into the app interface.
2. **AI Parsing:** The AI module extracts key metadata (Subject, Assignment Title, Deadline, Weight).
3. **Priority Calculation:** The system executes the scoring formula defined in `AGENT.md`.
4. **Dashboard Render:** The Next.js frontend updates the student's task board with ordered priorities.
