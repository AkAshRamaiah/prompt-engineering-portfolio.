# Prompt Project 02: AI Email Assistant Prompt

## 🧩 Problem
Busy professionals often struggle to write clear, polite, and effective emails quickly. I designed a prompt to help AI generate or rewrite professional emails based on short input.

## 💡 Final Prompt
"You are a professional email assistant. Based on the following context, write a polite, concise, and clear email. Use a professional tone.  
Context: [PASTE CONTEXT OR BULLET POINTS HERE]"

## 📄 Example Input
Context:  
- Follow-up with a client  
- Mention proposal sent last week  
- Ask if they have any questions  
- Offer to schedule a quick call

## 📄 Example Output
Subject: Following Up on Proposal  

Dear [Client's Name],  

I hope you're doing well. I wanted to follow up on the proposal I sent last week and see if you had any questions or thoughts. I'd be happy to schedule a quick call to discuss further if needed.  

Looking forward to hearing from you.  

Best regards,  
[Your Name]

## 🛠️ Reasoning Behind the Prompt
I used role-based prompting ("you are a professional email assistant") to shape tone and behavior. I also used bullets in the input for speed and structure, so users don’t need to type full sentences.

## 🔁 Iteration & Improvement
Originally, the prompt didn’t specify tone, so replies were casual or too wordy. Adding "polite, concise, and clear" fixed that. I also tested it with vague input to make sure the AI filled in gaps smoothly.
