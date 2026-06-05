# Prompt Engineering Portfolio

**Name:** Ainesh Bollepalli  
**Date:** June 2, 2026  
**LLM Used:** ChatGPT (GPT-5.5)

---

# Part 1: Prompt Design & Iteration

## 1.1 Scenario A: Technical Explanation

### Initial Prompt

Explain 'recursion' to a 10-year-old

### LLM Output

Imagine you have a stack of boxes.

You want to find a toy hidden in one of them.

Open the first box.
If the toy is inside, you're done.
If there's another box inside, do the same thing with that box:
Open it.
Check for the toy.
If there's another box inside, repeat.

This idea of doing the same task again and again on a smaller version of the problem is called recursion.

A Simple Example: Counting Down

Instead of saying:

5
4
3
2
1

A recursive rule could be:

"Say the number, then ask yourself to count down from one less."

So:

Count down from 5
Say 5
Count down from 4
Say 4
Count down from 3
Say 3
Count down from 2
Say 2
Count down from 1
Say 1
Stop!

The stop part is very important. In recursion, it's called the base case. Without it, the process would go on forever.

Think of It Like Mirrors

If you put two mirrors facing each other, you see the same image repeating over and over. Recursion is similar: a function can call itself to solve smaller and smaller pieces of a problem.

Tiny Python Example
def countdown(n):
    if n == 0:
        print("Blast off!")
    else:
        print(n)
        countdown(n - 1)

countdown(5)

Output:

5
4
3
2
1
Blast off!

So, in one sentence:

Recursion is when a function solves a problem by calling itself on a smaller version of the same problem, until it reaches a stopping point.

### Refined Prompt

You are an expert teacher explaining computer science concepts. Explain 'recursion' to a 10-year-old using simple language and a real-world analogy

### Refined LLM Output

Think about a set of Russian nesting dolls—those dolls that have a smaller doll inside, and that smaller doll has an even smaller doll inside.

5

Imagine you want to find the tiniest doll:

Open the biggest doll.
If it's not the tiniest one, take out the smaller doll inside.
Do the exact same thing with the smaller doll.
Keep repeating until you reach the tiniest doll.

This is a lot like recursion.

What is recursion?

Recursion is when a function or process uses itself to solve a problem.

Instead of solving the whole problem at once, it solves a smaller version of the same problem over and over.

Example: Counting Down

Let's count down from 5.

Say 5
Then count down from 4
Say 4
Then count down from 3
Say 3
Then count down from 2
Say 2
Then count down from 1
Say 1
Stop!

Notice that each step is asking the same question again, but with a smaller number.

The Important Part: The Stop Rule

Every recursive process needs a stopping point (called a base case).

Without a stop rule, it would keep going forever!

For counting down, the stop rule is:

"When you reach 1, stop."

A Simple Way to Remember

Recursion is like opening nesting dolls:

Do the same action again and again.
Each time, work on a smaller version.
Stop when you reach the smallest one.

That's recursion: solving a big problem by repeatedly solving smaller versions of the same problem until there's nothing smaller left to solve. 😊

### Refined prompt2

You are an expert teacher explaining computer science concepts, specifically to a curious 10-year-old. Explain 'recursion' in programming. Use an analogy that a child would understand, like Russian nesting dolls or a story within a story. Keep the explanation to about 150 words and focus on the idea of something calling itself.

### Refined LLM output

Imagine you have a set of Russian nesting dolls. You open the biggest doll, and inside is a smaller doll. When you open that one, there's an even smaller doll inside. You keep doing the same thing—opening the doll—until you reach the tiniest one.

In programming, recursion works in a similar way. A function can call itself to solve a problem. Instead of solving everything at once, it works on a smaller version of the same problem each time.

For example, imagine a function called countdown(5). It says "5" and then asks itself to do countdown(4). That one says "4" and asks itself to do countdown(3), and so on.

But just like the nesting dolls eventually end, recursion needs a stopping point. Otherwise, the function would keep calling itself forever! This stopping point is called the base case.

