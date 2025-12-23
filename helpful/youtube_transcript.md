# YouTube Transcript Summarizer

Extract key insights from a YouTube video transcript.

## The Prompt

_First, copy the transcript from the YouTube video description or subtitles._

```markdown
I have pasted a transcript from a YouTube video below. Please process it as follows:

1.  **Title**: Give the video a catchy and descriptive title.
2.  **Summary**: Provide a high-level summary of the video's content (1-2 paragraphs).
3.  **Key Takeways**: List the top 5 most important points or lessons.
4.  **Quotes**: Extract 3 meaningful quotes from the speaker.
5.  **Timestamps**: If possible, estimate where key points usually occur (based on text flow), or just list the points sequentially.

Here is the transcript:
"""
{hint: Paste transcript here}
"""
```
