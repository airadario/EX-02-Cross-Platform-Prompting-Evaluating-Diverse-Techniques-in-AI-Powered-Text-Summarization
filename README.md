# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm
## Step 1: 
Define the objective of summarizing the 500-word article on “The Basics of Blockchain Technology” for undergraduate students.

## Step 2: 
Select AI platforms such as ChatGPT, Google Gemini, and Claude for comparison.

## Step 3: 
Prepare three prompts using zero-shot, few-shot, and structured prompting techniques.

## Step 4: 
Submit the same article and prompts to each AI platform and collect the generated summaries.

## Step 5: 
Evaluate each summary based on accuracy, coherence, simplicity, speed, and user experience.

## Step 6: 
Assign scores from 1 to 5 for each evaluation criterion and compare the results.

## Step 7: 
Identify the best combination of AI platform and prompting technique based on the overall scores.

## Step 8: 
Present the results in a comparison table and select the most suitable approach for educational content summarization.

## OUTPUT
## Prompt 1: Zero-shot prompting
Summarize the 500-word technical article on “The Basics of Blockchain Technology” in simple English for undergraduate students. Include the definition of blockchain, how it works, its main features, advantages, limitations, and real-world applications. Keep the summary within 150 words.

## Prompt 2: Few-shot prompting
I need a simple summary of a technical article on blockchain technology for undergraduate students.

Example:
Topic: Artificial Intelligence.
Summary: Artificial Intelligence enables computers to perform tasks that normally require human intelligence, such as learning, reasoning, and problem-solving.

Now summarize the article “The Basics of Blockchain Technology” in a similar style. Explain the important concepts using simple words, short sentences, and relevant examples. Keep it within 150 words and include only information supported by the article.

## Prompt 3: Structured prompting
Act as an educational content editor. Summarize the article “The Basics of Blockchain Technology” for undergraduate students using the following structure:
1. Definition of blockchain
2. How blockchain works
3. Key features and benefits
4. Limitations and applications

Use simple English, maintain factual accuracy, and organize the information with clear headings and bullet points. Keep the summary within 150 words. Do not add facts that are absent from the original article.

## AI Platforms Used

## 1. ChatGPT

<img width="48" height="47" alt="image" src="https://github.com/user-attachments/assets/38f49d85-91ff-459a-ae4e-d9ae21f79b58" />

Used to generate structured, student-friendly summaries with clear explanations and customizable output.


## 2. Google Gemini

<img width="45" height="44" alt="image" src="https://github.com/user-attachments/assets/a5770e4e-7df9-4165-aab6-d09293213ef7" />

Used to generate concise summaries and organize the key ideas from the technical article.

## 3. Claude
<img width="49" height="47" alt="image" src="https://github.com/user-attachments/assets/3add94c9-6cab-4cc2-9df0-a249cd88d9bf" />

Used to produce readable summaries with logical flow and explanations of technical concepts.

## Sample Output: Summary of Blockchain Technology
Blockchain is a digital system that stores information in connected blocks across a network of computers. Each block contains transaction data and a cryptographic link to the previous block, forming a chain. Once information is validated and added, changing it is difficult because the network can detect unauthorized alterations.

Blockchain uses consensus mechanisms to help participants agree on valid transactions. Its main features include transparency, decentralization, traceability, and tamper resistance. It can reduce reliance on a central authority and improve record verification.

Blockchain is used in cryptocurrency, supply chain management, healthcare records, and digital identity systems. However, it also has limitations, such as energy consumption in some networks, scalability challenges, implementation costs, and regulatory concerns.

Overall, blockchain provides a way to maintain shared digital records securely, but its suitability depends on the specific application.

## Evaluation Criteria
<img width="426" height="166" alt="image" src="https://github.com/user-attachments/assets/1788bb89-d183-4317-a185-887cd79629e3" />

## Comparison of Prompting Techniques
<img width="597" height="119" alt="image" src="https://github.com/user-attachments/assets/38a7e491-87c0-42a2-ba00-09eff8587071" />


## Overall Comparison of AI Platforms
<img width="558" height="119" alt="image" src="https://github.com/user-attachments/assets/820faf31-e1cf-4336-9d0a-60ccbca95716" />

## Result

The experiment provides a method for comparing zero-shot, few-shot, and structured prompting across ChatGPT, Google Gemini, and Claude. Structured prompting is a strong candidate for producing accurate, coherent, and simple educational summaries. The best platform–prompt combination should ultimately be determined through source-based fact checking, timed trials, and user evaluation.