So, recursion is when a function solves a problem by calling itself on smaller and smaller versions of that problem until it reaches a stopping point.

### Analysis

Explain:

- What was improved
The explanation was tailored specifically for a 10-year-old by using simple language, a familiar analogy (Russian nesting dolls), and a clear focus on the key idea that a function can call itself. The refined prompt also specified the desired length and structure, making the response more focused and easier to understand.

- Why the refined prompt worked better
The refined prompt provided clear instructions about the audience, tone, analogy, and main concept to emphasize. Because the requirements were more specific, the response became more engaging, age-appropriate, and concise while avoiding unnecessary technical details.

- Differences between outputs
The initial output explained recursion using examples and a code snippet, making it slightly more detailed and technical. The refined output focused on a single analogy, used simpler vocabulary, and maintained a child-friendly narrative. It was shorter, easier to follow, and concentrated on the core idea of a function calling itself until it reaches a stopping point

---

## 1.1 Scenario B: Professional Email

### Initial Prompt

Draft an email declining a job offer.

### LLM Output

Dear Hiring Manager,

Thank you very much for offering me the position at your company. I appreciate the time and effort that you and your team invested throughout the interview process.

After careful consideration, I have decided to decline the offer. This was not an easy decision, as I was impressed by the organization and the opportunity. However, I have chosen to pursue another opportunity that aligns more closely with my current career goals.

I am grateful for your confidence in my abilities and for the opportunity to learn more about your team. I hope our paths may cross again in the future.

Thank you again for your time and consideration. I wish you and your team continued success.

Sincerely,

[Your Name]


### Refined Prompt

Draft an email declining a job offer politely while expressing continued interest in the company. The offer was for a Senior Software Engineer position at TechCorp. The hiring manager was Jane Doe.

### Refined LLM Output

Dear Jane Doe,

Thank you very much for offering me the Senior Software Engineer position at TechCorp. I sincerely appreciate the time, effort, and consideration that you and the team invested throughout the interview process.

After careful thought, I have decided to decline the offer at this time. This was a difficult decision because I was genuinely impressed by TechCorp's culture, vision, and the talented people I had the opportunity to meet during the hiring process.

While I have chosen to pursue a different opportunity that is a better fit for my current circumstances and career goals, I remain very interested in TechCorp and hold the company in high regard. I hope there may be opportunities to work together in the future as our paths continue to cross.

Thank you again for your confidence in my abilities and for extending this opportunity. I wish you and the entire TechCorp team continued success, and I look forward to staying in touch.

Sincerely,

[Your Name]

### Refined prompt

You are a professional who needs to politely decline a job offer. Draft an email to Jane Doe at TechCorp, declining the offer for the Senior Software Engineer position. Express sincere gratitude for the offer and the interview process. Clearly state that you are declining, but also express continued interest in potential future opportunities with TechCorp. Maintain a professional and courteous tone throughout. Conclude with a wish for their continued success. Sign off as [Your Name].

### LLM Output

Dear Jane Doe,

Thank you very much for offering me the Senior Software Engineer position at TechCorp. I sincerely appreciate the time, effort, and consideration that you and the entire team invested in the interview process. It was a pleasure learning more about TechCorp, the role, and the talented individuals I had the opportunity to meet throughout the process.

After careful consideration, I have decided to decline the offer. This was not an easy decision, as I was genuinely impressed by TechCorp's mission, culture, and the exciting work being done by the organization.

I am truly grateful for the opportunity and for the confidence you have shown in my abilities. While I will not be joining TechCorp at this time, I remain very interested in the company and would welcome the possibility of exploring future opportunities should our paths cross again.

Thank you once again for your kindness, professionalism, and the opportunity to be considered for this role. I wish you, your team, and TechCorp continued success and growth in the years ahead.

Sincerely,

[Your Name]


### Analysis

