---
layout: default
---

## **BS.GPD.CORE.01 Evidence**

<p style="text-indent: 55px;">
	
The enemy AI behavior I have created allows players moving through the game to be detected by enemies when players are within a certain viewing distance.  Using AI perception I was able to set the distance at which you're detected, the enemy AI can also detect sounds.  Using the "AI MoveTo" node I provided the enemy the ability to follow the player character around when spotted.  THe enemy AI also attacks the player and does damage when close enough.  This damage is applied using "Apply Damage" node, the amount of damage can be set within this node or creating its own variable.  Adding a "Play Anim Montage" node allows the enemy AI to have a set animation when they are attacking the player character to create immersive and interactive game environments.  AI implementation is a very complex and contains large amounts of scripts/blueprints to work properly, to do this I ensured that my code functioned properly by using the debugging option, it shows my blueprint nodes activate and I can visually see where the problem lies if any.  Additionally I kept detailed explanations of the purpose of each blueprint along with the logic behind them, using commenting and organizing my connecting lines between nodes to stay organized and this was key in creating and executing clear and effective code in Unreal Engine.  
</p>


<div style="text-align: center;">
    <a href="https://github.com/DCodeMorris/Week_7_Matrix/blob/main/assets/img/bp_enemy.png" target="_blank">
		<img src="https://github.com/DCodeMorris/Week_7_Matrix/blob/main/assets/img/bp_enemy.png" width="1920px" title="Enemy System Blueprint" />
	</a>
    <p><em>Figure 1 - Enemy Attacks Blueprint in Unreal Engine 5 - GAM-380 Game Experiential Learning</em></p>
</div>

