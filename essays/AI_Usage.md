---
layout: essay
type: essay
title: "Reflecting on AI Use in ICS 314"
# All dates must be YYYY-MM-DD format!
date: 2026-05-11
published: true
labels:
  - Software Engineering
  - Artificial Intelligence
  - Learning
---

## Reflecting on AI Use in ICS 314

### I. Introduction

Artificial intelligence tools have become a significant part of how students learn and how software gets built. In the context of software engineering education, AI assistants like ChatGPT and Claude are no longer novelties — they are practical tools that many students use daily for everything from understanding documentation to generating boilerplate code. ICS 314 was the course where I most deliberately engaged with these tools, and it gave me a clearer picture of both their strengths and their limits.

Throughout the semester I used two AI tools: Claude (by Anthropic) and ChatGPT (by OpenAI). I leaned on them heavily across most areas of the course, from working through WODs to drafting essays to building out features for the final project. My overall takeaway is that AI is genuinely powerful when used thoughtfully, but it can quietly mislead you when you trust it without verification.

---

### II. Personal Experience with AI

**Experience WODs (e.g. E18)**

I used AI regularly for the Experience WODs, primarily Claude and ChatGPT. My typical approach was to read through the WOD instructions myself first, attempt the problem, and then turn to AI when I got stuck. For example, during a functional programming WOD involving Underscore.js, I prompted ChatGPT with something like: "Using Underscore.js, write a function that takes an array of objects and returns only the names where the score is above 80." The response gave me a working starting point, but I still had to adjust the method chaining to match exactly what the WOD asked for. The benefit was getting unstuck quickly; the cost was that sometimes the AI's solution used a slightly different approach than what the course expected, which required extra time to reconcile.

**In-class Practice WODs**

For in-class practice WODs, I used AI in a similar way — mostly to understand the steps when I was lost rather than to generate a full solution. The time pressure of in-class WODs made AI especially useful as a fast reference. If I forgot the syntax for a React hook or a Meteor method, asking "How do I use useTracker in Meteor React?" was faster than digging through documentation. The answers were usually accurate enough to get me moving again, though I always had to read them carefully rather than paste blindly.

**In-class WODs**

For graded in-class WODs I followed the same approach. I would attempt the problem on my own first, then use AI to get unstuck if I hit a wall. I found that for WODs with tight time limits, having AI available reduced the stress of being completely blocked. That said, there were moments where ChatGPT gave me a plausible-looking answer that had a subtle error, and catching that error in a timed environment was its own challenge. The overall tradeoff felt worth it — AI helped me complete more WODs successfully than I would have otherwise — but it required me to stay critical rather than just accepting output.

**Essays**

I used AI to help structure and draft several essays in the course, including this one. My typical process was to give Claude a prompt describing the essay topic and what I wanted to say, review the draft it produced, and then rewrite sections in my own voice and with my own specific details. AI was useful for getting past the blank page and for organizing ideas into coherent sections. The risk is that AI-generated prose can sound generic, so I always had to go through and make sure the essay reflected my actual experiences and opinions rather than a plausible-sounding version of them.

**Final Project**

AI was most heavily used during the final project. I used both Claude and ChatGPT for code generation, debugging, and understanding unfamiliar patterns. For example, when setting up a new MongoDB collection with role-based access control, I asked Claude: "In a Meteor React app, how do I restrict a page so only users with the role 'admin' can see it?" The response walked me through using the `alanning:roles` package, which I then adapted to fit our project's structure. AI dramatically sped up the parts of the project involving unfamiliar APIs or configurations. The main cost was that generated code sometimes made assumptions about our project structure that didn't hold, so integration always needed careful review.

**Learning a Concept / Tutorial**

When encountering new concepts in the course — like functional programming patterns, Meteor's publish/subscribe model, or how React state flows through components — I frequently asked AI to explain them in plain terms. A prompt I used often was something like: "Explain Meteor's publish and subscribe pattern as if I have only used REST APIs before." These explanations were usually clearer and more tailored to my background than generic documentation. AI was genuinely helpful here, acting like an on-demand tutor who could meet me at my level.

**Answering a Question in Class or in Discord**

I did not use AI to answer questions in class or on Discord. When I contributed to a discussion or replied to someone's question, I preferred to answer from my own understanding. Posting an AI-generated answer to someone else's question felt like it missed the point — the value of those interactions is in genuine peer exchange, not relaying what a language model said.

**Asking or Answering a Smart Question**

Similarly, I did not use AI when formulating or responding to smart questions. Crafting a good smart question requires understanding your own confusion well enough to articulate it precisely, and I thought that process was valuable to do myself. Outsourcing it to AI would have shortcut the reflection that makes asking a smart question worthwhile.

**Coding Example (e.g. "give an example of using Underscore .pluck")**

I frequently asked AI for quick coding examples when the course introduced a new library or method. For instance, I asked ChatGPT: "Give me a short example of using Underscore's `.groupBy` method on an array of student objects grouped by grade." These examples were almost always accurate and saved me time compared to reading through library documentation cold. This is one of the areas where AI was most reliably useful with the lowest risk of error, since the outputs were small, verifiable, and easy to test immediately.

