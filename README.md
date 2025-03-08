# demon_crew
Demon themed conversational AI agents

TLDR: The broader aim of this project is to demonstrate how existing knowledge can be used as a creative and structuring aid to help create a collection of interesting, distinct and stable conversational AI personalities. I focused on exisitings knowledge related to demonology and astrology as a shortcut to extracting personality features.

## Link to Demo
https://elevenlabs.io/app/talk-to?agent_id=8bwFSaCey67azIONK4Fn
currently not doing what I want it to :/

## General Project Purpose
The broader aim of this project is to demonstrate how existing knowledge can be used as a creative and structuring aid to help create a collection of interesting, distinct and stable conversational AI personalities. By using existing resources, the authorial burden of coming up with and designing a collection of complex and distinct profiles is eased, allowing designers to focus on 'the big picture'.

There is a wealth of interesting and detailed information in the world: in books, scripts, XML files, narratives, historical datasets and document collections, 1.0 webpages, and even in pseudoscience. I wanted to explore how I could use LLMs as a tool to structure and take inspiration from such information. While this can also be done on practical data for more functional application projects, in this current project I focus on using existing knowledge for entertainment and creativity aspects in conversational agent design. Especially because this leverages an unique feature of LLMs that is useful for creative applications: novelty, and surprise. Outside of a Computation Creativity focus things like hallucinations and unexpected behavior are usually considered undesirable; but in a creative setting this is feature (not a bug) that is challenging to achieve with other technologies and methods.

## Specific Project Idea
For this project, focused on a occult and demonology existing knowledge because this is currently a popular trending theme and aesthetic in media and branding. Such as video games, film, tv series, books, fashion, music, etc.

As understood in the late medieval and renaissance period in Europe, practitioners who considered themselves as pursuers of higher knowledge and as magicians could attempt to summon and command demons to perform specific tasks that the demon is specialized it. For example, there's a demon who is an expert in mathematics and specializes in searching for lost keys.

If you need help solving or finding something out (especially if you're a bored!), would you rather prompt a generic LLM agent, OR WOULD YOU RATHER SUMMON A DEMON - AN EXCITING AGENT OF HELL!!

There's of course an intriguing thematic parallel to draw between beliefs in historic demon summoning processes, command and control, and with contemporary computing concepts of control, calling, programming, daemons, and agents. You might even say that demon summoning is the OG helpful agent.

## Issues and Solutions
A problem that I ran into during this project was that the LLM wasn't able to generate the entire JSON of 72 demons in one go. The work-around was to generate the JSON in batches of 3 demons and copy-paste the file together by hand, then feed the complete file back into the LLM for further processing. This was a time consuming step but the silver lining was that I was able to read some of the demon info as I copy-pasted and got more familiar with the data. 

I instructed the LLM to get information about 72 different demons from the Ars Goetia grimoire (https://en.wikipedia.org/wiki/The_Lesser_Key_of_Solomon#Ars_Goetia). Info about this is widely available online. I instruced the LLM to generate a draft where the demon information was structured into features for each demon in a JSON document, so that it can be used and reused in different applciations. However, I felt there was a lack of variation in the demons so I instructed the LLM to use astrology knowledge (also widely availble online) as a fast way to add varied personality features for each of demons. In theory, this helps to make each one more distinct in conversation interactions.

## Hackathon
Designing and generating the demon JSON file and the project idea to develop conversational agents was done today only for the hackathon. 
The general demon theme was inspired by a larger idea I have for a computer terminal and phone based game and where a player calls hell as a 1990s corporate call center.

## Development Screenshots

![image](https://github.com/user-attachments/assets/4a259056-946b-4a31-94d7-683f6f271f84)

![image](https://github.com/user-attachments/assets/f010f0b1-723a-409a-930e-171dee9de199)

![image](https://github.com/user-attachments/assets/35f73572-f831-48ee-b38a-210ade65b197)

