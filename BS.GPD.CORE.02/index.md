---
layout: default
---

## **BS.GPD.CORE.02 Evidence**

<p style="text-indent: 55px;">
	
I added a powerup in the game that allows the player character to fly, this is implemented by removing gravity within the game for the player and adding additional animations when in the flying position.  To trigger the flying ability I implemented a "On Component Begin Overlap Box",  these are components that trigger events when the player character overlaps the box component.  With the variables created it allows the duration of flight to be set.  In the second image you see the ability to stop flying by using the implemented jumping controls already included with the starting blueprint of the player character.  Using a "Flip Flop" allows me to switch the outputs of A and B, this sets movement rates for when a character is flying or walking, this is highly complex pretaining to game controls and enhances the overall gameplay experience.  This demonstrates my ability to involve various elements such as animation changes and gravity manipulation.
</p>


<div style="text-align: center;">
    <a href="https://github.com/DCodeMorris/Week_7_Matrix/blob/main/assets/img/Screenshot%202024-04-28%20110144.png" target="_blank">
		<img src="https://github.com/DCodeMorris/Week_7_Matrix/blob/main/assets/img/flying_bp.png" width="1920px" title="Flying System Blueprint" />
	</a>
    <p><em>Figure 1 - Flying System Blueprint in Unreal Engine 5 - GAM-380 Game Experiential Learning</em></p>
</div>
<div style="text-align: center;">
    <a href="https://github.com/DCodeMorris/Week_7_Matrix/blob/main/assets/img/flying_controls.png" target="_blank">
		<img src="https://github.com/DCodeMorris/Week_7_Matrix/blob/main/assets/img/flying_controls.png" width="1920px" title="Flying Controls Blueprint" />
	</a>
    <p><em>Figure 2 - Flying Controls Blueprint in Unreal Engine 5 - GAM-380 Game Experiential Learning</em></p>
</div>
