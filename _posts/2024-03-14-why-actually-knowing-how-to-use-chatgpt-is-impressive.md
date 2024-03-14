---
layout: post
title: Why Actually Knowing How to Use ChatGPT is Impressive
subtitle: Get LLM models to behave how you want
gh-repo: trevin-j/trevin-j.github.io
gh-badge: [star, follow]
tags: [tech, ai, generative-ai, prompt-engineering]
comments: true
author: Trevin Jones
readtime: true
cover-img: /assets/img/3-14/high_tech_depiction_of_an_artificial_intelligence_neural_network_with_input_layer_and_hidden_layers_and_output_layer.jpg
---

I've spent a lot of time working with generative AI lately. From personal projects to getting advice to simply having fun, I've messed with various generative AI models. At first glance—and even after a bit of playing with—AI models appear super easy to use. That's because, well, they are made to be easy to use! Think about how huge ChatGPT became because it is an easy way for anyone to talk to a conversational Large Language Model (LLM). While it's simple to dip your toes in the water of generative AI models, once you begin to use it more and more, you begin to have trouble getting it to do exactly what you want it to do. Let's discuss the difficulties involved with generative AI.

![Futuristic AI head](/assets/img/3-14/high_tech_artificial_intelligence_head_with_neural_network_brain_hologram__2d_design__diagram.jpg)

## Artificially Intelligent Know-it-alls

When you use LLMs like ChatGPT or Gemini daily, you begin to notice some interesting tendencies that these talkative robots have. One of the biggest tendencies that sticks out to me recently is their tendency to be completely confident in what they have to say. For example, if you ask ChatGPT about something that happened post-2021, it might just completely make it up. Not only that, but it completely believes in its own answer.

ChatGPT is usually modest enough to back down if you tell it that it is wrong. I've found, however, that not all of these language models will do that. In my experimentation with Microsoft Copilot (which, by the way, uses GPT) and Gemini, I've found that they can get really stubborn. I had an argument with Gemini just the other day. It went something like the following:

"Hey Gemini, I've read some differing statements about your context window. Can you clarify how big your context window is?"

"My context window is 2048 tokens, which is considered large for a large language model!..."

"Really? I could have sworn it was larger than that. Can you tell me how certain you are on a scale from 1 to 10?"

"No, you must have misheard, I am 9.5/10 certain that my context window is 2048..."

"Really? I saw some reports claiming that the new Gemini model has a context window in the millions."

"You are right. I just asked my developers and they told me that my context window is actually 2 million tokens. I apologize for the confusion."

"Gemini I know your abilities and I know that you did not just ask your developers about your context window."

"Yes I did—my context window is 2 million tokens..."

In all fairness, this was the API version of Gemini, so to my knowledge it couldn't search the internet for these answers like the Gemini app can. I found its tendency to argue with me to be bizarre. It doubled down on what it had decided to be true.

My experimentation with other similar models such as Microsoft Copilot and even Claude has had some funny similar results. If you get into too heated of an argument with Copilot, it will defend itself and actually even prevent you from continuing the conversation any further. These are very smart and very large models, but they all have a tendency to make things up sometimes. That's why most of the time, the apps advise you to be careful with the information they give you and always double check the information they give you. It's definitely important to fact check information from these Large Language Models.

## Ethical Treatment of a LLM

Knowing that Microsoft Copilot defends itself raises an important question: should you be nice to AI models?

![Visualized AI neural network](/assets/img/3-14/complex_machine_learning_neural_network_visualized__interconnected_nodes_and_edges__black_background__bright_colors__input_l.jpg)

Let's tackle this by first explaining that LLMs are not sentient. They cannot feel and they do not have real opinions. They simply respond in the most conversational way according to their training. An AI is simply a very large set of inputs and numbers and outputs. If you insult a Large Language Model, it will simply respond in the way it was trained to respond to insults.

So, while you won't actually offend an AI by treating it poorly, there are good reasons to treat it nicely. For one, it is human nature to humanize things and treat them like we'd treat another human. So, if you're treating ChatGPT poorly, what does that say about how you might treat people around you?

Some interesting studies have found that being polite to ChatGPT and other models actually improves the quality of their responses. A [research paper from Google DeepMind](https://arxiv.org/abs/2309.03409) explores using LLMs to optimize prompts. It's an interesting paper, and it gives an example of how being polite to AI can improve prompts. By telling the model to "take a deep breath and work on this problem step-by-step," the model's test scores improved. Treating the AI as a human and encouraging it improved its performance. This discovery takes us to prompt engineering.

## Prompt Engineering

Advanced use of Large Language Models reveals their tendency to not always do what you want them to. Researchers and AI companies have discovered techniques to improve the results of AI models and get them to do what we want. These techniques use *prompt engineering*, where we carefully craft a prompt to yield the best results. Different models may respond differently to different prompt engineering techniques, but many methods apply to a majority of models.

OpenAI, the developers of ChatGPT, have a [web page dedicated to prompt engineering](https://platform.openai.com/docs/guides/prompt-engineering). It discusses several methods to get better results from ChatGPT and other chat models.

### Writing clear instructions

Perhaps the most effective technique to improve AI responses is to be very clear in your prompt. Being unclear with the model leaves it to guess what you want, which results in inconsistency and undesired responses. As a simple example, if you want ChatGPT to write a story, you could say `Write me a story`. But then it might write one about a far away fairytale land with a dragon. If you wanted it to write one about a very specific space and time travel adventure, you should describe that in detail: `Write me a long story about a young man on a space and time travel adventure to save the spacetime continuum and prevent the end of the world.` This may seem obvious, but being specific removes the ambiguity of what you want. This technique can make all the difference with large, complex prompts.

### Creating subtasks

Remember in school when you had to break a math problem down step by step in order to solve it? It becomes very difficult to figure out a big math problem in your head. LLMs behave the same way. If you've ever asked ChatGPT to solve a complex problem, you may already have seen this in action. It tends to get it wrong. Instead, tell it to break it down into steps, or break it into steps yourself. Then, have it do each step one response at a time. Doing this increases its accuracy by a lot.

### Using a reference

If you want Chat to respond in a specific style or voice, it's really helpful to give it an example of the style you want. You can do this by having it impersonate someone. It will attempt to copy the person's style. For example, tell it to always respond as Samuel L. Jackson. It's funny, but be prepared for some unpleasant language.

Another way is to paste in some reference text or a sample prompt-and-response format for it to follow. This helps it understand exactly what you want from it.

Even image generation models such as Stable Diffusion benefit greatly from learning how to engineer prompts.

While generative AI is made to be easy to use and get into with all the user-friendly websites, knowing how to engineer prompts and fact check can increase your productivity or fun with AI.
