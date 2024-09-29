# Benchmark overview

In intelligent meeting management software, one of the important components is asking questions from the text of the conversation. 
This benchmark is prepared to evaluate the response quality of the LLM engine from the text.

The LLM benchmark includes 33 Contexts (for 14.74 hours) and 21 questions in Type 1 and Type 2.
1.	Type 1: General questions, including summarization tasks (11 questions).
2.	Type 2: Yes/no questions, which required a more straightforward response (10 questions).

The audio files in here[https://drive.google.com/drive/folders/1TjPnGTq20uWb5twzvoLKcuxi3HlGums1?usp=drive_link]

Each sample in the JSON file includes 1) an audio_path, which indicates the audio of the context, 2) the context, 3) Questions Type 1, and 4) Questions Type 2.

In benchmark_meeting.json, we prepared our results in MeeTask. We used chatgpt-4o-mini to answer the questions and evaluated the consistency between the answer, question, and context with a score of 0-5. The evaluation engines used were chatgpt-4o-mini and chatgpt-4o.
