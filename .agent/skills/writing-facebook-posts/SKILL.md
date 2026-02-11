---
name: writing-facebook-posts
description: Researches top 10 trending topics, prompts user for selection, and generates 5 short, concise Facebook post suggestions with hashtags. Use when the user needs help writing Facebook posts or finding trending topics.
---

# Writing Facebook Posts

## When to use this skill
- When the user asks to write a Facebook post.
- When the user wants to find trending topics for social media/Facebook.
- When the user mentions "social media post" or "Facebook update".

## Workflow
- [ ] Research top 10 trending topics.
- [ ] Present topics to the user and wait for selection.
- [ ] Generate 5 post suggestions based on the selected topic.
- [ ] Ensure posts are short, concise, and include hashtags.

## Instructions

### 1. Research Trending Topics
Use the `search_web` tool to find the top 10 trending topics relevant to **QA, Automation, AI,Stock Market, ETF, NSE, BSE, Nifty** for "today".
<!-- This is a single-line comment 
Use the `search_web` tool to find the top 10 trending topics for "today" or "right now".
Focus on general news, pop culture, stock market, movie releases, or tech depending on context, unless global/general is implied.
-->

List the 10 topics clearly to the user.
**STOP** and ask the user to select one topic from the list.

### 2. Generate Post Suggestions
Once the user selects a topic:
1.  Use `search_web` to gather a bit more context on the specific topic if needed to make the posts relevant.
2.  Generate 5 distinct Facebook post suggestions.
3.  **Style Constraints**:
    - **Short and Concise**: Maximum 2-3 sentences.
    - **Engaging**: Use questions or strong statements.
    - **Hashtags**: specific to the topic (e.g., #TopicName #Trending #News).
    - **Stock Market**: Use stock market terms and jargon.
    - **ETF**: Use ETF terms and jargon.
    - **NSE**: Use NSE terms and jargon.
    - **BSE**: Use BSE terms and jargon.
    - **Nifty**: Use Nifty terms and jargon.
    - **Images**: Use images to make it "pop".
    - **Link**: Use links to relevant resources.
    - **Aesthetics**: Use emojis where appropriate to make it "pop".

### 3. Final Output
Present the 5 suggestions in a clear Markdown list or code blocks for easy copying. & Recommend the best post for the user.
