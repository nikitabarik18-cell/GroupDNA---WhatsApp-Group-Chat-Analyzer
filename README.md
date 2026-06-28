# GroupDNA---WhatsApp-Group-Chat-Analyzer
A Python-based tool to analyze and visualize WhatsApp group chat data. Gain insights into user activity, chat patterns, and sentiment.
Your WhatsApp group chat, decoded. Think of it as "Spotify Wrapped, but for your friend group."

GroupDNA is a lightweight, Python-based analysis tool designed to extract insights and patterns from WhatsApp exported chat logs without relying on heavy data science libraries like pandas or matplotlib. It uses pure Python, NumPy, and datetime to turn raw text data into meaningful statistics.

🚀 Key Features
Smart Chat Parsing: Efficiently processes exported .txt files to extract timestamps, senders, and message content while handling system messages, media-omitted entries, and deleted messages.

Group Overview: Get a headline summary including chat duration, total message count, and individual participation stats.

Temporal Insights: Discover the group's "busiest day" and "busiest hour" of the day.

Activity Heatmap: Uses NumPy to generate a 6×24 matrix (participants vs. hours), revealing who is a night owl versus an early bird.

NLP Basics: Identifies the top 10 most frequently used words, complete with a stop-word filter to keep the insights relevant to your group's slang.

Interaction Analysis: Calculates average response times and detects "silent streaks" (consecutive days without messaging) for each participant.

🛠 Built With
Python: File I/O, string parsing, dictionaries, and list comprehensions.

NumPy: For efficient matrix operations and heatmap generation.

Datetime: For precise timestamp parsing and time-delta calculations.

(Note: This project is built using fundamental programming concepts without heavy external dependencies like pandas or matplotlib.)

📊 Sample Output (Activity Heatmap)
The tool generates a clean, terminal-based visualization of member activity:
<img width="1166" height="900" alt="Screenshot 2026-06-28 235558" src="https://github.com/user-attachments/assets/16de79b1-d32d-46f1-b767-8b5673342bec" />
and many more outputs:
<img width="986" height="710" alt="Screenshot 2026-06-29 001425" src="https://github.com/user-attachments/assets/35f0f7e7-ed2d-42b8-b4bf-8745fb0c13af" />
<img width="783" height="720" alt="Screenshot 2026-06-28 235718" src="https://github.com/user-attachments/assets/65c8fa53-74e7-4196-8894-5a532a2a55b7" />
<img width="837" height="717" alt="Screenshot 2026-06-28 235707" src="https://github.com/user-attachments/assets/a4bd8fee-eb5b-48aa-b46a-0bbb8d8cdbc6" />

📋 How to Use
Export Chat: Export your WhatsApp group chat as a .txt file (without media).

Upload: Place the file in your project directory.

Run: Run the analysis script to see the statistics and visualizations directly in your console.
