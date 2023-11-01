---
layout: post
title: Return to programming experience
date: 2023-11-01
categories: [it, devops]
---

# Diving Back Into Programming: Stock-Value Discord Bot

For long period of time I was planning to create a Discord bot that will provide information about the stock price.
I couldn't find motivation for it and since I started to running this blog I decided to write about it.
In hopes that it will motivate me to spend my free time in developing that bot and most importantly to learn something new.

## Python or Golang?

I was thinking about using Python or Golang for this project. I still need to figure out what language will i use for it. I know python better than Golang, but I want to learn Golang and this project might be a good opportunity to do so. 

## Weighing the Pros and Cons

When making a decision between Python and Golang for a project, it's essential to weigh the advantages and disadvantages of each language in the context of the task at hand.

### Python:

**Pros:**
- **Simplicity & Ease of Learning:** Python's syntax is clear and readable, making it an excellent choice for beginners and for quick prototyping.
- **Rich Libraries:** Python boasts a vast collection of libraries for web development, data analysis, and other tasks, including the `discord.py` library, which simplifies creating Discord bots.
- **Community Support:** The Python community is extensive, ensuring that any issue or doubt one might have can be quickly resolved.

**Cons:**
- **Performance:** While Python is adequate for most tasks, it's interpreted and tends to be slower than compiled languages like Golang.
- **Concurrency:** Python's threading can be a challenge due to the Global Interpreter Lock (GIL). 

### Golang:

**Pros:**
- **Performance:** As a compiled language, Golang offers significant performance benefits over interpreted languages.
- **Concurrency:** Golang is known for its goroutines and channels, making concurrent programming straightforward and efficient.
- **Static Typing:** This feature can catch potential bugs at compile-time, reducing runtime errors.

**Cons:**
- **Steeper Learning Curve:** For those more familiar with Python, diving into Golang might be a bit challenging initially.
- **Fewer Libraries:** While Golang has a growing library ecosystem, it doesn't match Python's breadth just yet.

## Making The Decision

Considering my primary goal is to learn, leaning towards Golang might provide a better experience however it might be hard at first. It will push me out of my comfort zone and introduce me to new paradigms, especially around concurrency. On the other hand, if I want to get the bot up and running quickly and smoothly, Python would be the logical choice.

However, the journey is as crucial as the destination. Given my inclination to explore and the opportunity to dive deep into a new language, I'm leaning towards **Golang** for this project. The performance benefits, the unique approach to concurrency, and the challenge of the unfamiliar make it an exciting choice.

## Next Steps

Having settled on Golang, the next steps will be:
1. **Setting Up the Environment:** I'll start by setting up the Go environment on my system, ensuring I have all the necessary tools and libraries.
2. **Research:** I'll need to find libraries or APIs that provide stock price information that can be integrated with a Discord bot in Golang.
3. **Prototyping:** Before diving deep, a simple prototype will be essential. This will help me understand the challenges and potential blockers ahead.
4. **Documentation:** As I go along, documenting my journey will be crucial, not only for this blog but also for my own reference and to keep me motivated.
5. **Dockerization – Putting the Bot in a Container:** I want to make sure that my bot is running in a container. I will need to research how to do it in the most sufficient way.
6. **Deployment:** I will need to decide how I will deploy my bot. I will need to research what are the options and what are the pros and cons of each option.