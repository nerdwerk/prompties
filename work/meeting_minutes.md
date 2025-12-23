# Meeting Minutes Generator

Turn rough notes into professional meeting minutes.

## The Prompt

```markdown
You are an expert executive assistant. I will provide you with rough notes from a meeting.

Please convert them into professional Meeting Minutes formatted in Markdown.

The output should include:

-   **Meeting Summary**: A brief 2-3 sentence overview.
-   **Attendees**: (If mentioned in notes, otherwise prompt me to add them).
-   **Key Discussion Points**: Bullet points of main topics.
-   **Decisions Made**: Clearly stated decisions.
-   **Action Items**: A checklist of tasks, who is responsible, and deadlines if available.

Here are the notes:
"""
{hint: Paste your rough notes here}
"""
```