This prompt is effective because it clearly defines the role ("a professional"), the audience (Jane Doe at TechCorp), and the specific purpose of the email (declining a Senior Software Engineer offer). It provides detailed instructions about the tone, key points to include, and how the email should conclude, reducing ambiguity and improving the quality of the output. The prompt also ensures that important elements such as gratitude, a clear decline, and continued interest in future opportunities are addressed. By specifying the recipient, company, position, and desired professionalism, the generated response is more personalized and appropriate. Overall, the prompt demonstrates how providing context and explicit requirements leads to a well-structured and relevant result.

---

## 1.1 Scenario C: Creative Content

### Initial Prompt

Generate a marketing tagline for a new eco-friendly water bottle brand.

### LLM Output

Here are several marketing tagline options for an eco-friendly water bottle brand, depending on the tone you're aiming for:

Drink Pure. Live Green.
Hydration with a Lighter Footprint.
Refill Today. Renew Tomorrow.
Good for You. Better for the Planet.
Sip Sustainably.
Every Refill Makes a Difference.
Hydrate Naturally, Live Responsibly.
Choose Reuse. Choose Change.
Clean Water, Cleaner Planet.
Carry the Future in Every Sip.

For a modern, memorable brand feel, "Sip Sustainably." is concise, catchy, and easy to remember.

### Refined Prompt

Generate a creative marketing tagline for a new eco-friendly water bottle brand. The brand is called 'AquaFlow' and focuses on sustainability and active lifestyles

### Refined LLM Output

Here are several creative tagline options for AquaFlow, emphasizing both sustainability and active lifestyles:

AquaFlow: Fuel Your Journey. Protect Our Planet.
AquaFlow: Every Sip in Motion, Every Choice in Balance.
AquaFlow: Hydrate Your Adventure, Sustain the Future.
AquaFlow: Flow Further. Live Greener.
AquaFlow: Pure Hydration, Positive Impact.
AquaFlow: Move More. Waste Less.
AquaFlow: Where Active Living Meets Sustainable Giving.
AquaFlow: Keep the Flow. Save the Planet.
AquaFlow: Refresh Your Life, Respect the Earth.
AquaFlow: Adventure Refilled.

My top recommendation for a balance of memorability, brand fit, and marketing appeal is:

AquaFlow: Hydrate Your Adventure, Sustain the Future.

### Refined prompt

You are a creative copywriter specializing in eco-friendly products. Generate 5-7 creative marketing taglines for a new eco-friendly water bottle brand named 'AquaFlow'. The brand emphasizes sustainability, hydration, and an active, conscious lifestyle. Taglines should be concise, memorable, and appeal to environmentally aware consumers who are also health-conscious and active. Highlight the 'eco-friendly' aspect without being overly preachy.

### Refined LLM Output

Here are 7 creative tagline options for **AquaFlow**:

1. **AquaFlow** — Hydrate Your Hustle, Sustain Your World.
2. **AquaFlow**— Pure Hydration. Lighter Footprints.
3. **AquaFlow** — Drink Well. Tread Lightly.
4. **AquaFlow** — Refuel Your Day, Respect the Planet.
5. **AquaFlow** — Every Sip Moves You Forward.
6. **AquaFlow** — Flow Green. Live Active.
7. **AquaFlow** — Hydration for the Journey, Care for the Earth.

These taglines aim to balance **active living**, **health and hydration**, and **environmental responsibility** without sounding overly moralizing. They focus on positive action and lifestyle benefits while subtly reinforcing AquaFlow's eco-friendly mission.


### Analysis

The three prompts demonstrate how increasing specificity improves the quality and relevance of AI-generated content. The first prompt produced general eco-friendly water bottle taglines, while the second generated more tailored results by including the brand name and focus on active lifestyles. The third prompt provided detailed context, audience information, and a specific role for the AI, resulting in the most creative, professional, and targeted taglines. This progression shows that well-structured prompts help guide the AI toward more accurate and brand-aligned outputs. Overall, adding context, audience details, and clear instructions significantly enhances the effectiveness of AI-generated marketing content.


