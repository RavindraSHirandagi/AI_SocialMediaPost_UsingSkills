# AI-Powered Social Media Composer

## Overview
This project contains a collection of specialized AI skills designed to assist with creating high-quality, trend-aware social media content. These skills leverage AI to research current topics and generate posts tailored to specific platforms.

## Available Skills

### 1. Writing LinkedIn Posts (`writing-linkedin-posts`)
This skill helps you craft professional and impactful LinkedIn updates.
- **Features:**
    - Researches top 10 trending professional/industry topics (e.g., AI, Tech, Leadership).
    - Generates 5 concise (3-4 sentences) post suggestions.
    - Includes relevant hashtags and engagement-driving questions.
    - Maintains a professional tone suitable for career growth and networking.

### 2. Writing Facebook Posts (`writing-facebook-posts`)
This skill focuses on creating engaging and relatable content for Facebook.
- **Features:**
    - Researches current viral and trending topics.
    - Generates 5 short, shareable post suggestions.
    - Uses conversational language and relevant hashtags.
    - Designed to maximize engagement and "likes."

## Installation & Setup

To use these skills with your AI agent:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/RavindraSHirandagi/AI_SocialMediaPost_UsingSkills.git
   ```

2. **Open in Your Agent's Workspace:**
   - Open the cloned folder as your active workspace in the Antigravity (or compatible) agent.
   - The agent will automatically detect and load the skills located in the `.agent/skills/` directory.

3. **Explore More Skills:**
   - This repository includes a vast library of additional skills in the `antigravity-awesome-skills/` and `anthropics_skills/` directories.
   - To use any of these, simply copy the desired skill folder into your active `.agent/skills/` directory.

## Creating New Skills
Detailed instructions for creating your own custom skills can be found in [antigravity-skill-creator.md](antigravity-skill-creator.md). This guide explains the required file structure, YAML frontmatter, and best practices for defining powerful agent capabilities.

To use a skill, simply mention it in your chat with the agent or describe what you want to do.

**Examples:**
- "Help me write a LinkedIn post about the latest AI trends."
- "@writing-linkedin-posts"
- "I need a Facebook post about the weekend."
- "@writing-facebook-posts"

## Future Improvements
- Add support for Twitter/X threads.
- Image generation prompts for each post.
- Instagram caption generator.
