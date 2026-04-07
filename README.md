# VibeCoded
Vibe coded projects using GPT, Gemini, AIStudio, and my own two hands.

In order to avoid having some of my larger scale tools copycatted, I'm only uploading projects here that do not accept user payment for a generation or service. For this reason, most of these projects are tools I created to help me use AI to the best of its ability while keeping it's obvious constraints/limitations in mind. 

"AI is powerful, which is why it’s important to use it carefully and responsibly. That means being mindful of AI’s limitations and accounting for biases. The best results come from a combination of human ingenuity and AI’s capabilities. So keep asking insightful questions, refining your prompts, and above all, applying your critical-thinking skills to verify outputs before you use them. That way, you contribute to a future where AI serves everyone responsibly." - Google AI Fundamentals Course 04/2026

Here are the constraints and limitations I've found so far, and the tools I've made to address these problems:

1) The constraint of knowledge cutoff:

"Knowledge cutoff is the point in time when a model’s training data ends. This means the model lacks information on events, discoveries, or data that occurred after that date.

You might notice that a model can provide information about very recent events. Some may do this by performing a live web search to find current information that they can supplement their answer with. It's helpful to think of this as the difference between what the model knows from its training versus what it can look up in the moment. The model's core knowledge is not continuously updated, which is why the concept of a knowledge cutoff remains a critical limitation to bear in mind.

Responsible AI use requires you to verify time-sensitive information. Always use a search engine or other reliable sources to fact-check statistics, news, or any information about recent events.

To work effectively with a model's knowledge cutoff, you can use these techniques:

Look up the cutoff: You can search online for the knowledge cutoff date of a specific AI tool. This helps you understand the boundary of its internal knowledge.

Verify time-sensitive information: For any statistics, breaking news, or details about recent events, always cross-reference AI's answer with a reliable external source, like a search engine or an official report.

Specify your timeframe: When asking about a topic that changes over time, state the timeframe for what you need. For example, instead of "What was the biggest song of the summer?" ask “What was the biggest song of the summer in 2025?”

Refine with follow-up prompts: If an answer seems outdated, like calling a product new when it is several years old, use a follow-up prompt to ask for more recent alternatives or clarification." - Google AI Fundamentals Course 04/2026

2) Changes in AI’s performance over time:

"Drift is the gradual decline in a model’s accuracy and relevance as the real world changes. You might observe drift in two ways:

Factual drift: This is when AI becomes less accurate over time because of its knowledge cutoff. For example, an AI model's advice on current fashion trends may become less useful the further you get from its training date.

Behavioral drift: This refers to changes in AI’s behavior over time. As developers update models, you might notice that the formatting, tone, or conversational style changes, even when you use the same prompts.

Here are a few ways to manage and mitigate both kinds of drift:

Provide accurate and up-to-date context in your prompts, especially for topics that change quickly, like market trends or technology.

Keep chats focused by starting a new conversation for each specific task. This also helps to reset the context window if a conversation becomes too long or the output starts to feel off topic.

Be explicit with clear and specific instructions in your prompts." - Google AI Fundamentals Course 04/2026
