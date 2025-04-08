# Chrome Extension Idea: Email Writer

## Authors

Tommy Li

## Problem Statement

Professionals spend a significant amount of time crafting email replies, especially when responding to long or complex threads. It’s easy to lose track of context, forget to respond, or delay replies due to the mental load of formulating the right message. Existing tools like Gmail’s Smart Reply are too simplistic and often ignore the tone or history of the conversation. Our extension solves this by automatically generating thoughtful, context-aware replies that reflect the full email chain and let users choose tone and intent before sending.

## Target Audience

The target audience includes busy professionals, founders, executives, salespeople, recruiters, and students — anyone who frequently communicates over email and needs to reply to long threads quickly and thoughtfully. They are tech-savvy, time-constrained, and rely on email as a primary communication channel. Many use Gmail or Google Workspace and are open to productivity-enhancing tools.

## Description

This Chrome Extension integrates into Gmail and uses AI to automatically draft email replies based on the full content of the email thread. Users can choose the tone and intent of the reply and insert the response into their email with one click, saving time and reducing decision fatigue while maintaining professionalism and context awareness.

## Selling Points

1. Understands full email context, not just the last message
2. Saves time by generating smart, editable replies instantly
3. Customizable tone and intent to match any scenario
4. Seamless integration with Gmail’s interface
5. No data storage — privacy-focused with secure processing

## User Stories

1. As a busy founder, I want to generate quick but thoughtful replies to investor emails so that I can focus on running my startup.
2. As a recruiter, I want to reply to candidate threads with personalized messages so that I maintain a professional and responsive image.
3. As a student applying for internships, I want help replying to long email chains with professors and employers so that I sound polished and confident.
4. As a sales rep, I want to send follow-ups that reference the entire thread so that my prospects feel heard and respected.
5. As an executive assistant, I want to draft responses quickly for my boss's emails so that I can manage time efficiently across tasks.

## Notes

We may face challenges parsing deeply nested Gmail threads due to the way Gmail formats quoted replies. We might need to refine our DOM scraping or use Gmail’s API in future versions. Another challenge is making sure AI replies are editable and not overconfident — we’ll allow full edits before sending. Long-term, the extension could evolve to include scheduling tools or smart summarization.

## References & Inspiration

