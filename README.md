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

### Recipe Input

![Recipe Writer](./screenshots/recipe-writer.png)

### Generated Content

![Generated Blog Post](./screenshots/generated-blog-post.png)

### WordPress Integration

![WordPress Draft](./screenshots/wordpress-draft.png)

