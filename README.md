# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:
cvbbbc
### Project Title or Name of the Application	: Shart Simulator
### Section			   	      : 9-Sodium
### Group Members			    : Abrojena, Ancheta, Santos
### Date (Proposal Date)  : Nov 5, 2026
fdfhdfhfshsdhfhhtrthdfh
### Project Description:

- A brief summary of the project description and the need for it.

- Describes system components, features, and expected outputs clearly and logically. NOTE: Clearly described the elements(classes), their attributes and methods and how they will interact with each other.

- Include the description as well of your target demographics as the user of your application. 

- The description is then followed by the class diagram, depicting clearly what was described.

- - -

"Shart Simulator" will be a game based on Cookie Clicker (by Orteil and Opti) about clicking on Shart, which increases your number of Shartcoins. You can use your Shartcoins to buy upgrades (like an increase in Sharts per Click, instant increase in Shartcoins, automatic Sharts per second, etc), or different types of sharts with different superpowers in the ShartShop. The goal of the game is to collect as much Sharts and earn as much Shartcoins as you can.

We would like to be honest and say that our project is primarily for the use of entertainment. The concept of "shart simulator" is funny despite the poop-theme. It might be weird, but that can be attractive to the right audience. The target audience for this game are gamers.

Below are the following classes, attributes, and functions:




class User ATTRIBUTES:

-name

+lifetime_shartcoins

+current_no_of_shartcoins

-shart_equipped

+current_spc*

-list_of_achievements

+list_of_sharts_owned

+list_of_upgrades

*spc = shartcoins per click




class User FUNCTIONS:

-access_shartshop()

-change_shart_equipped()




class ShartShop ATTRIBUTES:

-list_of_upgrades_to_buy

-list_of_sharts_to_buy




class ShartShop FUNCTIONS:

+purchase()

*User can purchase Upgrades and Sharts from the ShartShop, and it will be taken into effect and added to the User's respective list




class GeneralUpgrades ATTRIBUTES:

-upgrade_name

-tier_powers

*different upgrade variants will be inherited from GeneralUpgrade but will have their own upgrade_name and tier_powers




class General_Shart ATTRIBUTES:

-shart_name

-shart_superpower




class GeneralShart FUNCTIONS:

+enter_sim_gamemode()

*different Shart variants will be inherited from GeneralShart but will have their own shart_name and shart_superpower




**Sample class Diagram from https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png:**

![Sample Diagram](https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png)

### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1:
- Objective 2:
- Objective n:

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
