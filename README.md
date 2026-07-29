Exercise 1: Identify the Prompt Technique

· Objective: Check understanding of different prompt techniques.

· Task: Determine which prompt technique is being used.

· Instruction: Read the prompt below and identify the technique applied.

· Prompt: “Summarize the following paragraph in one sentence.”

Submission Answer:

· Identified Technique: Zero-Shot Prompting

· Justification: The prompt commands the model to perform a task immediately without providing any prior examples or training data to guide its formatting or style.

---

Exercise 2: Prompt Recognition

· Objective: Understand how a single example guides AI output.

· Task: Identify the prompt technique used.

· Instruction: Analyze the prompt below and name the technique.

· Prompt: “Example: Question: What is AI? Answer: AI refers to machines that can perform tasks requiring human intelligence. Now answer: What is Prompt Engineering?”

Submission Answer:

· Identified Technique: One-Shot Prompting

· Justification: The prompt provides exactly one fully structured example (Question and Answer pair) to illustrate the expected syntax and structural tone before introducing the new target question.

---

Exercise 3: Choose the Correct Technique

· Objective: Apply the correct prompting method based on scenario.

· Task: Select the most suitable prompt technique.

· Instruction: Read the scenario and choose the correct technique.

· Scenario: You want AI to follow the same writing style every time while generating responses.

Submission Answer:

· Selected Technique: Few-Shot Prompting

· Justification: Providing multiple examples (typically 3 to 5) teaches the AI complex structural styles, conversational tones, and edge cases. This ensures predictable, high-fidelity consistency across repeated generations.

---

Exercise 4: One-Shot Prompt Creation

· Objective: Practice writing a one-shot prompt.

· Task: Create a prompt using exactly one example.

· Instruction: Write a one-shot prompt to generate a polite response for a customer complaint, using one example response to guide tone.

Submission Answer:

Task: Transform blunt customer complaint updates into empathetic, professional responses.


Example:

Complaint: "My order is delayed. I want a refund now."

Polite Response: "Thank you for reaching out to us. We sincerely apologize for the delay with your order. We are tracking your package right now and will process a priority update, or a full refund if you prefer. Thank you for your patience."


Now generate a Polite Response for this new complaint:

Complaint: "Your app crashed while I was checking out and it took my money but didn't give me a receipt."

Polite Response: "Thank you for bringing this to our attention, and I am incredibly sorry for the frustration this has caused. I completely understand your concern regarding the

charge. I am looking into our transaction records right now to locate your payment and ensure your account is properly credited or a receipt is sent. Rest assured, we will get this resolved for you immediately."

---

Exercise 5: Rewrite Using Correct Technique

· Objective: Apply prompt techniques in practice.

· Task: Rewrite the prompt using an appropriate technique.

· Instruction: Improve the prompt below by choosing the correct technique (Zero-Shot, One-Shot, or Few-Shot).

· Original Prompt: “Make this sound professional: ‘Send this now.’”

Submission Answer:

· Chosen Approach: One-Shot Prompting (Example-Based Approach)

· Prompt Rewritten:

Instruction: Rewrite casual, urgent commands into formal, professional business phrases.


Example:

Casual: "Give me the files by tonight."

Professional: "Could you please share the requested files by the end of the day today?"


Now rewrite the following text using the same professional tone:

Casual: "Send this now."

Professional: "Please kindly forward this information at your earliest convenience."

---

Exercise 6: True or False (Concept Trap)

· Objective: Check conceptual clarity.

· Task: Evaluate the statement.

· Instruction: Mark the statement as True or False and justify your answer.

· Statement: “Few-shot prompting is used when the task is very simple and well-known.”

Submission Answer:

· Evaluation: False

· Justification: Simple, well-known tasks are best handled by Zero-Shot Prompting, because large language models already possess broad internal data for common actions. Few-Shot Prompting is reserved for complex tasks, niche data schemas, unusual tones, or strict output constraints that the model cannot infer without multi-point demonstrations.

---

Exercise 7: Prompt Comparison

· Objective: Understand how clarity affects AI responses.

· Task: Evaluate two prompts.

· Instruction: Compare the prompts below and identify which one will give better output.

o Prompt A: “Write a product description.”

o Prompt B: “Write a 3-sentence product description for a budgeting app targeting young professionals.”

Submission Answer:

· Selection: Prompt B

· Justification: Prompt B sets a clear operational scope (3-sentence length), establishes the subject context (budgeting app), and defines the exact target audience (young professionals). This explicit framework minimizes ambiguity, allowing the model to optimize its vocabulary and tone directly for the objective, whereas Prompt A is too vague and unpredictable.

---

Exercise 8: Technique Selection (Tricky)

· Objective: Test understanding of when to use each technique.

· Task: Select the correct prompt technique.

· Instruction: Scenario: You want AI to consistently follow the same writing style across multiple outputs. Choose the best technique and explain why.

Submission Answer:

· Selected Technique: Few-Shot Prompting

· Justification: To enforce a highly distinct, immutable writing style across varied outputs, a single example (One-Shot) might cause the model to copy specific words from that example rather than learning the overall rhythm. By providing a diverse set of examples via Few-Shot Prompting, the AI isolates the underlying stylistic blueprint (syntax, vocabulary, tone) from the specific context of the items, leading to highly robust, repeatable output styles.



Exercise 9 : Bonus Challenge

Objective : You are unsure which technique to use.


Rule-based Question:

Fill in the blanks:

Simple task, no examples → __Zero Shot____ prompting

One example to guide style → _One Shot _____ prompting

Multiple examples to train pattern → _Few Shot_____ prompting
