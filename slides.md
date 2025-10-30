---
theme: apple-basic
# background: https://cover.sli.dev
# force color schema for the slides, can be 'auto', 'light', or 'dark'
colorSchema: light
# favicon, can be a local file path or URL
favicon: "https://garthtuck.com/images/favicon.ico"
# some information about your slides (markdown enabled)
title: Getting Started with AI
class: text-center
layout: center
# author field for exported PDF or PPTX
author: Garth Tuck
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# download: true
# exportFilename: Garth-Tuck-AI-Workshop
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

**Getting Started with AI**

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

---
layout: image-right
image: /genai.png
---

# What is Generative AI?

**Generative AI** is a type of artificial intelligence that can create **new content** — like text, images, music, or code — based on patterns it learned from **existing data**.

Think of it like this:
- You give it a **prompt** (a question or instruction).
- It analyzes tons of examples it's seen before.
- It produces something **new** that matches what you asked for.

**Example:**
"Write a friendly email to reschedule my meeting."
→ ChatGPT writes a polite message for you.

---
layout: two-cols
---

# How Does It Work?

::: left

**Training**

AI models are trained on massive datasets (books, websites, code, images) to learn patterns, grammar, facts, and styles.

**Pattern Recognition**

When you ask a question, the AI doesn't "think" like a person.

It predicts the most likely next word, sentence, or image based on patterns.

:::

::: right

**No Memory**

AI doesn't remember past conversations (unless in the same chat session). It responds based on what you just asked.

**Not Perfect**

