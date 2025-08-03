# AgentDuplicate

### AgentDuplicate(string, Agent, boolean, boolean, boolean, boolean, boolean)
- ***string:*** 
- ***Agent:*** 
- ***boolean:*** *(optional)* 
- ***boolean:*** *(optional)* 
- ***boolean:*** *(optional)* 
- ***boolean:*** *(optional)* 
- ***boolean:*** *(optional)* 
- ***Returns:*** Agent

AgentDuplicate is a creating a clone of agent from the orginial agent. ***Example:*** Let's clone a Abel!
```Lua
AgentCreate("AbelDummy", "sk61_abel.prop", Vector(0,0,30), Vector(0,0,0), kScene, false, false);

AgentDuplicate("AbelTwin", "AbelDummy");

AgentSetPos("AbelTwin", Vector(3,0,30));
```
<img width="1401" height="750" alt="agentcopy" src="https://github.com/user-attachments/assets/18069aea-b055-46d4-a97b-d5ae46b6a868" />

Abel's clone has created!

### Usage

```Lua
local resultAgent = AgentDuplicate(variableString, variableAgent)
```

```Lua
local resultAgent = AgentDuplicate(variableString, variableAgent, variableBoolean)
```

```Lua
local resultAgent = AgentDuplicate(variableString, variableAgent, variableBoolean, variableBoolean)
```

```Lua
local resultAgent = AgentDuplicate(variableString, variableAgent, variableBoolean, variableBoolean, variableBoolean)
```

```Lua
local resultAgent = AgentDuplicate(variableString, variableAgent, variableBoolean, variableBoolean, variableBoolean, variableBoolean)
```

```Lua
local resultAgent = AgentDuplicate(variableString, variableAgent, variableBoolean, variableBoolean, variableBoolean, variableBoolean, variableBoolean)
```



[Back To Scripting Documentation](../README.md)