**Explaining Code**

When I encountered code I did not fully understand — whether from a course example, a Stack Overflow answer, or a teammate's pull request — I would paste it into Claude and ask: "Can you explain what this code does line by line?" This was especially helpful for more complex JavaScript patterns like promise chaining or higher-order functions. AI explanations were usually accurate and well-paced, though occasionally they glossed over a subtle detail that mattered. I learned to follow up with clarifying questions when something still felt unclear.

**Writing Code**

I used AI to write code throughout the course, particularly for repetitive or boilerplate-heavy tasks. For example, when creating a new page component in our final project, I would prompt Claude with: "Write a React component for a profile page that displays a user's name, email, and bio, pulling data from a Meteor collection." The output gave me a solid scaffold that I then modified to match our schema and styling. Writing code with AI is fast, but it requires knowing enough to spot when something is wrong — which is itself a skill the course helped me build.

**Documenting Code**

I used AI to help write JSDoc-style comments for functions in the final project. A typical prompt was: "Write a JSDoc comment for this function that fetches all active listings from the database and returns them sorted by date." The generated comments were clean and accurate. This is a low-risk use of AI since documentation is easy to verify — you can just read it and check whether it matches what the code actually does.

**Quality Assurance**

I used AI regularly for quality assurance, particularly for ESLint errors. When I had a block of errors I did not immediately understand, I would paste the code and the error messages into ChatGPT and ask: "Fix the ESLint errors in this code." It was effective for straightforward issues like missing semicolons, unused variables, or incorrect import ordering. For more complex errors involving React hooks rules or async/await patterns, the fixes were sometimes incomplete and I had to iterate. Overall this saved significant time compared to looking up each ESLint rule individually.

**Other Uses**

One additional use I found valuable was asking AI to review the overall structure of a component or module and suggest improvements. Prompts like "Is there a cleaner way to organize this Meteor method?" occasionally surfaced refactoring ideas I wouldn't have thought of on my own. It functioned like a code review from a knowledgeable peer, with the caveat that its suggestions weren't always aligned with the patterns the course emphasized.

---

### III. Impact on Learning and Understanding

Using AI heavily in ICS 314 had a real impact on how I learned — both positive and negative. On the positive side, having an always-available resource that could explain concepts, generate examples, and debug code lowered the friction of learning new material significantly. Topics that might have taken hours to piece together from documentation became accessible in minutes. This kept momentum up during the course, which moved quickly.

The challenge is that speed can come at the cost of depth. When AI does the heavy lifting, it is easy to move on without fully internalizing why something works. I noticed this most during WODs — sometimes I could complete a WOD with AI assistance but struggled to reproduce similar code from scratch later. That gap between using AI and truly understanding the material is something I had to consciously manage by reviewing solutions and asking follow-up questions rather than just accepting working code.

---

### IV. Practical Applications

Outside of ICS 314, I used AI in much the same way — as a fast reference and code assistant for personal projects. The habits I developed in this course, like prompting with specific context and verifying outputs before relying on them, carried over directly. I can see AI being a standard part of professional software development workflows, particularly for onboarding to unfamiliar codebases, generating boilerplate, and catching basic errors quickly.

---

### V. Challenges and Opportunities

The main challenge I encountered was AI's tendency to produce confident but subtly wrong answers. This was most problematic in areas where I lacked enough background knowledge to catch the error — a situation that happens frequently when learning something new. The opportunity this creates for software engineering education is teaching students not just how to use AI, but how to verify its outputs critically. Knowing when to trust AI and when to double-check it is a skill in its own right.

---

### VI. Comparative Analysis

Compared to traditional approaches — reading documentation, watching tutorials, working through problems independently — AI-assisted learning is faster but shallower by default. Traditional methods force you to sit with confusion longer, which often leads to deeper understanding. AI removes that friction, which is useful for productivity but can short-circuit the learning process if you let it. The most effective approach I found was combining both: use AI to get oriented quickly, then slow down and make sure you actually understand what was generated.

---

### VII. Future Considerations

AI tools will only become more capable and more embedded in software engineering workflows. For education, I think the important challenge is designing courses that teach students to be intelligent users of AI rather than passive consumers of its output. That means assignments that require demonstrated understanding beyond what AI can fake, and explicit instruction on how to prompt effectively, evaluate responses critically, and know when AI is not the right tool. ICS 314 gave me a good foundation for thinking about this, but I expect the conversation around AI in education will keep evolving.

---

### VIII. Conclusion

ICS 314 gave me extensive hands-on experience with AI tools in a software engineering context. Using Claude and ChatGPT across WODs, essays, the final project, and everyday coding tasks showed me where AI genuinely accelerates work and where it can mislead you if you are not careful. My main recommendation for future courses is to treat AI literacy — knowing how to use these tools responsibly and critically — as a core learning objective alongside the technical content. AI is not going away, and learning to work with it thoughtfully is one of the most practical skills a software engineering student can develop.
