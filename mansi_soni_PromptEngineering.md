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

## Part 3: Strategic Prompting Techniques
### 3.1 Chain-of-Thought Prompting
### 3.2 Few-Shot Prompting

## Part 4: Responsible AI & Limitations
### 4.1 Testing for Hallucinations
### 4.2 Testing for Bias
### 4.3 Limitations & Responsible UseLLM used: Gemini 3.5 Flash




