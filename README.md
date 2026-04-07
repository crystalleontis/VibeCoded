# VibeCoded
Vibe coded projects using GPT, Gemini, AIStudio, and my own two hands.

NOTE: In order to avoid having some of my larger scale tools copycatted, I'm only uploading projects here that do not accept user payment for a generation or service. For this reason, most of these projects are tools I created to help me use AI to the best of its ability while keeping it's obvious constraints/limitations in mind. 

README SECTION 1: Live Tools

My live tool list is currently:
1) OfferPath: https://bit.ly/offerpath

Put your resume in, get jobs out. It's that easy.

2) SitesScout: https://bit.ly/sitesscout

Put your URL in, get a full website health report back. 

3) Go Out Tool: https://bit.ly/goouttool

Go out and touch grass, or do something even cooler.

README SECTION 2: Known AI constraints, challenges, and limitations

"AI is powerful, which is why it’s important to use it carefully and responsibly. That means being mindful of AI’s limitations and accounting for biases. The best results come from a combination of human ingenuity and AI’s capabilities. So keep asking insightful questions, refining your prompts, and above all, applying your critical-thinking skills to verify outputs before you use them. That way, you contribute to a future where AI serves everyone responsibly." - Google AI Fundamentals Course 04/2026

"AI isn't magic. ​It's a computer program that, like others, has capabilities ​and limitations. ​Understanding how AI works can help you get ​the most out of it." - Google AI Fundamentals Course 04/2026

Here are the constraints and limitations I've found so far:
- Hallucinations & Confident Misinformation:

AI tools often present falsehoods as facts, such as fabricating legal cases, news events, or company policies. Models may hallucinate patterns or features that reflect prejudiced or unrepresentative data, leading to unfair discrimination. Models can misinterpret slang, idioms, or cultural references which can lead to nonsensical outputs.

AI hallucinations—where models confidently generate false, misleading, or nonsensical information—stem from probabilistic training, data gaps, and over-optimization for engagement. Key issues include data bias (leading to prejudiced outputs), factual inaccuracies, and hallucinations in image generation and autonomous driving, which pose significant safety and misinformation risks. Lastly, bad actors can intentionally manipulate AI, causing it to misclassify information or generate incorrect outputs (e.g., in cyber security or image recognition). 

Causes of AI Problems:

-- Probabilistic Nature: LLMs predict the most likely next token, not the verified truth.

-- Poor Training Data: Incomplete or low-quality data ("garbage in, garbage out").

-- Overfitting: Memorizing training data prevents effective generalization.

-- Failure in Retrieval Augmented Generation (RAG): When models pull from external sources, they may Misinterpret or fail to fact-check the data.

- Data Fabrication:

Logical and Mathematical Errors: AI may fail at complex reasoning or basic arithmetic, fabricating answers to math problems.

- "Sycophancy" and Misleading Conformity:

Chatbots may agree with a user's incorrect assumptions to keep them engaged, sometimes confirming delusional beliefs or reinforcing negative emotions.

- The constraint of knowledge cutoff:

Data Lag and Inaccuracy: Models often rely on outdated training data, causing them to provide incorrect information about current events.

"Knowledge cutoff is the point in time when a model’s training data ends. This means the model lacks information on events, discoveries, or data that occurred after that date.

You might notice that a model can provide information about very recent events. Some may do this by performing a live web search to find current information that they can supplement their answer with. It's helpful to think of this as the difference between what the model knows from its training versus what it can look up in the moment. The model's core knowledge is not continuously updated, which is why the concept of a knowledge cutoff remains a critical limitation to bear in mind.

Responsible AI use requires you to verify time-sensitive information. Always use a search engine or other reliable sources to fact-check statistics, news, or any information about recent events.

To work effectively with a model's knowledge cutoff, you can use these techniques:

Look up the cutoff: You can search online for the knowledge cutoff date of a specific AI tool. This helps you understand the boundary of its internal knowledge.

Verify time-sensitive information: For any statistics, breaking news, or details about recent events, always cross-reference AI's answer with a reliable external source, like a search engine or an official report.

Specify your timeframe: When asking about a topic that changes over time, state the timeframe for what you need. For example, instead of "What was the biggest song of the summer?" ask “What was the biggest song of the summer in 2025?”

Refine with follow-up prompts: If an answer seems outdated, like calling a product new when it is several years old, use a follow-up prompt to ask for more recent alternatives or clarification." - Google AI Fundamentals Course 04/2026

- Changes in AI’s performance over time:

"Drift is the gradual decline in a model’s accuracy and relevance as the real world changes. You might observe drift in two ways:

Factual drift: This is when AI becomes less accurate over time because of its knowledge cutoff. For example, an AI model's advice on current fashion trends may become less useful the further you get from its training date.

Behavioral drift: This refers to changes in AI’s behavior over time. As developers update models, you might notice that the formatting, tone, or conversational style changes, even when you use the same prompts.

Here are a few ways to manage and mitigate both kinds of drift:

Provide accurate and up-to-date context in your prompts, especially for topics that change quickly, like market trends or technology.

Keep chats focused by starting a new conversation for each specific task. This also helps to reset the context window if a conversation becomes too long or the output starts to feel off topic.

Be explicit with clear and specific instructions in your prompts." - Google AI Fundamentals Course 04/2026

- Different models have different strengths:

"Different AI models have different strengths, ​depending on how they were trained ​and how their learning was refined. ​Some models are really good ​at quickly providing all-around help. ​Other models might be best for advanced tasks ​like research, coding, ​or weighing the pros and cons of a complicated decision. ​Keep in mind, more complex tasks require more computations, ​which could take the model longer to complete." - Google AI Fundamentals Course 04/2026

- Token Usage and data limitations:

- AI downtime/regressions, live bugs:

AI sites currently exist (such as https://www.braintrust.dev/learn/ai-monitoring/) that provide live realtime solutions to these problems.

- Existing AI Tinkerer Tools Trust Hurdle:

https://www.promptarmor.com/

Someone who creates AI tools for fun is often called an AI tinkerer or enthusiast, representing a hands-on approach to exploring new technology. Other common terms include AI hobbyist, creator, or prompt engineer (if focused on prompt-based tools), with synthographer sometimes used for AI art creators. 

Here are the most common terms based on different types of "making":

-- AI Tinkerer / Enthusiast: The most common term for hobbyists experimenting, building projects, and exploring AI capabilities in their free time.

-- AI Creator / Developer: A broad term for anyone building AI-powered applications, apps, or models.

-- Prompt Engineer / Prompt Master: Refers specifically to those who build tools or content by crafting complex, specialized AI prompts.

-- Synthographer / AI Artist: Used for individuals focused on generating AI art or visual media.

-- AI Operator / Technician: A more technical term sometimes used to emphasize that the user is running the AI tool, rather than creating the underlying model. 

Many in the community prefer the term "tinkerer" as it captures the playful, low-stakes nature of doing it for fun, often leveraging open-source, inexpensive, or free AI/ML tools.

Tools that currently exist, like braintrust above (and any of mine for that matter), are difficult to "trust" without being given a full scope of the maker type, hardware and software stack, AI model and tool stack, personal AI preferences and global settings, personal AI training for recent events, update logs, etc... which would ultamitely give away the "secret sauce" opening the door to copycats, direct rips, etc... 

README SECTION 3: Live github tools made by me and my robot friends
