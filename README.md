
# PURPOSE AND USEFULNESS
  The purpose of this program is to quickly and instantaneously create simple NPC characters to provide a framework for their more intricate design and personality. 
  
  You will enter 10 names of your choice at one time, which will then cleanly display the resulting character's age, a personality characteristic, a physical attribute, and a status in society. 
  
  It gives enough information to inspire a design and provide dialogue. 
    
  This project was coded in Python in 39 lines in total, including comments.

# TECHNICAL EXPLANATION
  Here is a simplified explanation of what this program is doing:
  
  Creates a list called “Names, which takes input through a loop until 10 names have been inputted.
    
   3 More lists are created, for characteristics, attributes, and status. All 3 have a large pool of hard-coded traits, and combining     them in unique ways leads to unique characters.
    
  It then runs the following code for each name:
    Determines their age, loosely based on the length of their name. (The characters below 3 years of age are babies and do not have       personality traits or notable physical characteristics yet.)
    
   Has one large print statement dependent on baby status, which then takes the age obtained previously and pulls from the lists for     characteristics and attributes.
    
  Each print state also contains equal-sign dividers and \n’s for line separation, making it very pleasing to view.
    In addition, most of this is reiterated in the comments of the original python code.

# OPTIMIZATION
The ways I can see to make this project better is to add more traits for a more specific archetype of a character. The traits that do exist are properly thorough for a project such as this, so more personality traits, physical traits, or other aspects would be most useful to make it more detailed. 

In addition, a system could be put into place to ask the user how many characters they want generated, instead of always doing ten.
