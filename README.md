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
## 1.Select the technical article "The Basics of Blockchain Technology."
## 2.Provide the same article content to different AI platforms:
ChatGPT
Gemini
Claude
Copilot
## 3.Apply different prompting techniques:
Zero-shot prompting
Few-shot prompting
Chain-of-thought prompting
Role-based prompting
## 4.Generate summaries using each AI platform.
## 5.Compare the generated outputs based on:
Accuracy
Coherence
Simplicity
Response speed
User experience
## 6.Record the observations and identify the best-performing combination.
## PROMPTING TECHNIQUES
## 1. Zero-Shot Prompting

Zero-shot prompting provides a direct instruction without giving examples.

## Example Prompt:

"Summarize the article 'The Basics of Blockchain Technology' in simple words."

## 2. Few-Shot Prompting

Few-shot prompting provides examples along with instructions to guide the AI model.

## Example Prompt:

"Summarize the article in the following format:

## Example:
Topic: Artificial Intelligence
Summary: AI enables machines to learn and perform tasks.

Now summarize the article 'The Basics of Blockchain Technology' in the same format."


## 3. Chain-of-Thought Prompting

Chain-of-thought prompting encourages the model to analyze information step-by-step before generating the final answer.

## Example Prompt:

"Analyze the key concepts of Blockchain Technology step-by-step and then provide a simple summary for undergraduate students."


## 4. Role-Based Prompting

Role-based prompting assigns a specific role to the AI before generating output.

## Example Prompt:

"You are an educational content creator. Summarize the article 'The Basics of Blockchain Technology' for undergraduate students using simple explanations."


## Result
## 1.CHATGPT+ZERO-SHOT PROMPT:
Summary: The Basics of Blockchain Technology

Blockchain is a digital record-keeping technology that stores information in a secure and transparent way. It consists of a chain of blocks, where each block contains a set of data and is connected to the previous block using cryptographic methods.

Unlike traditional databases controlled by a single organization, blockchain works through a decentralized network where multiple computers verify and maintain the data. This makes the system more secure, transparent, and difficult to modify without permission.

Each transaction added to a blockchain is verified by network participants through a process called consensus mechanisms. Once recorded, the information becomes permanent and cannot be easily changed, which improves trust between users.

Blockchain technology is the foundation of cryptocurrencies like Bitcoin and Ethereum, but its applications extend beyond digital currencies. It is used in areas such as healthcare, supply chain management, banking, voting systems, and digital identity verification.

In simple terms, blockchain acts like a shared digital ledger that allows people and organizations to securely record, verify, and exchange information without relying on a central authority. Its key benefits include security, transparency, reliability, and reduced chances of fraud.

## 2.CLAUDE+FEW-SHOT PROMPTING

Topic: Blockchain Technology

Summary: Blockchain is a decentralized digital ledger that records transactions across a network of computers in a secure, transparent, and tamper-resistant way. Each block contains a set of transactions and is linked to the previous block, forming a chain — making it difficult to alter past records without changing every subsequent block. It removes the need for a central authority (like a bank) by allowing participants to verify and trust data collectively.

## 3.COPILOT+CHAIN OF THOUGHT PROMPTING
Blockchain is essentially a decentralized, tamper-proof digital ledger where transactions are grouped into blocks, verified by a network, and permanently linked together. It ensures trust, transparency, and security without needing a central authority, making it vital for cryptocurrencies, supply chains, and secure record-keeping.

Step-by-Step Breakdown of Blockchain Technology
1
Initiate a Transaction
A user requests an action such as sending cryptocurrency or recording data.

User creates a transaction (e.g., sending Bitcoin)

Transaction includes sender, receiver, and amount

Digital signature ensures authenticity

2
Broadcast to Network
The transaction is shared with all computers (nodes) in the blockchain network.

Transaction sent to peer-to-peer network

Nodes receive and prepare to validate

3
Verification & Validation
Nodes check if the transaction is legitimate using cryptography.

Verify digital signatures

Ensure sender has sufficient funds

Validate against blockchain rules

4
Block Formation
Valid transactions are grouped together into a block.

Transactions bundled into a block

Each block contains a timestamp and unique hash

Hash links block to previous one

