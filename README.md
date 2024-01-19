Welcome to Aidoc DevOps task! 
General Points 
1. You might face technologies that you have never used before, that's fine. We would like 
to get a sense of your self-learning skills. That's something every DevOps engineer faces on a weekly basis. 
2. Build for minimal change, use the best practices known to you to accomplish the 
steps. 
3. There are dozens of different solutions for this task, you're welcome to discuss different ideas and possibilities with your interviewer. There's more than one excellent solution. 4. Think of automating every small step in the process, and about the tools you'd use for 
this. Every step you have to implement in your solution should be under version control and automated. Meaning - if your whole solution is deleted - it should take 5 minutes to set up again. 
5. Feel free to contact your interviewer for any question that arises, the goal is for you to 
focus on the important parts of the exercise so if you feel you're wasting time - consult to make sure you're indeed implementing what is important. 
Project Description 
Aidoc configuration service is based on Hashicorp Consul. The configuration is managed based on the Consul K/V Store. 
You are required to create a CI/CD Process that will ship configuration files from Git to Consul. 
Requirements from the system: 
• 
The Consul service shall be publicly accessible through the Internet 
All of the code and configuration shall be managed through Git 
Whenever a developer merges change to configuration files to master, a pipeline shall 
be triggered which pushes the code to the production consul 
A single sanity test shall be performed to validate that the written configuration was applied successfully 
Consul shall be restricted to ACL Access only 
For this exercise you may work on a repository which includes only one configuration file. 
There is no requirement to manage secrets securely, you may assume that the configuration does not contain secrets. 
Bonus - find a way to store Consul's ACL token in a secure way for the Cl pipeline to 
use. 
