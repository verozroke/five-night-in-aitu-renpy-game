# five-night-in-aitu-renpy-game
FINAL REPORT
1.	Our project is a visual novel. A visual novel is a special genre of games that is based on reading the text and taking certain actions that affect the further plot. Our team chose this genre because of its small popularity. Our goal is to popularize visual novels and show the public their interest. The main difficulty lies in writing an interesting story with multiple endings. Our group does not want to do something banal and uninteresting, so making a unique plot. 
2.	Perhaps our novella will not have 10 endings, but our story completions will not leave anyone indifferent. We work on quality, not quantity. The main problem of similar games is precisely in the absence of an interesting story that cannot offend the reader. There is no immersion in the world written by the authors. We, in turn, are working on the deepest elaboration of each moment.
3.	Our project can objectively be better than others, for the reason that it is aimed primarily at humor. Our goal is not to make money, but only to create a short and interesting game based on the Ren’Py library. The problem is that many game developers’ aim is to create a game (even a visual novel) on game engines like Unity. Although, in turn, Ren’Py is a more successful and convenient option for creating games of this genre. It's simple, its performance is fast, it has all the features that any visual novel should have. Not a little important factor is also the scenarious part of our game. With the help of our satire and humor, we wanted to show how the students of our university behave. Some are funny, some are smart. But despite this, with each new step, the characters of our game change and learn from their mistakes.
4.	For this project, we used the most popular and convenient (for such a projects) programming language – Python. With integrated library and modules of Ren’Py. Ren’Py is a visual novel engine – used by thousands of creators from around the world. In our project, we have 9 different locations. More than 5 characters. 3 unexpectable for the player 3 endings of the scenario. And also, non-gameplay related stuff and functions such as “saving/loading the game", "flowchart", "dialogue skipping" and etc.
5.	We have studied the entire market for such visual novel games. And we came to the conclusion that we will rely on the best examples from these games. Such games are: “Zero Escape:  999”, “Everlasting Summer” and its modifications, "Love, Money, Rock and Roll". We have also made conclusions that consumers are most interested in the genres of visual novels such as everyday life, comedy, and romance. That is why our short story focuses on these three genre differences. We skillfully managed to balance these criteria for our game, and this helped us achieve a good and consistent story.
6.	The key points of our code is its variability. To do this, we have a series of menus in the story with actions that further affect the endings. For example, to open the secret ending, the hero must help a classmate with one thing, which will further affect the development of the plot. Also, the game has a number of story branches, so the player must complete the game more than 1 time to get all the content.


7.	Commands: menu (pic. 2 and pic. 4). It gives the user a choice of some actions that he can choose. Each choice affects a certain plot. This is done by jumping to a specific code branch that is unique to the story branch.
Quotes in brackets - ("text"). (pic. 2, pic. 3 and pic. 4) This is what the user will see. It is used: in the selection menu, in the phrases of the characters, in the text and answers of the main character. To change their format, use indentation, colons, or determine who the phrase belongs to before the text.
Variables (pic. 2): Using the boolean system, initially variables are False. Then, as you select, some variables may change to True, which will determine the ending.
Characters (pic. 1 and pic. 5): We created 13 different characters. In this picture, we see that in order to create them, we just need to name the character (in our own invented syntax, we decided that we write c_ before the character name), then use the Character() function, where we pass the name of the character as arguments, as well as the color that will be glued to it. To call a character in the game, it is enough for us to write his name in the script.py (pic. 3), and then write the phrase that he will speak. And this phrase will appear on the screen. Every character have 2 or more outfits which has at least 3 different emotions. So, we created no less than 72+ variables of characters’ emotions.
Sprites (pic. 7): In the /image directory we have all the characters sprites. As we said before, our characters has more than 6 different emotions, and because of that, we organized directories and divided it to different outfits with laconic names.
Locations (pic. 6): We have added 9 locations to our game. To do this, we decided to create a separate file locations.rpy and add them there using the image function. This function creates a variable in which the picture of this location is stored.
8.	We chose a development environment (in our case, it is ren.py based on the Python language). Next, we outlined what will happen in each chapter and where the development will go, narration, etc. Then we began to study the method of developing a game using a Python lesson and finally, we started to develop our chapters. The first development chapter is day 3 which in turn is the key to the story. Then we will start thinking about the first chapters and the last ones. In our arsenal of tools, we used TortoiseGit desktop program (instead of Git Bash) along with GitHub for collaborative development. (pic. 9)
 

9.	Askhat: made the definition of locations and their choice. Created a needed system and methodology for more productive work of our team. Created GitHub repository and helped other teammates to connect it. Took care of the characters and their display. Developer of chapters 1 and 5, key moments and plot twists. Creator of the interface, unique locations and sprites. 
10.	Artem: developed the variability of solutions, the structure of the game and the content of the chapters. Developer of chapters 3 and 5, key moments and plot twists. Creator of interface, music and sounds. 
Dzhikhangir: Endings Creator, Day 2 & 4 Developer, and Team Motivator. Brilliant ending and character designer.
11.	Our goal was to create a short and fun visual novel that would represent our beloved university. We believe that we have coped with this problem by 100 percent, because we are already completely satisfied with our result. We have completed all the tasks assigned to us, which made our game unique in the visual novel genre. As a result of our project, we came to the conclusion that we have a very interesting game about friendship and university studies with humor. There are several endings in our game, any choice in it affects our plot. Also, we have over 10 characters, each based on a real person from our group. In total, we have written more than 1500 lines of code, which make this game unique. It's a lot of work done by just 3 people and a handful of ambitions. And because of this, I think our whole team has learned to take responsibility and improved their work skills through teamwork skills. We also improved our programming skills in Python, which will be our main language in the future. As a result, this game gave us great experience in many areas necessary for life, and of course, we should not forget about having a good time with team members.