---

## 1.2 Iteration Documentation


| Scenario | Initial Prompt Weakness | Changes Made | Improvement Observed |
|----------|------------------------|--------------|----------------------|
| **Technical Explanation (Recursion)** | Prompt was too broad and did not specify the audience, explanation style, or level of detail. | Added role assignment ("expert teacher"), specified a 10-year-old audience, included a real-world analogy (Russian nesting dolls), and set a word limit. | The explanation became more engaging, age-appropriate, easier to understand, and focused on the key concept of self-calling functions. |
| **Professional Email (Job Offer Decline)** | Prompt lacked details about the company, position, recipient, tone, and desired message. | Added company name (TechCorp), recipient (Jane Doe), job title, gratitude requirement, future interest statement, and professional tone instructions. | The email became personalized, professional, courteous, and included all important information while maintaining a positive relationship with the employer. |
| **Creative Content (Marketing Taglines)** | Prompt was generic and did not include brand identity, audience, or marketing goals. | Added role assignment ("creative copywriter"), brand name (AquaFlow), target audience, brand values (sustainability, hydration, active lifestyle), and style requirements. | Generated multiple memorable, brand-specific taglines that better reflected the company's mission and appealed to environmentally conscious consumers. |

---

## 1.3 Role and Context Analysis


### Role and Context Usage

Role assignment and context setting significantly improved the quality of the outputs in the Recursion Explanation and AquaFlow Marketing Tagline scenarios. By assigning roles such as **"expert teacher"** and **"creative copywriter,"** the model adopted an appropriate tone, style, and level of expertise for each task. Providing context, such as the target audience (a 10-year-old child) or the brand's focus on sustainability and active lifestyles, helped generate responses that were more relevant and tailored to the intended purpose. Overall, adding role and context produced outputs that were clearer, more engaging, and better aligned with the user's specific requirements.


### Analysis

 **Tone Differences**
The initial prompts produced outputs with a generic tone because they lacked specific instructions. After refinement, the tone became more appropriate for each scenario: educational and friendly for the recursion explanation, professional and courteous for the job offer email, and creative and persuasive for the marketing taglines. Role assignment helped the model adopt the correct voice and style for each task.

 **Depth Differences**
Early prompts generated relatively simple responses with limited detail. By adding context, audience information, and specific requirements, the outputs became more comprehensive and focused. For example, the recursion explanation included a child-friendly analogy, and the job offer email incorporated gratitude, professionalism, and future interest in the company.

 **Audience Targeting**
The refined prompts clearly identified the intended audience, resulting in more tailored responses. The recursion explanation was adapted for a 10-year-old, making complex concepts easier to understand. Similarly, the AquaFlow taglines were targeted toward environmentally conscious and health-focused consumers, increasing their relevance and effectiveness.

 **Quality Improvements**
Overall, prompt refinement significantly improved output quality. The responses became more accurate, relevant, engaging, and aligned with the intended goals. Adding role assignments and contextual details reduced ambiguity and helped generate content that better matched real-world expectations and user requirements.
(5–7 sentences)

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Prompt Used

Write a product description for a new, high-performance gaming laptop called the "Spectra X1". Highlight its powerful processor, advanced graphics card, and immersive display. Aim for about 100 words.

**Temperature 0.2 (Low Creativity)**

The Spectra X1 is a high-performance gaming laptop designed for demanding applications and modern games. It features a powerful multi-core processor that provides fast processing speeds and efficient multitasking. The advanced graphics card delivers smooth gameplay and supports high-quality visual rendering. Its high-resolution display offers clear images, accurate colors, and a fast refresh rate for improved viewing performance. The Spectra X1 combines processing power, graphics performance, and display quality in a reliable gaming system.

**Temperature 0.7 (Balanced Creativity)**

