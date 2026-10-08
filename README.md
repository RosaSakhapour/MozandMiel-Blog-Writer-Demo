# MozandMiel-Blog-Writer-Demo

An AI-powered recipe writing system I built for my food business, Moz&Miel.

The goal was simple: I wanted to turn my raw recipe notes into structured, educational blog content without manually rebuilding the same sections every time.

## Demo

[Watch the demo](./demo/demo-video.mp4)

## What It Does

The system takes structured recipe information such as:

- Recipe title
- Ingredients
- Cooking instructions
- Taste description
- Personal notes
- Additional educational topics

It then uses the OpenAI API to generate a structured blog post containing:

- A natural introduction
- "What Is/Are" educational section
- Reasons to make the recipe
- Ingredient notes
- Step-by-step cooking explanations
- FAQs
- Additional educational content
- Recipe card information

The generated content can then be sent directly to WordPress through the WordPress REST API, where it is created as a draft.

## Workflow

Raw Recipe Notes  
↓  
Next.js Application  
↓  
OpenAI API  
↓  
Structured JSON Output  
↓  
Content Validation  
↓  
WordPress REST API  
↓  
WordPress Draft

## Tech Stack

- Next.js
- TypeScript
- React
- OpenAI API
- WordPress REST API
- Tailwind CSS
- JSON
- Git/GitHub

## Why I Built It

Moz&Miel is both a food brand and a real-world environment for experimenting with technology.

Instead of treating software engineering and content creation as separate things, I wanted to build tools that solve problems I actually encounter while running the business.

This project is one example of that approach.

## Screenshots

### WordPress Posts Page Before Generation

<img width="1348" height="748" alt="image" src="https://github.com/user-attachments/assets/76677402-018a-496d-b810-041885618724" />


### Recipe Input

<img width="1235" height="578" alt="image" src="https://github.com/user-attachments/assets/6ddfb0e4-d216-44f0-93a8-11c644866f7a" />


### Generated Content

<img width="1261" height="638" alt="image" src="https://github.com/user-attachments/assets/0b2a14a0-fea6-4fcf-9ea1-6b6bf471f94e" />

### WordPress Posts Page After Generation

![WordPress Draft](./screenshots/wordpress-draft.png)

### Generated Post, Completed

