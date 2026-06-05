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

### Prompt Without Role

**Prompt:**  
[Prompt]

**Output:**  
[Output]

### Prompt With Role

**Prompt:**  
Act as a senior software engineer and explain cloud computing to a beginner.

**Output:**  
[Output]

### Analysis

Discuss:

- Tone differences
- Depth differences
- Audience targeting
- Quality improvements

(5–7 sentences)

---

# Part 2: Temperature & Parameter Control

## 2.1 Temperature Experimentation

### Prompt Used

"Write a short story about a robot discovering emotions."

### Temperature 0.2 Output

[Output]

### Temperature 0.7 Output

[Output]

### Temperature 1.0 Output

[Output]

### Comparison Table

| Parameter | Creativity | Consistency | Detail Level |
|-----------|------------|-------------|--------------|
| 0.2 | | | |
| 0.7 | | | |
| 1.0 | | | |

---

## 2.2 Analysis & Recommendations

Discuss:

- How temperature affects output
- When to use low temperature
- When to use high temperature
- Business applications

(Minimum 6–8 sentences)

---

# Part 3: Strategic Prompting Techniques

## 3.1 Chain-of-Thought Prompting

### Standard Prompt

Solve:  
"A company sells 120 units at $50 each. Production cost is $30 per unit. Calculate profit."

### Standard Output

[Output]

### Chain-of-Thought Prompt

Solve the problem step-by-step and explain your reasoning.

### Chain-of-Thought Output

[Output]

### Comparison

Discuss:

- Differences in reasoning
- Transparency
- Educational value

(5–7 sentences)

---

## 3.2 Few-Shot Prompting

### Few-Shot Prompt

Example 1:  
Customer: My order is late.  
Response: I apologize for the delay. Let me check the status for you.

Example 2:  
Customer: I received a damaged product.  
Response: I'm sorry to hear that. We can arrange a replacement immediately.

Customer:  
I was charged twice for my purchase.

Response:

### LLM Output

[Output]

### Analysis

Explain:

- How examples influenced behavior
- Benefits of few-shot prompting
- Real-world use cases

(5–7 sentences)

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
