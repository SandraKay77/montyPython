# montyPython
#*****************************************************************************
#Author:        Sandra Schreffler
#Lab:           Lab 5
#Date:          06.17.22

#Description: This program prompts a user through several questions to complete the Quest for the Holy Grail, and prints a message with each successful questor's name.

#input: String yourName, string yourQuest
#output: Strings;

Sample Run: 
# what is your name?
# what is your quest?
# That is correct, you may pass


# Sample Run;
# What is your name? sir robin
# What is your quest?  to seek the grail
# sir robin
# You have answered correct. You May Pass! 
# HALT! Are there any who dare to answer my questions?!  yes
# What is your name? sir lancelot
# What is your quest?  I seek the grail
# you have failed! You are cast into the Gorge of Eternal Peril!
# AHHHHHHHHHHHHHHHH
# HALT! Are there any who dare to answer my questions?!  yes    
# What is your name? king arthur
# What is your quest?  to seek the grail
# sir robin
# You have answered correct. You May Pass!
# king arthur
# You have answered correct. You May Pass!
# HALT! Are there any who dare to answer my questions?!  no
# I thought not. 



# Constant String THEQUEST
# Constant String QUEST FAILED
# Constant String QUEST SUCCEED
# Constant String SCREAM
# Constant String Array QUESTORS[4]

# Function mainQuest
#       askName()
#       yourQuest()

# # Function askName
# 	Display “What is your name? “
# 	Declare yourName = input
# 	While not nameVerify(yourName)
# 	Display “I don't believe you should be on this quest! Next please.... You there! “ 

# # Function nameVerify(String aName)
# Declare yourName = aName.casefold
# For Each name in Questors[]
# 	If name.casefold == yourName
# 	Return True

# # Function yourQuest
# 	Display “What is your quest?”
# Declare quest = input
# If closeEnought(quest) = true
# 	Onward quest
# Else if closeEnough(quest) = false
# 	Quest failed
# # Function closeEnough
# Declare s1 = myQuest.casefold();
# Declare s2 = THEQUEST.casefold();
#     if s1 == s2:
#         return True;
#     else:
#         return False;


# # Function onwardQuest
# Display QUEST SUCCEED

# # Function questFailed
# Display QUESTFAILED
# Display SCREAM
#*****************************************************************************