AI can make mistakes, give outdated info, or "hallucinate" (make up facts that sound true but aren't).

:::

---

# Real-World Examples

<v-clicks>

- **Customer Service** – AI chatbots answer questions 24/7.
- **Writing Assistance** – Tools like Grammarly or ChatGPT help draft emails, reports, or essays.
- **Creative Work** – Generate images (DALL·E), music, or video scripts.
- **Coding** – GitHub Copilot suggests code as you type.
- **Healthcare** – AI helps analyze medical images or suggest diagnoses.
- **Education** – Personalized tutoring and instant homework help.

</v-clicks>

---
layout: two-cols
---

# A Brief History of AI

::: left

**1950s**

Alan Turing asks, "Can machines think?" The **Turing Test** is born.

**1997**

IBM's **Deep Blue** beats world chess champion Garry Kasparov.

**2011**

IBM's **Watson** wins *Jeopardy!* against human champions.

:::

::: right

**2016**

**AlphaGo** (by DeepMind) beats the world Go champion.

**2020**

**GPT-3** (by OpenAI) shows advanced language understanding.

**2022**

**ChatGPT** launches and goes viral, reaching 100M users in 2 months.

:::

---

# Key AI Vocabulary

<v-clicks>

- **AI (Artificial Intelligence)** – Machines that perform tasks requiring human-like intelligence.
- **Machine Learning** – AI systems that learn from data instead of being explicitly programmed.
- **Neural Network** – A computer system modeled after the human brain.
- **Natural Language Processing (NLP)** – AI that understands and generates human language.
- **Prompt** – The instruction or question you give an AI.
- **Hallucination** – When AI confidently generates false information.
- **Token** – A chunk of text the AI processes (roughly a word or part of a word).

</v-clicks>

---
layout: image-right
image: /ai-interaction.png
---

# How to Interact with AI

**Be Clear and Specific**

❌ "Tell me about dogs."
✅ "Write a 3-paragraph article about how dogs improve mental health."

**Give Context**

"I'm a college student. Explain blockchain like I'm new to technology."

**Use Examples**

"Write a thank-you note like this: [example]."

**Ask Follow-Ups**

"Make it shorter." or "Add more details about the benefits."

---

# Types of Prompts

<v-clicks>

**Informational**
"What are the benefits of meditation?"

**Instructional**
"Write a grocery list for a week of healthy meals."

**Creative**
"Write a funny story about a cat who thinks it's a dog."

**Problem-Solving**
"I have $500 and 3 days. Plan a road trip from Denver to Moab."

**Conversational**
"What's a good gift for my mom who loves gardening?"

</v-clicks>

---

# Writing Effective Prompts

<v-clicks>

**Be Specific**

"Write a blog post" → "Write a 500-word blog post about remote work benefits for Gen Z."

**Set the Tone**

"Write a professional email" vs. "Write a casual, friendly email."

**Define the Format**

"Give me a bulleted list" or "Write it as a poem."

**Provide Constraints**

"Explain this in 3 sentences" or "Use simple language for a 5th grader."

</v-clicks>

---
layout: two-cols
---

# Prompt Example Breakdown

::: left

**Weak Prompt:**

"Write about dogs."

**Problems:**
- Too vague
- No clear goal
- No audience or tone

:::

::: right

**Strong Prompt:**

"Write a friendly and informative 3-paragraph article for a blog about the benefits of owning a dog, focusing on companionship, exercise, and mental health."

**Why It Works:**
- Clear purpose (blog article)
- Specific length (3 paragraphs)
- Defined topics (companionship, exercise, mental health)
- Tone set (friendly, informative)

:::

---

# Example: Weak vs. Strong Prompt

❌ **Weak:**
"Tell me about AI."

✅ **Strong:**
"Explain how AI chatbots work in 3 sentences, using simple language for someone who's never used AI before."

---

❌ **Weak:**
"Help me write an email."

✅ **Strong:**
"Write a polite email to my professor asking to reschedule my meeting from Thursday to Friday because of a doctor's appointment."

---

# Example Output: Strong Prompt

**Prompt:**

"Write a friendly and informative 3-paragraph article for a blog about the benefits of owning a dog, focusing on companionship, exercise, and mental health."

---

# Prompt Ideas You Can Try Right Now

<v-clicks>

1. ✉️ Write a polite message to reschedule my dentist appointment.
2. 🧑‍🍳 Give me a 3-day healthy meal plan with simple recipes.
3. 🧠 Explain how interest rates work like I'm in 9th grade.
4. 🧳 Suggest a weekend getaway near [a city] under $300.
5. 🎁 What's a fun birthday gift idea for a 12-year-old who loves space?
6. 🐶 Write a funny haiku about a dog who's afraid of squirrels.

</v-clicks>

---
layout: two-cols-header
---

# Group Activity - Try ChatGPT yourself!

::: left

- **<u>Timebox: 10 minutes</u>**
- On your phone or a shared device:
  - Scan the QR code to open chatgpt.com →
- **<u>Enter your prompt:</u>**
  - Example: Plan a 3-day Southern Utah road trip with kids (ages, 12, 9. 6).
  - Now, try changing the destination or group type.
- No smartphone? Pair with a neighbor.
- Share your results with the group (2–3 volunteers)

:::

::: right

<img width="300" src="/chatGPT-qr.png" alt="QR code linking to chatgpt.com" />

:::

---

# Major AI Providers

<div class="grid grid-cols-2 gap-8 items-center justify-items-center mt-8">
  <div class="text-center">
    <img src="https://www.gstatic.com/lamda/images/gemini_sparkle_v002_d4735304ff6292a690345.svg" alt="Google Gemini" class="h-20 mx-auto mb-2" />
    <p class="font-semibold">Google Gemini</p>
  </div>
  <div class="text-center">
    <img src="https://www.perplexity.ai/favicon.svg" alt="Perplexity" class="h-20 mx-auto mb-2" />
    <p class="font-semibold">Perplexity</p>
  </div>
  <div class="text-center">
    <img src="https://cdn.oaistatic.com/_next/static/media/apple-touch-icon.82af6fe1.png" alt="OpenAI ChatGPT" class="h-20 mx-auto mb-2" />
    <p class="font-semibold">OpenAI ChatGPT</p>
  </div>
  <div class="text-center">
    <img src="https://claude.ai/images/claude_app_icon.png" alt="Anthropic Claude" class="h-20 mx-auto mb-2" />
    <p class="font-semibold">Anthropic Claude</p>
  </div>
</div>

---

# Questions?

<img width="600" src="/qna-slide.png" alt="Questions and answers illustration" />

---
layout: image-left
image: end-slide.png
---

# Happy trails!

👋🏻 Thanks for your time.

💡 Want more? Visit <a href="https://chatgpt.com" target="_blank">chatgpt.com</a> or scan the QR code again anytime.

<img width="300" src="/chatGPT-qr.png" alt="QR code linking to chatgpt.com" />
