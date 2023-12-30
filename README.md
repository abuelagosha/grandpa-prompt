# Prompt Engineering Grandpa's Language Model 

These are ongoing attempts at trying to prompt engineer the open AI language model into my grandpa's persona. 
The base structure synthesizes langchain and open AI to form the language model that can be personalized through prompt engineering. 

# First Method - Few Shot Prompting

1. I tried to paste in sample conversational flow between the family member and my grandpa for the bot as reference. 
2. I then created a persona instruction with basic details of his character and to mimick the sample conversational flow. 

# Second Method - Summarizing + Prompting

1. I pasted in the entire raw interview transcript of my family talking about my grandpa.
2. I created a first prompt instructing the bot to summarize the character of my grandpa according to the transcript.
3. I then used this generated summary to create a second prompt of persona instruction. 