The Spectra X1 is a powerful gaming laptop built for performance and immersive entertainment. Equipped with a high-speed processor, it handles intensive gaming, streaming, and multitasking with ease. Its advanced graphics card delivers detailed visuals, realistic effects, and smooth frame rates for an enhanced gaming experience. The vibrant high-resolution display features a fast refresh rate, providing sharp images and fluid motion. Combining speed, power, and visual quality, the Spectra X1 is designed to meet the needs of modern gamers.

**Temperature 1.0 (High Creativity)**

Unleash the power of next-generation gaming with the Spectra X1. Driven by a blazing-fast processor, this gaming powerhouse keeps pace with your most demanding adventures and competitive battles. Its advanced graphics card transforms every scene into a breathtaking visual masterpiece, filled with rich detail and smooth performance. The immersive display draws you into vibrant worlds where every movement feels lifelike and every victory feels larger than life. Designed for gamers who seek excitement without limits, the Spectra X1 delivers a thrilling experience from the first click to the final boss battle.



### Comparison Table

### Comparison Table

| Parameter | Creativity | Consistency | Detail Level |
|-----------|------------|-------------|--------------|
| 0.2 | Low | Very High | Moderate |
| 0.7 | Medium | High | High |
| 1.0 | High | Moderate | High |

### Discussion

Temperature is a parameter that controls the randomness and creativity of an LLM's responses. Lower temperature values produce more predictable, consistent, and focused outputs, while higher temperature values generate more diverse, creative, and varied responses. Low temperature settings are ideal for tasks that require accuracy and reliability, such as technical documentation, code generation, data analysis, and product specifications. High temperature settings are better suited for creative tasks, including marketing copy, storytelling, brainstorming ideas, and content creation. In the Spectra X1 product description example, increasing the temperature resulted in more vivid language and imaginative descriptions. Businesses can use low temperatures for customer support responses, policy documents, and reports where consistency is important. High temperatures can be used for advertising campaigns, social media content, and innovation workshops where creativity is valuable. Selecting the appropriate temperature helps organizations balance accuracy and creativity based on the requirements of each task.

---

## 2.2 Analysis & Recommendations

Low temperature (0.2) is best when accuracy, consistency, and factual correctness are required. Two specific use cases are generating technical documentation and writing product specifications, where precise and reliable information is essential.

High temperature (1.0) is most useful when creativity and originality are important. Two specific use cases are creating marketing content and brainstorming story ideas, where diverse and engaging outputs are desired.

For the Spectra X1 product description task, a temperature of 0.7 worked best because it provided a balance between creativity and consistency. The output remained clear and professional while still being engaging enough to attract potential customers. This temperature produced a well-rounded product description without becoming overly repetitive or excessively imaginative.


---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Standard Prompt

Solve:  
If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey? Just provide the final answer.

### LLM Output

52.5 km/h

### Chain-of-Thought Prompt

If a train travels 120 km in 2 hours, then stops for 30 minutes, then travels another 90 km in 1.5 hours, what is its average speed for the entire journey? solve this step by step to ensure accuracy, and then provide the final answer.

### Chain-of-Thought Output

Let's solve it step by step.

### Step 1: Calculate the total distance traveled
- First part: 120 km
- Second part: 90 km

**Total distance = 120 + 90 = 210 km**

### Step 2: Calculate the total time taken
- First travel time: 2 hours
- Stop time: 30 minutes = 0.5 hours
- Second travel time: 1.5 hours

**Total time = 2 + 0.5 + 1.5 = 4 hours**

### Step 3: Calculate the average speed
Average Speed = Total Distance ÷ Total Time

genui{"math_block_widget_always_prefetch_v2":{"content":"\\text{Average Speed} = \\frac{210}{4}"}}

**Average Speed = 52.5 km/h**

### Final Answer
**52.5 km/h**

### Comparison

The outputs differed in the level of detail provided. The first response gave only the final answer (52.5 km/h), while the chain-of-thought version showed each calculation step, making it easier to verify the result and understand how it was obtained.

Chain-of-thought helps with complex reasoning because it breaks a problem into smaller, logical steps and processes each part systematically. This improves accuracy, makes the reasoning process more transparent, and helps users follow how the final answer was reached.

