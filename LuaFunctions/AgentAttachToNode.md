# AgentAttachToNode

### AgentAttachToNode(Agent, Agent, string, boolean)
- ***Agent:*** 
- ***Agent:*** 
- ***string:*** 
- ***boolean:*** *(optional)* 
- ***Returns:*** Nothing

AgentAttachToNode is a small agent prop that you want attached to another agent’s node.
This is different to AgentAttach, If you have a character agent created for example, a Character agent will have a type of node (Head, Eye_L, Hand, arm_L etc.) you will have to attach agent props (Gun agent as an example) to Agent Character’s Node.
***Example:*** Let’s try attach a toy agent into Clementine’s Node (Right hand)
The node of Right hand is called “wrist_R”

```Lua
    AgentCreate("Broccoli", "obj_toyBroccoli.prop", Vector(0.5,0,32), Vector(0,0,0), kScene, false, false);

    --Name of Node's Wrist Right (Hand)
    local nodeName = "wrist_R";

    --Check if Clementine do have any Nodes after adding new nodename
    if AgentHasNode("Clementine", nodeName) then
       --If she does have node, Then Attach it!
        AgentAttachToNode("Broccoli", "Clementine", nodeName);
        
        --Note: This is for fixing Broccoli's postiton on Clementine's Hand
        --AgentSetPos("Broccoli", Vector(0, 0.000, 0.022)); 
        --AgentSetRot("Broccoli", Vector(0, 0, 0));
    end
```
![very low](https://github.com/user-attachments/assets/acc1e9c9-0938-4912-861d-bb6b4c3053a7)

And… The result is here! Now there’s a problem… You see the Broccoli is underground besides clementine. But don't worry! You see, I have leftover “AgentSetPos” to fix where you want to put Broccoli. And also, you can see it moving the same way Clementine's right hand is moving!

### Usage

```Lua
AgentAttachToNode(variableAgent, variableAgent, variableString)
```

```Lua
AgentAttachToNode(variableAgent, variableAgent, variableString, variableBoolean)
```



[Back To Scripting Documentation](../README.md)
