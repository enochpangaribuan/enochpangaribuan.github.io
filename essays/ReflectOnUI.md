---
layout: essay
type: essay
title: "Frameworks for U and I"
# All dates must be YYYY-MM-DD format!
date: 2026-02-26
published: true
labels:
  - Software Engineering
  - Learning
  - HTML
  - Bootstrap 5
---

## UI Frameworks: Frustrating at First, Powerful in the End

UI frameworks are not simple. In fact, learning one can feel almost like learning a new programming language. When I first started working with Bootstrap, I quickly realized that this was more than just adding style to HTML. It was learning an entire system of structure, layout, and design rules. At first it was overwhelming, but over time I began to understand why developers use UI frameworks instead of relying only on raw HTML and CSS.

One of the coolest parts of learning Bootstrap was getting hands-on with real website components. Instead of staring at plain HTML elements, I was building responsive navbars, experimenting with different types of navigation layouts, creating footers, styling buttons, and organizing content that could realistically appear on a home page. I especially enjoyed seeing how quickly a page could look professional just by applying the right classes. It felt powerful to transform something simple into something polished with only a few lines of code.

For example, creating a styled button in Bootstrap is much simpler than writing custom CSS from scratch:

```html
<button class="btn btn-primary">Click Me</button>"
```

With just a few predefined classes, the button is already styled, spaced correctly, and responsive. Without a framework, I would need to manually define colors, padding, borders, hover effects, and responsiveness in CSS. Bootstrap handles all of that automatically.

However, the most difficult part of using a UI framework was not building the basic components. It was modifying them. Bootstrap gives you a standard navbar, footer, or layout that works immediately. But our WOD assignments required us to tweak those default components to match specific design requirements. That meant adjusting spacing, removing background images, changing alignment, modifying responsiveness, and sometimes overriding Bootstrap’s own styling rules.

That process was frustrating.

When I tried to change one small thing, sometimes three other things would shift unexpectedly. I had to learn how containers, rows, columns, and breakpoints interacted with each other. I had to understand why certain classes worked together and why others conflicted. It forced me to think beyond “just make it look right” and instead understand the structure behind the framework. In that sense, the frustration was part of the learning process.

My favorite experience with UI frameworks was building a carousel for a website recreation project. The carousel included two images and one video, all sliding automatically on a clean black background. At first, it seemed straightforward. But integrating different types of media into one responsive component required careful structure and attention to detail. I had to think about how the JavaScript behavior worked, how the layout affected the viewing experience, and how to make everything feel smooth and intentional.

<img width="600px" class="rounded float-start pe-4" src="../img/SLSscreenshot1.png">

<img width="600px" class="rounded float-start pe-4" src="../img/SLSscreenshot2.png">

When it finally worked exactly the way I imagined, it was extremely satisfying. That was the moment when I realized I was no longer just copying examples from documentation. I was actually using the framework creatively and confidently.

This leads to an important question: why not just use raw HTML and CSS?

Technically, it is possible to build everything from scratch. However, UI frameworks offer significant software engineering benefits. First, they provide speed. A developer can build a responsive layout in minutes instead of hours. Second, they enforce consistency. Spacing, typography, and alignment follow a predictable system. This becomes especially important when multiple developers work on the same project. A shared framework ensures that everyone follows the same design patterns.

Another benefit is maintainability. Framework components are reusable and standardized. Instead of rewriting styles for every button or navigation bar, developers rely on tested components. This reduces errors and improves scalability as projects grow larger. In professional environments, these benefits are extremely valuable.

That said, UI frameworks do require an investment of time. Memorizing class names, understanding the grid system, debugging layout conflicts, and reading documentation carefully can be challenging. At times, using raw CSS might feel simpler for small projects. But for larger or collaborative work, the structure and consistency of a framework become worth the effort.

Overall, my experience with Bootstrap changed the way I see front-end development. Before learning UI frameworks, I viewed HTML as structure and CSS as decoration. Now I understand that frameworks combine structure, style, and responsiveness into one organized system. They may feel rigid at times, but that structure is what makes them powerful.

I used AI tools to help organize my thoughts and refine the clarity of this essay. However, the reflections and experiences described here are based on my own hands-on work and challenges while learning Bootstrap 5.

In conclusion, UI frameworks are not easy. They can be frustrating and sometimes feel overly detailed. But they provide speed, consistency, maintainability, and professional-level design structure. Learning Bootstrap was challenging, yet incredibly rewarding. The time and frustration invested in understanding UI frameworks ultimately pays off in the ability to build cleaner, more scalable, and more professional websites.
