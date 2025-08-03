# AgentAttach

### AgentAttach(Agent, Agent, boolean)
- ***Agent:*** 
- ***Agent:*** 
- ***boolean:*** *(optional)* 
- ***Returns:*** Nothing

 AgentAttach is an agent prop that you want attached to another agent.
 ***Example:*** Let’s attach a toy agent and Clementine agent!
```Lua
AgentCreate("Broccoli", "obj_toyBroccoli.prop", Vector(0.5,0,32), Vector(0,0,0), kScene, false, false);
AgentAttach("Clementine", "Broccoli");
```
<img width="702" height="580" alt="agentattach" src="https://github.com/user-attachments/assets/08f71afe-c05c-4cbb-a804-1d87de0346ea" />

As you can see in the above image, I spawned Broccoli on the postition differently instead of 0,0,0, because I want to spawn him close to clementine! Now, they are already attached to which I added code. The Broccoli supposedly will move the same way Clementine moves if you’re controlling Clementine to walk.

### Usage

```Lua
AgentAttach(variableAgent, variableAgent)
```

```Lua
AgentAttach(variableAgent, variableAgent, variableBoolean)
```



[Back To Scripting Documentation](../README.md)
