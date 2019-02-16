# Pepepancho

remember to unzip the fonts and install them boys, then reset your computer

ok, so i don't know how to use github, so let me explain myself real quick, you got all your conky stuff figured out? no?
are you some kind of noobish dude/dudette who just wants to make ubuntu look pretty but doesn't know how to and will probably make 
his/her kernel explode in flames? that's what i thought, otherwise you wouldn't be reading this file, lmao, okay, basic stuff:

50 MINUTE "CUSTOMIZE UBUNTU TUTORIAL":https://www.youtube.com/watch?v=gLZ_5QA03Aw

okay done?, now you have conky, good, good... ok next thing, you have to get into your .conky folder, the dot means that it's
a hidden folder, it's located in ~/home/your name/.conky, to reveal the folder you go to the top menu -->View->Show hidden files:
and it's done, ez pz, you go inside this folder, then you create a folder called BLACK DYNAMITE... well, not necesarily that name
you could call it whatever you want, but that way it'll be easier for you to remember... well, you make the folder and then you 
put both documents, Black Dynamite TITLE and Black Dynamite CREDITS in there.

Now you open your conky manager, both files should appear on the list, you check both of them, and tada! both of them should
display on your screen

Ok, now about the internetoptions, they will probably fail (if everything displays correctly then stop reading), there are 
different kinds of connection for reasons i cannot  comprehend (i'm just a 19y/o boy, not a programmer) and you'll 
have to change that manually, now, to do this, you open your terminal with ctrl+alt+T, then you write

sudo apt-get update
sudo apt-get install net-tools

after that, you go and write:

ifconfig -a

This will allow you to see lots of internet options that i don't understand, but you're looking for the names before the giant
bunches of nonsensical internet data, in my case:

enp5s0 
lo 
wlp9s0

in my case, i took the first option (enp5s0), then i went to the conky manager, pressed the "edit widget option", and then went to 
the network window, where i put enp5s0 (which is MY type of connection and could be completely different to YOUR kind of connection)
and applied the changes, that should fix the internet options.

now, i know you probably have a ton of questions about why my code is so fucking awful, well, i just edited another person's 
conky config and crippled it to the point where it ended up looking completely different, i don't know what i was doing
and i still don't know, but let me tell you, it looks stupid good, and i don't care what you think, ignorance is bliss brother.

if you have any other problems, don't contact me, i don't know how to fix them, just google them d00d, i practically did all
of this thanks to google, and so can you! good luck with the voffsets, spanish color names and alligncs
