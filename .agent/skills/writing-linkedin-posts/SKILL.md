---
name: writing-linkedin-posts
description: Researches top 10 trending professional topics, prompts user for selection, and generates 5 short, concise LinkedIn post suggestions with hashtags. Use when the user needs help writing LinkedIn posts or finding professional trends.
---

# Writing LinkedIn Posts

## When to use this skill
- When the user asks to write a LinkedIn post.
- When the user wants to find trending professional or industry topics.
- When the user mentions "LinkedIn update" or "professional post".

## Workflow
- [ ] Research top 10 trending professional/industry topics.
- [ ] Present topics to the user and wait for selection.
- [ ] Generate 5 post suggestions based on the selected topic.
- [ ] Ensure posts are short, professional, and include relevant hashtags.

## Instructions

### 1. Research Trending Topics
Use the `search_web` tool to find the top 10 trending topics relevant to **QA, Automation, AI,Stock Market, ETF, NSE, BSE, Nifty** for "today".
List the 10 topics clearly to the user.
**STOP** and ask the user to select one topic from the list.

### 2. Generate Post Suggestions
Once the user selects a topic:
1.  Use `search_web` to gather more professional context/insights on the specific topic if needed.
2.  Generate 5 distinct LinkedIn post suggestions.
3.  **Style Constraints**:
    - **Short and Concise**: Maximum 3-4 sentences.
    - **Professional Tone**: Insightful, inspiring, or informative.
    - **Engagement**: meaningful questions or "hot takes".
    - **Formatting**: Use clean spacing and bullet points if necessary.
    - **Images**: Use images to make it "pop".
    - **Hashtags**: 3-5 relevant professional tags (e.g., #Leadership #TechTrends #CareerGrowth).

### 3. Final Output
Present the 5 suggestions in a clear Markdown list or code blocks for easy copying. & Recommend the best post for the user.
