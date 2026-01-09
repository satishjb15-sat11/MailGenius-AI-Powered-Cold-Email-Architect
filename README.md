# MailGenius-AI-Powered-Cold-Email

MailGenius is a specialized AI application designed to solve the "Blank Page Syndrome" for sales professionals. By leveraging the Gemini 3 Flash model, it transforms raw product data and recipient details into polished, persuasive cold emails. Unlike generic AI chats, this tool is fine-tuned for business communication and conversion.

The core value of this project lies in its System Instructions and Prompt Design. I engineered the AI logic to follow specific copywriting standards:
AIDA Framework Implementation: The model is strictly instructed to follow the Attention, Interest, Desire, Action flow for every email generated.
Dynamic Tone Mapping: I developed specific prompt triggers that adjust vocabulary, sentence length, and formality based on user-selected tones (Professional, Friendly, or Bold).

Context Grounding: The prompt ensures the AI extracts the "Primary Value Proposition" from the user's product description rather than hallucinating features.
Safety & Spam Prevention: Integrated instructions to avoid "spam-trigger" words in subject lines to improve email deliverability.

🚀 Key Features
Recipient Personalization: Generates emails that feel researched and personal, not automated.
Tone Selection: Switch between different brand voices instantly.
Modern UI: A sleek, dark-themed dashboard built for focus.
Instant Export: Copy-to-clipboard functionality for seamless workflow.

🛠️ Tech Stack
LLM Engine: Gemini 3 Flash (via Google AI Studio)
Framework: React.js / Next.js
Styling: Tailwind CSS
Environment: Firebase Studio / Project IDX