5
Consensus Mechanism
Network nodes agree on the validity of the block.

Methods include Proof of Work (PoW) or Proof of Stake (PoS)

Consensus ensures trust without central authority

6
Block Added to Chain
Once validated, the block is permanently added to the blockchain.

Block linked to previous block via hash

Creates an immutable chain of records

7
Ledger Updated
All nodes update their copy of the blockchain.

Distributed ledger reflects new transaction

Transparency and security maintained



Simple Summary for Undergraduate Students
Blockchain is like a shared digital notebook that everyone can see but no one can erase. Each page (block) records transactions, and once written, it’s locked with a unique fingerprint (hash). New pages are added only when everyone in the network agrees they’re valid (consensus). This makes blockchain secure, transparent, and decentralized, useful for cryptocurrencies like Bitcoin, supply chain tracking, and secure digital contracts.
## 4.CHATGPT+ROLE-BASED PROMPTING
The Basics of Blockchain Technology – Summary for Undergraduate Students

Blockchain is a modern digital technology used to store and share information securely. It works like a digital ledger where data is recorded in groups called blocks. These blocks are connected together in a sequence, forming a chain of blocks.

Unlike traditional databases that are controlled by a single organization, blockchain uses a decentralized network, meaning many computers participate in storing and verifying information. This reduces the need for a central authority and increases trust among users.

Each block contains transaction details, a timestamp, and a unique code called a hash that connects it to the previous block. Because of this structure, changing information in one block affects the entire chain, making blockchain highly secure and resistant to tampering.

Blockchain networks use consensus mechanisms to confirm transactions. Methods like Proof of Work and Proof of Stake allow network participants to agree on valid transactions before adding them to the blockchain.

The most popular application of blockchain is cryptocurrency, such as Bitcoin, where it enables secure digital payments. However, blockchain is also used in many other fields, including healthcare for secure patient records, supply chains for tracking products, banking for faster transactions, and voting systems for transparent elections.

In simple terms, blockchain is a shared and secure digital record system that allows multiple users to store, verify, and exchange information without depending on a single controlling authority. Its main advantages are security, transparency, reliability, and trust.

Key Takeaways:

Blockchain is a decentralized digital ledger.
Data is stored in connected blocks secured by cryptography.
Transactions are verified through consensus mechanisms.
It improves security and transparency.
It has applications beyond cryptocurrencies in various industries.

## COMPARISION TABLE

| AI Platform | Prompt Technique | Accuracy  | Coherence | Simplicity | Speed     |
| ----------- | ---------------- | --------- | --------- | ---------- | --------- |
| ChatGPT     | Zero-shot        | Good      | Good      | Good       | Fast      |
| ChatGPT     | Few-shot         | Very Good | Very Good | Excellent  | Fast      |
| ChatGPT     | Role-based       | Excellent | Excellent | Excellent  | Fast      |
| Claude      | Chain-of-Thought | Excellent | Excellent | Good       | Moderate  |
| Claude      | Role-based       | Very Good | Excellent | Good       | Moderate  |
| Copilot     | Zero-shot        | Good      | Average   | Good       | Fast      |
| Copilot     | Few-shot         | Good      | Good      | Good       | Very Fast |
| Copilot     | Role-based       | Very Good | Good      | Good       | Fast      |
## RESULT

The experiment was performed using ChatGPT, Claude, and Copilot with different prompting techniques for summarizing "The Basics of Blockchain Technology."
ChatGPT (Zero-shot prompting) generated a simple and relevant summary with good accuracy and readability.
Claude (Few-shot/Chain-of-Thought prompting) produced a detailed and well-structured summary with excellent accuracy and logical flow.
Copilot (Zero-shot prompting) provided a fast response with good simplicity but comparatively lower coherence and detail.
ChatGPT (Role-based prompting) generated the best output by providing an accurate, clear, and student-friendly summary.
The comparison showed that role-based and few-shot prompting techniques improved the quality of AI-generated summaries.
Among all tested platforms, ChatGPT with role-based prompting achieved the best overall performance in terms of accuracy, coherence, simplicity, speed, and user experience.
The experiment concludes that effective prompt design plays an important role in enhancing AI-powered text summarization.
