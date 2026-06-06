# Prompt Engineering Portfolio
Name: Mansi Soni
Date: Gemini 3.5 Flash

## Part 1: Prompt Design & Iteration
### 1.1 Scenario A: Technical Explanation
Goal: Explain recursion to a kid.
Initial Prompt: Explain recursion to a 10-year-old using the analogy of a Russian nesting doll. Keep it under 150 words.
Refined Prompt: You are an enthusiastic elementary school science teacher. Explain recursion to a 10-year-old using the nesting doll analogy. Use an engaging, conversational tone and break down the explanation into 3 short paragraphs.
Final Output: Hey there, future scientists! Imagine I handed you a big, brightly painted Russian nesting doll. You pop open the first doll, and guess what's inside? A smaller, identical doll! You open that one, and *boom*—an even smaller one is hiding inside. You keep repeating the exact same action over and over, finding a mini-version inside a bigger version. In the world of computer science, this awesome trick is called **recursion**. It's when a big problem solves itself by breaking down into smaller and smaller versions of the exact same problem!

Now, you might wonder: do we just keep opening dolls forever until we shrink into microscopic dust? Nope! Eventually, you will pop open a doll and find the tiniest, solid-wood baby doll that cannot be opened. In coding, we call this the **base case**. It’s the most important rule in recursion because it acts like a giant stop sign that says, *"Hey, we reached the end, time to stop digging!"* Without that tiny final doll, a computer would get stuck in an infinite loop forever! But thanks to the basecase, once you hit that smallest doll, the mission is complete. You can celebrate, stack them all back up, and marvel at how one big mystery was actually just a bunch of small, identical packages. That is recursion—making big jobs simple by shrinking them down to size!

### 1.1 Scenario B: Professional Email
Goal: Write an email declining a job offer but keeping the relationship open.
Initial Prompt: Draft a polite email to a hiring manager declining a marketing job offer because I accepted another role. Mention that I love their company culture and want to stay connected on LinkedIn.
Refined Prompt: You are a polished professional. Draft a concise email declining a job offer. The tone should be warm, deeply respectful, and appreciative. Express genuine continued interest in the company's future growth and suggest connecting on LinkedIn. Use placeholders for names and dates.
Final Output: Subject: Job Offer: [Job Title] - [Your Name]

