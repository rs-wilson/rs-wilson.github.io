---
title:  "Experimenting with AI"
date:   2025-01-11 00:00:01
categories: software-engineering
tags: engineering javascript
---
If you're like me, you tried AI when it first came out and thought "nope, this isn't useful yet". And that was true two years ago. In that time, AI models have improved so significantly that when I recently tried [Claude](https://claude.ai), I was blown away. Yes, AI now has the power to change the world.  

It's still a tool. Like the invention of the power drill, it simply makes creating works of engineering and art that much faster, not necessarily any better. Not only does the AI still need appropriate prompts, it needs a human's ingenuity to properly iterate. Claude, in this case, is excellent at working with iterative prompts, which was missing in earlier versions of these types of tools.  

With Claude, I was able to generate a full video game [Biplanes](https://github.com/rs-wilson/biplanes) in _hours_ instead of _days_, with no real programming other than telling Claude to modify the existing codebase. However, I ran into a few limitations. First, while there is a 'project' context you can create within Claude, you need to manually keep files in sync, so it's not as easy as just working within Visual Studio. Second, it conversations or project context became too long, the AI would run into the limits that are in place; and I'm running the profession, paid version. This is the direct and intimate limitation with AI in the world right now: context is powerful, but there's not enough power to go around (yet).

These limitations had me seek out more integrated tools. While I was able to almost-easily generate a single-file JavaScript game, real work will require much larger contexts. The option that stuck out to me was (Cody)[https://sourcegraph.com/cody], the Visual Studio extension which is powered by Claude. This was definitely neat, however in working with it even through just a few additional files, as I tried to split up the game into a more appropriate file structure, it was clear that it struggled with loading all necessary context. Even the auto-complete++ feature that Cody is famous for is nice, but still more often wrong. That's the thing about engineering: you're usually doing something _new_.

I need to try Github's co-pilot next. However, as of today the limits of AI (even agentic AI) are clear, and engineers aren't going anywhere. We'll be using our power tools in the same way craftsman of old started to be more productive in their shops with electricity.