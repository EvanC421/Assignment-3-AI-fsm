# Assignment-3-AI-fsm

## 

Youtube link: [https://youtu.be/LlzgzgpU0sc](https://youtu.be/LlzgzgpU0sc)



## ISSUES FACED DURING IMPLEMENTATION



The first issue I faced was trying to make the states within states work accurately to my design.

The solution was quite simple. In the script, I encapsulated part of the entire code. Then, I copied and pasted said code and edited the states to be accurate to my design.



The second issue I faced was the transition from the villager's patrol state to the afraid state. I needed to activate the afraid state when the player collides with the villager.

The solution I found was to create a collision function that checks if the collider's tag is the player and if the overstate is set to villager. It wasn't my favourite solution because it required code outside of the state to work.

