# 5 AM Thoughts: Building a Writing Prompt Generator

Date: 2024-02-14

Yet again, it's 5 am, and I'm wondering what I should do,
Be it wrong or right, I spent the night,
Working on another tool,
But my writer's block, believe it or not,
It's letting the words come through!
Oh what a bot, helped me a lot,
Maybe it helps you too?

## The Project

I've developed a tool using Microsoft's phi-4-128k-instruct model for generating writing prompts when creativity seems just out of reach. The application is built as a desktop widget using tkinter, allowing it to persist on screen and provide writing support right from startup via a batch file.

## Technical Details

- **Model**: Microsoft phi-4-128k-instruct
- **Frontend**: Tkinter for desktop widget
- **Integration**: Batch file for startup automation
- **Current Status**: Running on local GPU with CUDA
- **Future Plans**: Migration to Groq for improved performance

## Performance Considerations

Currently, even with CUDA acceleration, my laptop is reaching its computational limits just from inference. To address this, I'm planning to migrate the model's processing to Groq, which should provide better performance while freeing up my GPU for other tasks.

## Vision

This project is part of my larger goal to create tools that help make better use of free time. As I transition from being just a thinker to becoming a builder, I'm focusing on creating practical applications that solve real problems - even if those problems strike at 5 AM! 