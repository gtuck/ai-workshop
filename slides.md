---
theme: apple-basic
# background: https://cover.sli.dev

# force color schema for the slides, can be 'auto', 'light', or 'dark'
colorSchema: dark

# favicon, can be a local file path or URL
favicon: "https://garthtuck.com/images/favicon.ico"

# some information about your slides (markdown enabled)
title: Getting Started with ChatGPT
class: text-center
layout: center

# author field for exported PDF or PPTX
author: Garth Tuck

# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
---

<style>
h1 {
  background-color: #492365;
  background-image: linear-gradient(45deg, #814d9d 10%, #a275b3 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

# Welcome

<br>

**Getting Started with ChatGPT**

### Presenter:

**Garth Tuck**

---
layout: image-right

image: /title-slide.png
---

# Workshop Goals:

- Understand what generative AI is and how it works  
- Explore real-world examples of how AI already impacts our lives  
- A few milestones in AI history and key AI vocabulary and concepts  
- Practice writing effective prompts to get useful responses from ChatGPT  
- Try hands-on tools and leave with ideas you can apply right away
- ...and **have fun** experimenting

## Workshop Environment:

- Open, inclusive, and curiosity-driven

---
layout: quote
---

# AI in our world

**Where do you think AI might already be helping you in daily life—without you even realizing it?**

---

# A few examples include:

<v-clicks>

1. **📸 Photo Tagging & Face Recognition** Your phone or social media app automatically groups your photos by faces or places—powered by AI.

2. **🔍 Search Suggestions** As you type, search engines guess what you mean based on past searches and trends—thank AI for that.

3. **🧭 GPS & Maps** AI predicts traffic, suggests faster routes, and updates real-time arrival times.

4. **📺 Streaming Recommendations** Netflix, YouTube, Spotify, etc., use AI to suggest shows or songs based on what you've watched or listened to.

5. **📱 Voice Assistants** Siri, Alexa, and Google Assistant recognize speech, interpret commands, and even hold mini conversations.

6. **📝 Autocorrect & Smart Text Prediction** Your phone suggests the next word or fixes typos as you type—that’s AI anticipating your intent.

7. **🌡️ Smart Home Devices** Thermostats like Nest learn your preferences and adjust temperatures automatically to save energy.

</v-clicks>

---
layout: two-cols-header
---

# 15 Milestones in AI History

::left::

<v-clicks>

- **1950 – Turing Test Proposed**<br>Alan Turing proposes a test for machine intelligence based on human-like conversation.

- **1956 – Dartmouth Conference**<br>Term "Artificial Intelligence" coined; birth of AI as a formal field.

- **1958 – LISP Programming Language**<br>John McCarthy creates LISP, the go-to AI language for decades.

- **1966 – ELIZA Chatbot**<br>Simulates a psychotherapist—early success in natural language processing.

</v-clicks>

::right::

<v-clicks>

- **1970s – Expert Systems Rise**<br>Programs like MYCIN show machines can mimic expert decision-making.

- **1987–1993 – AI Winter**<br>Disillusionment and lack of funding slow progress significantly.

- **1997 – Deep Blue Defeats Kasparov**<br>First computer to beat a reigning chess world champion.

- **2002 – Roomba Launches**<br>Consumer AI enters homes with autonomous robot vacuum.

</v-clicks>

---
layout: two-cols-header
---

# 15 Milestones in AI History (cont.)

::left::

<v-clicks>

- **2011 – IBM Watson Wins Jeopardy!**<br>Defeats human champions with deep NLP and fact retrieval.

- **2012 – ImageNet & AlexNet Breakthrough**<br>Deep learning revolution begins with CNNs and visual recognition success.

- **2016 – AlphaGo Beats Lee Sedol**<br>Reinforcement learning and self-play reach new levels of strategy.

- **2020 – GPT-3 Released by OpenAI**<br>Natural language generation reaches astonishing fluency and scale.

</v-clicks>

::right::

<v-clicks>

- **2022 – ChatGPT Goes Mainstream**<br>Conversational AI enters daily use with GPT-powered assistants.

- **2023 – AI-Generated Art and Code Boom**<br>Tools like DALL·E, Copilot, and Midjourney reshape creative and coding work.

- **2024 – GPT-4 Multimodal Release**<br>First major model to understand and generate both text and images with precision.

</v-clicks>

---

# Common AI vocabulary

| **Term**                                 | **What It Means**                                                                                                                  |
| ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| AI (Artificial Intelligence)             | A computer system that can perform tasks usually requiring human intelligence (like understanding language or recognizing images). |
| ML (Machine Learning)                    | A type of AI where computers learn from data and improve over time without being explicitly programmed.                            |
| GPT (Generative Pre-trained Transformer) | A large language model trained on tons of text to predict and generate human-like responses.                                       |
| LLM (Large Language Model)               | A type of AI trained on massive text data to understand and generate human language.                                               |
| Transformer                              | The underlying architecture that powers many modern AI models, including GPT, is known for its "attention" mechanism.              |

---

# Common AI vocabulary (cont.)

| **Term**      | **What It Means**                                                                                                    |
| ------------- | -------------------------------------------------------------------------------------------------------------------- |
| Token         | A piece of a word or character that the AI processes; for example, “chatting” might be split into “chat” and “ting”. |
| Prompt        | The input or question you give to an AI—what you type to start the conversation.                                     |
| Fine-Tuning   | Training a model to be better at specific tasks on a smaller, focused dataset.                                       |
| Training Data | The information (usually lots of text) used to teach the AI how to understand and respond.                           |
| Inference     | The process of the AI generating a response based on your input—it’s “thinking” time for the model.                  |

---

# A few common ways AI is used today

<v-clicks>

1. 💬 **Conversational Assistants**  
   Chatbots like ChatGPT, Google Assistant, and Siri help answer questions and automate tasks.

2. 🎨 **Image and Art Generation**  
   Tools like DALL-E and Midjourney create custom images from simple text prompts.

3. 📈 **Business Productivity**  
   Automate emails, summarize meetings, write reports, and generate marketing content.

4. 🧠 **Education and Tutoring**  
   Personalized explanations, language learning support, and homework help.

5. 🎙️ **Realistic Voice Companions**  
   Platforms like Sesame use expressive AI voices for engaging and humanlike conversations.

</v-clicks>

---
layout: center
---
# <a href="https://www.sesame.com/research/crossing_the_uncanny_valley_of_voice#demo" target="_blank">Conversational voice demo</a>

---

# A few practical ways to use ChatGPT

<v-clicks>

1. 📝 **Draft Emails or Messages**  
   Quickly write polite, professional, or friendly emails and texts.

2. 📅 **Plan Your Day or Week**  
   Ask for a customized daily schedule based on your tasks and preferences.

3. 🍽️ **Meal Planning and Recipes**  
   Get meal ideas based on ingredients you have or dietary needs.

4. 📚 **Explain Complex Topics Simply**  
   Ask for an easy-to-understand explanation of concepts like credit scores or climate change.

5. 🛠️ **Brainstorm Ideas**  
   Generate creative ideas for gifts, events, projects, or side hustles.

</v-clicks>

---
layout: center
---
# <a href="https://chatgpt.com" target="_blank">ChatGBT demo</a>

---

# How to write a good prompt

<v-clicks>

- 🧩 **Be specific**  
  "Tell me a bedtime story about a robot and a cat" vs. "Write a story"

- 🗣️ **Use natural language**  
  Pretend you're talking to a helpful friend, not coding a machine.

- 🎨 **Set the tone**  
  Want it funny? Professional? Thoughtful? Just say so!

- 💡 **Give examples**  
  "Make it sound like a Shakespearean poem" or "List it like a recipe."

- 🔁 **Tweak and test**  
  If the first response isn't great, try rewording or asking from a new angle!

</v-clicks>

---

# For example:

<br>

## ❌ Poor Prompt

"Write something about dogs."
<br>

## ✅ Good Prompt

"Write a friendly and informative 3-paragraph article for a blog about the benefits of owning a dog, focusing on companionship, exercise, and mental health."

---
layout: two-cols-header
---
# Group Activity - Try ChatGPT yourself!

::left::

- On your phone:
  - Scan the QR code to access the free version
- Enter your prompt - Let's start with:
  - "Plan a 3-day road trip through Utah with kids."
  - Now, try changing the destination or group type.
- Share your results with the group

::right::
<img width="375" src="/chatGBT-qr.png" />

---

# Questions?

<img src="/qna-slide.png" />

---
layout: image-left

image: /end-slide.png
---

# Happy trails!

👋🏻 Thanks for your time.

💡 Want more? Visit <a href="https://chat.openai.com" target="_blank">chat.openai.com</a> or scan the QR code again anytime.

<img width="300" src="/chatGBT-qr.png" />
