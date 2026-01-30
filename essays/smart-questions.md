---
layout: essay
type: essay
title: "RTFM/STFW"
# All dates must be YYYY-MM-DD format!
date: 2026-01-29
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/smart-questions/rtfm.png">

## There's no such thing as a dumb question

There’s a common saying that “there’s no such thing as a dumb question,” but in the technical world, that isn’t always true. Programmers spend countless hours developing solutions to complex problems, and along the way, it’s normal to encounter roadblocks that are difficult to overcome alone. When that happens, many turn to online communities like Stack Overflow, hoping other users can offer guidance. While getting an answer may seem straightforward, the key to receiving a helpful solution lies in asking the question correctly. Crafting a well-formed question with proper etiquette—demonstrating clarity, preparation, and respect for the community—is essential before anyone will take the time to provide meaningful assistance.

A great example of a “smart question” is the post from Stack Overflow that describes the problems reading large binary data streams from a serial port in Mathematica. The user explains that communication works normally for small data sizes but fails once the stream exceeds roughly 4992 bytes, where the received data becomes truncated. Instead of giving a vague complaint, the writer clearly defines the conditions of failure, the symptoms, and the environment in which the issue occurs. They specify the baud rate, data format, and software version. This allows the readers to understand the situation without having to request any basic clarification. This type of question shows careful consideration and respect for the time of potential responders.

<div class="text-center">
  <img width="300px" class="rounded" src="../img/smart-questions/RaiseHand.jpg">
</div>

The question also stands out because it includes a reproducible test setup. The user built a controlled experiment using an Arduino that sends a predictable sequence of binary values after receiving a size request from Mathematica. Because the data is organized and verifiable, others can easily check whether the same issue occurs on their systems. Also, the writer mentions their prior troubleshooting: they confirm the hardware works with other serial tools, test different buffer sizes, and note that additional reads do not recover missing bytes. This shows that they have already put in effort to diagnose the problem rather than expecting others to do all the work. 

Finally, the tone and framing play a role in making it a smart question. The user does not accuse the software of being broken but instead suggests that the issue “seems specific” to the interface and asks whether there might be a limitation or an error in their own method. This neutral, collaborative approach encourages the knowledgeable users to engage rather than become defensive. This question is precise, testable, and supported by evidence, which aligns with the points of effective technical communication. By combining all these things, such as clarity, preparation, and humility, the writer increases the likelihood that they will receive a useful and respectful response.

On the other hand, an example of a “non-smart” question of the same topic could be one that is vague, assumes the software is at fault, and provides almost zero useful information for someone trying to help. For example, a user might post: “Mathematica serial is broken, I’m trying to read data from my Arduino, and it stops working when the data gets big. Smaller stuff is fine. I think Mathematica has a bug. How do I fix this?” At first, it seems like a call for help, but the body has nearly none of the details needed to diagnose the problem. It does not mention the Mathematica version, baud rate, exact amount of data causing the issue, or even a description of what “stops working” means.

<div class="text-center">
  <img width="300px" class="rounded" src="../img/smart-questions/Facepalm.gif">
</div>

On top of that, non-smart questions do not show any evidence of prior research or testing. The user here doesn’t show whether they tried other serial tools, experimented with buffer sizes, or checked error messages. There is also no code, data, or reproducible example. Asking “How do I fix this?” without providing such details leaves the responder to guess at the problem, which is frustrating and very inefficient. It shows a lack of effort or willingness to understand the system, which is exactly the type of behavior that ends up being ignored or dismissed.

Lastly, non-smart questions usually place the blame prematurely and fail to define the actual problem clearly. By claiming that Mathematica is broken, the user assumes that the whole issue comes from the software instead of considering potential mistakes in their approach. This question is also very general. It contains no specific target or goal for the responder to address. To sum up, non-smart questions are vague, unstructured, and unhelpful, making it unlikely that anyone would choose to invest time in providing a meaningful solution.