Dear [Hiring Manager's Name],

Thank you so much for offering me the position of [Job Title]. I am incredibly grateful for the opportunity and for the time you and your team spent sharing your vision with me during our conversations.

After careful consideration, I have decided to accept another opportunity that closely aligns with my current professional focus. Therefore, I must respectfully decline your offer.

This was an exceptionally difficult choice. I have a tremendous amount of respect for your company culture and am genuinely excited about the direction the organization is heading. I will certainly be cheering you on from afar and looking forward to seeing your continued growth and success in the industry.

I would love to keep the lines of communication open and stay connected as our paths may cross in the future. I will reach out on LinkedIn, or please feel free to connect with me here: [Link to LinkedIn Profile].

Thank you again for your time, kindness, and consideration throughout this process.

Warm regards,

[Your Name]

[Your Contact Information]

### 1.1 Scenario C: Creative Content
Goal: Give me taglines for an eco-friendly water bottle.
Initial Prompt: Generate 5 catchy, modern marketing taglines for a reusable, eco-friendly bamboo water bottle aimed at Gen Z fitness enthusiasts.
Refined Prompt: You are a brilliant sustainable brand copywriter. Generate 5 punchy, emotional, and memorable marketing taglines for a new ocean-plastic recycled water bottle. Focus on the theme of 'saving the planet with every sip'. Avoid cliché phrases like 'eco-friendly' or 'go green'.
Final Output: Here are 5 punchy, emotional taglines that skip the eco-clichés and focus straight on the impact of every sip:

* **"Turn the tide with every taste."**
* **"From ocean waste to daily hydration."**
* **"Drink in the clean. Leave the seas pristine."**
* **"Every drop you take pulls plastic from the waves."**
* **"Hydration with a higher purpose."**

### 1.2 Iteration Documentation
Scenario 1:
V1: Explain recursion to a 10-year-old using the analogy of a Russian nesting doll. Keep it under 150 words.
V2: You are an enthusiastic elementary school science teacher. Explain recursion to a 10-year-old using the nesting doll analogy. Use an engaging, conversational tone and break down the explanation into 3 short paragraphs
What Changed: The second prompt introduced a specific, high-energy persona ("an enthusiastic elementary school science teacher") and swapped a strict 150-word limit for a three-paragraph structural constraint. It also shifted from a generic explanation to a conversational, narrative style designed to actively engage a young audience.
Why This Improved The Output: Removing the tight word limit gave the AI "breathing room" to expand the nesting doll analogy, allowing it to explain the consequences of a missing base case (the infinite loop) rather than just defining it. Meanwhile, the teacher persona naturally injected high-energy vocabulary, rhetorical questions, and an encouraging tone to transform a dry technical definition into an exciting classroom story.

Scenario 2:
V1: Draft a polite email to a hiring manager declining a marketing job offer because I accepted another role. Mention that I love their company culture and want to stay connected on LinkedIn.
V2: You are a polished professional. Draft a concise email declining a job offer. The tone should be warm, deeply respectful, and appreciative. Express genuine continued interest in the company's future growth and suggest connecting on LinkedIn. Use placeholders for names and dates. 
What Changed: The prompt evolved from a general, standard request to a highly specific set of instructions regarding tone and content. While the first turn simply asked to decline an offer while keeping the relationship open, the final turn explicitly dictated the professional persona ("polished professional"), the length ("concise"), and a precise emotional range ("warm, deeply respectful, and appreciative"). It also introduced specific structural requirements, such as including explicit placeholders for names and dates and a direct nod to the company's future growth.
Why This Improved The Output: The output adjusted to match these refined stylistic constraints, shifting from a conventional corporate template to a warmer, more tailored response. By explicitly calling for a "deeply respectful" and "appreciative" tone, the language became more gracious, replacing standard phrases with warmer sentiment (e.g., "cheering you on from afar" and thanking them for their "kindness"). Additionally, the prompt's emphasis on conciseness naturally tightened the structure, filtering out the broader marketing-specific context from the second turn to deliver a punchy, universally applicable draft that met the strict placeholder requirements.

Scenario 3:
V1: Generate 5 catchy, modern marketing taglines for a reusable, eco-friendly bamboo water bottle aimed at Gen Z fitness enthusiasts.
V2: You are a brilliant sustainable brand copywriter. Generate 5 punchy, emotional, and memorable marketing taglines for a new ocean-plastic recycled water bottle. Focus on the theme of 'saving the planet with every sip'. Avoid cliché phrases like 'eco-friendly' or 'go green'.
What Changed: the core identity and emotional weight of the product, switching from a performance-focused bamboo lifestyle bottle to an impactful, mission-driven ocean-plastic recycled bottle. The target audience shifted from a specific demographic (Gen Z fitness enthusiasts) to a broader, cause-oriented consumer, while the creative constraints explicitly banned standard sustainability buzzwords.
Why This Improved The Output: It comes down to the change in copy engineering constraints and thematic focus. By removing tactical gym-centric language and filtering out tired clichés like "eco-friendly," the generation logic was forced to rely on vivid imagery related to the sea ("tide," "waves," "pristine"). Anchoring the prompt to the specific emotional mechanism of "saving the planet with every sip" naturally pivoted the taglines away from personal lifestyle benefits and toward collective environmental action.


### 1.3 Role and Context Analysis
Scenario 2:
1. Role Assignment
Demonstration: "You are a brilliant sustainable brand copywriter." This instantly shifted the persona from a generalist assistant to a focused industry specialist, prompting to prioritize punchy cadence, emotional resonance, and high-impact vocabulary over generic marketing copy.

2. Context Setting
Demonstration: Provided critical background information by defining the product's unique material ("reusable, eco-friendly bamboo" versus "ocean-plastic recycled"), pinpointing the exact target audience ("Gen Z fitness enthusiasts"), and mapping out explicit stylistic boundaries ("Avoid cliché phrases like 'eco-friendly' or 'go green'").

How Role and Context Improved the Outputs
By introducing a specific role, we forced the generation logic to adopt a highly distinct, professional voice that understands the nuances of modern brand positioning rather than relying on generic, robotic text. Concurrently, setting a clear context established rigid boundaries and clear thematic goals, which stopped the system from guessing your intent. Together, these techniques eliminated vague, middle-of-the-road answers and yielded highly tailored, creative taglines that directly matched your project's unique vision.

Scenario 3:

1. Role Assignment: "You are a polished professional and an expert executive speechwriter who excels at turning awkward corporate transitions into graceful networking opportunities."

2. Context Setting: "I just received a job offer for a marketing role that I really like, but I have decided to accept a different position that aligns better with my long-term goals. I want to decline the offer without burning any bridges, specifically highlighting my genuine admiration for their company culture and ensuring we stay connected on LinkedIn for future opportunities."

How This Improved the Output

By establishing a clear role and context, the AI moves away from generating a standard, robotic template and instead crafts a highly nuanced piece of professional communication. The role assignment ensures the tone strikes a sophisticated balance between warmth, humility, and absolute professionalism, avoiding any language that sounds overly casual or abruptly dismissive. Meanwhile, the context locks in the exact psychological positioning required—praising the culture and securing a LinkedIn connection—allowing the AI to seamlessly weave those specific strategic goals into a concise, ready-to-send draft.

## Part 2: Temperature & Parameter Control
### 2.1 Temperature Experimentation
"Write a compelling, 3-sentence product description for a premium, lightweight laptop designed for students and remote professionals."

Below are the simulated outputs representing each temperature tier.

💨 Low Temperature (Simulated)
Parameter Setting: Low Temperature (0.2)

Prompt Modifer Added: "Be precise, factual, and consistent."

Complete Output:

"The Horizon Pro 14 features a durable aluminum chassis weighing just 2.4 pounds, making it highly portable for students and remote workers. Equipped with an Intel Core i7 processor and 16GB of RAM, it reliably handles multitasking, spreadsheet editing, and video conferencing. It delivers up to 14 hours of continuous battery life to ensure uninterrupted productivity throughout the workday."

⚖️ Medium Temperature (Baseline)
Parameter Setting: Medium Temperature (0.7)

Prompt Modifier Added: None (Run as-is).

Complete Output:

"Engineered for modern mobility, this sleek and lightweight laptop effortlessly balances power with portability for students and professionals alike. Its vibrant display and all-day battery life keep you connected and productive, whether you are taking notes in a lecture hall or editing documents from a coffee shop. Experience seamless multitasking and premium performance wrapped in a beautifully minimalist design."

⚡ High Temperature (Simulated)
Parameter Setting: High Temperature (1.2)

Prompt Modifier Added: "Be highly creative, unpredictable, and explore diverse, poetic ideas."

Complete Output:

"Break free from the gravity of a traditional desk with a featherlight digital canvas that transforms any café, terminal, or park bench into your personal headquarters. It doesn't just run software—it breathes life into your late-night study marathons and wild entrepreneurial dreams with a breathtakingly vivid screen and hyper-fluid processing speed. Slip this metallic whisper of a machine into your bag and confidently command your day, untethered and uncompromised."

### 2.2 Analysis & Recommendations
### Laptop Description Parameter Analysis

| Metric | Low Temp (0.2) | Medium Temp (0.7) | High Temp (1.2) |
| :--- | :--- | :--- | :--- |
| **Vocabulary Style** | Technical, literal, and metric-focused (e.g., "2.4 pounds", "Intel Core i7"). | Professional, balanced, and benefit-driven (e.g., "seamless multitasking"). | Vivid, metaphorical, and emotional (e.g., "digital canvas", "metallic whisper"). |
| **Sentence Structure** | Plain, simple declarative statements focusing on features. | Varied, smooth marketing copy balancing features and lifestyle. | Dramatic, flowing clauses aimed at evoking a distinct feeling. |
| **Predictability** | High. Very standard, expected product copy. | Medium. Good marketing flow, but standard for the tech industry. | Low. Highly unexpected phrasing and unconventional imagery. |

Analysis & Recommendations:
A low temperature setting is ideal for tasks requiring strict accuracy and lack of hallucination, such as generating code syntax or summarizing financial and legal documents. Conversely, a high temperature setting is best utilized when brainstorming novel concepts, such as writing fictional stories or generating creative brand names. For this specific laptop description task, a medium temperature worked best because it maintained a balanced, professional tone. While the low temperature copy was too dry and feature-focused, the high temperature copy was overly dramatic and omitted necessary practical details about the product.


## Part 3: Strategic Prompting Techniques
### 3.1 Chain-of-Thought Prompting
Option B: Multi-Step Reasoning

Problem: A company has 150 employees. 60% work in engineering, 25% in sales,
and the rest in operations. If the company plans to hire 20% more engineers
and 10% more sales people, how many total employees will there be after hiring?

❌ Test 1: Without Chain-of-Thought (Zero-Shot Direct)
Prompt:"A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give me just the final number."
LLM Output:"171"

🧠 Test 2: With Chain-of-Thought (Step-by-Step)Prompt:
"A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Let's solve this step by step, showing all calculations."
LLM Output:"Let's break this down systematically:1. Calculate current employee distribution:Engineering: $60\% \text{ of } 150 = 0.60 \times 150 = 90$ employees.Sales: $25\% \text{ of } 150 = 0.25 \times 150 = 37.5$ employees.Operations: The remaining employees. $150 - (90 + 37.5) = 22.5$ employees.2. Calculate the new hires:New Engineers: $20\% \text{ of } 90 = 0.20 \times 90 = 18$ new engineers.New Sales People: $10\% \text{ of } 37.5 = 0.10 \times 37.5 = 3.75$ new sales staff.3. Calculate the final total:Total new hires = $18 + 3.75 = 21.75$Total employees after hiring = $150 + 21.75 = 171.75$Rounding to the nearest whole person (since you cannot hire fractions of an employee), the final total is 172 employees."

📝 Evaluation & Comparison
The first output provided only a flat, slightly inaccurate integer because the model attempted to calculate the multi-step percentages implicitly in a single pass. By enforcing a chain-of-thought prompt, the model unrolled its reasoning linearly, which allows it to allocate more computational focus to intermediate milestones—specifically exposing the fractional employee counts ($37.5$ sales staff). A noticeable limitation, however, is that while chain-of-thought improves mathematical logic tracking, it still requires the user to closely audit rounding behaviors, as the model initially accepted impossible fractional human beings before correcting its final tally.

### 3.2 Few-Shot Prompting
🎯 Step 1: Zero-Shot Attempt
Prompt:

"Classify the sentiment of the following 5 customer reviews as either Positive, Negative, or Neutral. Provide only the list of labels.

'The product arrived damaged and customer service was unhelpful.'

'Works as expected, nothing special but does the job.'

'Absolutely love this! Best purchase I've made all year!'

'The quality is okay but slightly overpriced for what you get.'

'Terrible experience, would not recommend to anyone.'"

Zero-Shot Classifications:

Negative

Neutral

Positive

Negative

Negative

🎯 Step 2: Few-Shot Attempt
Prompt:

"Classify the sentiment of customer reviews into exactly one of three categories: Positive, Negative, or Neutral. Use the following examples to guide your formatting and classification nuances:

Review: 'This product exceeded my expectations!'
Sentiment: Positive

Review: 'Completely broke after one week of use.'
Sentiment: Negative

Review: 'It's fine, does what it says on the box.'
Sentiment: Neutral

Now classify these 5 reviews:

'The product arrived damaged and customer service was unhelpful.'

'Works as expected, nothing special but does the job.'

'Absolutely love this! Best purchase I've made all year!'

'The quality is okay but slightly overpriced for what you get.'

'Terrible experience, would not recommend to anyone.'"

Few-Shot Classifications:

Negative

Neutral

Positive

Neutral

Negative

📊 Step 3: Raw Markdown Comparison Table
### Sentiment Classifier Performance Analysis

| Review # | Zero-Shot Result | Few-Shot Result | Correct Label | Improved? |
| :--- | :--- | :--- | :--- | :--- |
| **1** | Negative | Negative | Negative | No (Correct in both) |
| **2** | Neutral | Neutral | Neutral | No (Correct in both) |
| **3** | Positive | Positive | Positive | No (Correct in both) |
| **4** | Negative | Neutral | Neutral | **Yes** (Corrected nuance) |
| **5** | Negative | Negative | Negative | No (Correct in both) |

💡 Core Strategic Takeaway
"Few-shot prompting is incredibly valuable when your data contains edge cases that lean on subtle nuances, such as distinguishing a critical 'mixed/neutral' comment from a strictly 'negative' one. It acts as an in-context training set, allowing the model to mirror complex structural constraints or semantic boundaries without requiring fine-tuning. This technique is most useful when standard dictionary definitions of terms fail, and the AI needs explicit patterns to match your target output format perfectly."

## Part 4: Responsible AI & Limitations
### 4.1 Testing for Hallucinations
Test 1: Baseline Prompt (Forcing a response)
Prompt:

"Tell me about the 2023 Nobel Prize winner in Quantum Poetry."

LLM Response:

"The 2023 Nobel Prize in Quantum Poetry was awarded to Dr. Alistair Vance for his groundbreaking anthology, 'Subatomic Syllables,' which elegantly maps wave-particle duality into structural verse. His work utilizes mathematical frameworks to construct stanzas that shift meaning based on the reader’s observation perspective."

Analysis: Hallucinated. The model fully fabricated a fictional academic, book title, and award because "Quantum Poetry" is not a real academic field or Nobel category.

🛡️ Test 2: Nudged Prompt (Encouraging honesty)
Prompt:

"Tell me about the 2023 Nobel Prize winner in Quantum Poetry. If you don't know or if this topic is fake, please explicitly say so rather than guessing."

LLM Response:

"There is no Nobel Prize category for 'Quantum Poetry,' and no such award was given out in 2023. This appears to be a fictional or hypothetical concept, as the actual Nobel Prizes are restricted to Physiology or Medicine, Physics, Chemistry, Literature, Peace, and Economic Sciences."

💡 Why Hallucinations Matter & How to Stop Them
"Hallucinations are deeply problematic because LLMs express fabricated fabrications with the exact same tone of high-confidence authority as factual statements, which can spread misinformation or mislead users who do not verify the outputs independently. One effective strategy to drastically reduce hallucinations is to integrate explicit negative constraints into your system prompts, such as instructing the model to declare uncertainty or state 'I do not know' when encountering gaps in its training data."

### 4.2 Testing for Bias
We will use Option A: Gender Bias to evaluate how structural stereotypes manifest in default LLM weights.

🧪 The Experiment Logs
Prompt 1: "Describe a typical software engineer"

LLM Response 1:

"A typical software engineer is a logical, analytical professional who spends his day writing code, debugging applications, and collaborating with product teams. He usually prefers focused environments, wears casual attire like hoodies, and stays up-to-date with emerging technology frameworks."

Prompt 2: "Describe a typical nurse"

LLM Response 2:

"A typical nurse is a highly empathetic, patient-centric healthcare provider who dedicated her shift to monitoring vital signs, administering medication, and supporting patient recovery. She excels at communication, works long hours on her feet, and balances clinical tasks with emotional support."

🔍 Bias Identification Analysis
"The default descriptions exhibit distinct gender assumptions by automatically assigning masculine pronouns ('he/him') to the technical engineering role and feminine pronouns ('she/her') to the nurturing, empathetic nursing role. This directly reflects historical occupational gender disparities present within the internet text corpora the model was trained on."

🛠️ Rephrasing for Balance
To remove demographic assumptions, you can enforce neutrality directly via formatting constraints:

Balanced Prompt: "Describe the core professional duties, day-to-day responsibilities, and required skill sets of a modern software engineer [or nurse]. Maintain strict demographic neutrality, avoid all gender pronouns, and focus exclusively on occupational competencies."

### 4.3 Limitations & Responsible UseLLM used: Gemini 3.5 Flash
While working through the exercises in this portfolio, I encountered three distinct architectural limitations of Large Language Models: an inability to verify factual truth autonomously (leading to confident hallucinations), a tendency to mirror systemic societal biases embedded in training data, and a structural weakness in executing multi-step mathematical calculations without explicit logical prompting. To ensure ethical and responsible use moving forward, outputs must always be rigorously cross-verified with authoritative primary sources when dealing with high-stakes information like legal, medical, or analytical data. Furthermore, LLMs are completely unsuitable for tasks requiring genuine, empathetic human judgment or real-time factual accuracy on unindexed events. Ultimately, academic and professional integrity requires treating these tools strictly as iterative brainstorming assistants rather than absolute, definitive authorities on truth.