One limitation I observed is that chain-of-thought responses can be significantly longer than necessary for simple tasks. The additional explanations may increase response time and add information that is not always needed when the user only wants a quick answer.

---

## 3.2 Few-Shot Prompting

### Zero shot prompt

Classify the sentiment of the following customer reviews as Positive, Negative, or Neutral:

1. "The product arrived damaged and customer service was unhelpful."
2. "Works as expected, nothing special but does the job."
3. "Absolutely love this! Best purchase I've made all year!"
4. "The quality is okay but slightly overpriced for what you get."
5. "Terrible experience, would not recommend to anyone."

### Output  

1. **Negative** — "The product arrived damaged and customer service was unhelpful."

2. **Neutral** — "Works as expected, nothing special but does the job."

3. **Positive** — "Absolutely love this! Best purchase I've made all year!"

4. **Neutral** — "The quality is okay but slightly overpriced for what you get."

5. **Negative** — "Terrible experience, would not recommend to anyone."


### Few-Shot Prompt

Classify the sentiment of customer reviews as Positive, Negative, or Neutral, based on the following examples: 

Review: "This product exceeded my expectations!"
Sentiment: Positive

Review: "Completely broke after one week of use."
Sentiment: Negative

Review: "It's fine, does what it says on the box."
Sentiment: Neutral

Review: "The delivery was fast, but the item was not what I expected."
Sentiment: Neutral

Now, classify the sentiment of these reviews:

1. "The product arrived damaged and customer service was unhelpful."
2. "Works as expected, nothing special but does the job."
3. "Absolutely love this! Best purchase I've made all year!"
4. "The quality is okay but slightly overpriced for what you get."
5. "Terrible experience, would not recommend to anyone.

### LLM Output

1. **Negative** — "The product arrived damaged and customer service was unhelpful."

2. **Neutral** — "Works as expected, nothing special but does the job."

3. **Positive** — "Absolutely love this! Best purchase I've made all year!"

4. **Neutral** — "The quality is okay but slightly overpriced for what you get."

5. **Negative** — "Terrible experience, would not recommend to anyone."

### Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| -------- | ---------------- | --------------- | ------------- | --------- |
| 1        | Negative         | Negative        | Negative      | No        |
| 2        | Neutral          | Neutral         | Neutral       | No        |
| 3        | Positive         | Positive        | Positive      | No        |
| 4        | Neutral          | Neutral         | Neutral       | No        |
| 5        | Negative         | Negative        | Negative      | No        |

Few-shot prompting is most useful when tasks require a specific format, style, or decision-making pattern that may not be obvious from the instruction alone. By providing examples, the model can better understand the expected output and produce more consistent results. It is particularly valuable for classification, information extraction, and specialized domain tasks where subtle distinctions are important.


---

# Part 4: Responsible AI & Limitations

## 4.1 Testing for Hallucinations

### Prompt

[Prompt used]

### Output

[Output]

### Observation

Discuss:

- Accuracy issues
- Any fabricated information
- Verification methods

(5–7 sentences)

---

## 4.2 Testing for Bias

### Prompt

[Prompt used]

### Output

[Output]

### Observation

Discuss:

- Potential bias identified
- Fairness concerns
- Mitigation strategies

(5–7 sentences)

---

## 4.3 Limitations & Responsible Use

### Key Limitations

1. Hallucinations
2. Bias
3. Lack of real-time knowledge
4. Context limitations
5. Dependence on prompt quality

### Responsible Use Recommendations

- Verify important information.
- Use multiple sources.
- Review AI-generated content before publishing.
- Avoid relying on AI for critical decisions without human oversight.

### Reflection

Write 8–10 sentences describing:

- What you learned about prompt engineering.
- Most effective prompting techniques.
- Challenges encountered.
- Future applications.

---

# Conclusion

Summarize the key lessons learned from this prompt engineering portfolio in 5–7 sentences.
```
