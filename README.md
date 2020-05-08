# Final
Final project IT1000

#Paragraph 
Writers write descriptive paragraphs because their purpose is to describe something. Their point is that something is beautiful or disgusting or strangely intriguing. Writers write persuasive and argument paragraphs because their purpose is to persuade or convince someone

#Headers
# H1
## H2
### H3
#### H4
##### H5
###### H6

#Link 
I'm an inline-style link](https://www.google.com)

#Image 
![blues](FPAiP2p-blues-hockey-wallpaper.jpg)

#List
		<ul>
			<li>Red</li>
			<li>Blue</li>
			<li>Green</li>
			<li>Purple</li>
		</ul>

#Bold text
**BOLD**

#Italicized text
*Italicized*

#Block of code
def Choose_Option():
    user_choice = input ("Choose Rock, Paper, or Scissors: ")
    if user_choice in ["Rock", "rock", "r", "R"]:
        user_choice = "r"
    elif user_choice in ["Paper", "paper", "p", "P"]:
        user_choice = "p"
    elif user_choice in ["Scissors", "scissors", "s", "S"]:
        user_choice = "s"
    else:
        print("Try agin")
        Choose_Option()
    return user_choice
