# Why?
The default priority icons in JIRA are exactly the same arrows of slightly different colour. Even for a person without vision issues it can be difficult to tell which icon is which priority.

# What do we do now? (╯°□°）╯︵ ┻━┻ 

The goal of this work is to provide user-friendly icons for priorities of tickets in JIRA or any other system. The icons in this repository have been intentionally designed with accessibility in mind and provide more visual clues regarding their meaning:
* They all have different shape so that you can understand which priority they represent without relying on color.
* Their shape is based on repetition and orientation of ^ symbol and you can easily understand which is more important than the other.
* The color and orientation helps to distinguish low and high priority tickets.

<span>
<image  height="42" src="https://raw.githubusercontent.com/CrowdCast/JIRA-Priority-Icons/34539b2923ff586e435c18bd8718b7564b121617/Highest.svg"/>
<image  height="42" src="https://raw.githubusercontent.com/CrowdCast/JIRA-Priority-Icons/34539b2923ff586e435c18bd8718b7564b121617/High.svg"/>
<image  height="42" src="https://raw.githubusercontent.com/CrowdCast/JIRA-Priority-Icons/34539b2923ff586e435c18bd8718b7564b121617/Medium.svg"/>
<image  height="42" src="https://raw.githubusercontent.com/CrowdCast/JIRA-Priority-Icons/34539b2923ff586e435c18bd8718b7564b121617/Low.svg"/>
<image  height="42" src="https://raw.githubusercontent.com/CrowdCast/JIRA-Priority-Icons/34539b2923ff586e435c18bd8718b7564b121617/LowestOption2.svg"/>
</span>

# How can I use it? ┬─┬ ノ( ゜-゜ノ)
You need to understand that JIRA does not allow to upload these icons into JIRA. You need to host them somewhere else.
* Fork this reposotiry and **make sure your fork stays public** or your JIRA users won't be able to access the icons. In this case you will avoid future modification of this reposotory affecting your JIRA.
* Go to https://YOUR_ORG.atlassian.net/secure/admin/ViewPriorities.jspa
* Click "Edit" on each priority and specify URLs to **PNG** icons:
    * https://raw.githubusercontent.com/YOUR_GIT_HUB_USER/JIRA-Priority-Icons/master/Highest.png
    * https://raw.githubusercontent.com/YOUR_GIT_HUB_USER/JIRA-Priority-Icons/master/High.png
    * https://raw.githubusercontent.com/YOUR_GIT_HUB_USER/JIRA-Priority-Icons/master/Medium.png
    * https://raw.githubusercontent.com/YOUR_GIT_HUB_USER/JIRA-Priority-Icons/master/Low.png
    * https://raw.githubusercontent.com/YOUR_GIT_HUB_USER/JIRA-Priority-Icons/master/Lowest.png

# Can we take it even further?
Yes! Add some personality to your JIRA! The default names of the priorities are not better than the icons. Who knows what "Medium" means in context of your orgranization? Here are some suggested changes:
* **Highest** => **Catastrophic** - The ultimate importance! If not done rocks will start falling from the sky and people start rampaging on the streets.	
* **High** => **Must have** - Has to be done sooner than later. Not doing this is not an option.	
* **Medium** => **Nice to have**	- Should be done, if possible. If not, we will survive without it.
* **Low** => **Can live without** - Has chances to be done, but no promises. Should not be touched unless there is nothing more important.	
* **Lowest** => **Meh** - Tasks go to die here. Do not do it unless it is very quick or there is nothing more important. Can be indefinitely pushed down the road.	
