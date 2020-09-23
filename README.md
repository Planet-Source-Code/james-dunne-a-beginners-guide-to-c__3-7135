<div align="center">

## A Beginners guide to C\+\+


</div>

### Description

This article teaches beginners a few things, not all but I am gonna include in other tutorials, I will only make a sequel to tutorials if you like the prequal
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[James Dunne](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/james-dunne.md)
**Level**          |Beginner
**User Rating**    |4.1 (29 globes from 7 users)
**Compatibility**  |C\+\+ \(general\)
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/james-dunne-a-beginners-guide-to-c__3-7135/archive/master.zip)





### Source Code

<p><strong><font face="Verdana, Arial, Helvetica, sans-serif">Introduction -<br>
 <br>
 </font></strong><font face="Verdana, Arial, Helvetica, sans-serif">Okay, This
 is my first tutorial ive ever written for Planet-Source-Code so go light if
 I make mistakes :). I really hope this helps you as much as another tutorial
 helped me. In this tutorial you will learn (hopefully) how to compile source
 code and write a basic program that will display an Variable
 that you input. </font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Enjoy, ~Jamesy.</font></p>
<p> </p>
<p><strong><font face="Verdana, Arial, Helvetica, sans-serif">Part 1 : The first
 code of a beginner-</font></strong></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Well, if you dont have a
 clue what to do you probably haven't got<br>
 compiler yet so go to http://www.download.com
 and search Dev-C++, this will show up a single result, if not search for Bloodshed
 Dev-C++. This is a C++ and a C compiler also! So go ahead download it. Now,
 once you have installed it open it and click the new file icon to bring up a
 text editor-like window with this inside : </font></p>
<blockquote>
 <blockquote>
 <p><font color="#009900" face="Courier New, Courier, mono">#include <iostream.h><br>
  #include <stdlib.h></font></p>
 <p><font face="Courier New, Courier, mono"><strong>int</strong> main()<br>
  {</font></p>
 <p><font face="Courier New, Courier, mono"> system(<font color="#FF0000">"PAUSE"</font>);<br>
  <strong> return</strong> <font color="#0000FF">0</font>;<br>
  }</font></p>
 </blockquote>
</blockquote>
<p><font face="Verdana, Arial, Helvetica, sans-serif">now, in between the sharp
 brackets (ones with a point in the middle) type or copy this :</font></p>
<blockquote>
 <blockquote>
 <p><font face="Courier New, Courier, mono">cout << <font color="#FF0000">"Howdy
  there, Oh yeah, Hello World!"</font>;</font></p>
 </blockquote>
</blockquote>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Now you should have something
 like this :</font></p>
<blockquote>
 <blockquote>
 <p><font color="#009900" face="Courier New, Courier, mono">#include <iostream.h><br>
  #include <stdlib.h></font></p>
 <p><font face="Courier New, Courier, mono"><strong>int</strong> main()<br>
  {<br>
  cout << <font color="#FF0000">"Howdy there, Oh yeah, Hello World!"</font>;<br>
  </font><font face="Courier New, Courier, mono">system(<font color="#FF0000">"PAUSE"</font>);<br>
  <strong>return</strong> <font color="#0000FF">0</font>;<br>
  }</font></p>
 </blockquote>
</blockquote>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Go to "Execute"
 on the toolbar (where File, Edit, etc is) then press "Compile & Run"
 and it should say in an MS-DOS prompt :</font></p>
<blockquote>
 <blockquote>
 <p><font face="Courier New, Courier, mono">Hello there, Oh yeah, Hello World!</font></p>
 </blockquote>
</blockquote>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Congrats, you just programmed
 in C++! Sure you didnt write the program but you did compile it which means
 your a programmer.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Now for the explanation
 :</font></p>
<p><font color="#009900" face="Verdana, Arial, Helvetica, sans-serif">#include</font><font face="Verdana, Arial, Helvetica, sans-serif">
 means to insert code out of a header file. </font></p>
<p><font color="#009900" face="Verdana, Arial, Helvetica, sans-serif">iostream.h</font><font face="Verdana, Arial, Helvetica, sans-serif">
 is the file that lets you do the cout and cin commands. iostream means input-output-stream
 just if you are wondering.</font></p>
<p><font color="#009900" face="Verdana, Arial, Helvetica, sans-serif">stdlib.h</font><font face="Verdana, Arial, Helvetica, sans-serif">
 lets you do the system(<font color="#FF0000">"PAUSE"</font>); command.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">The blank line is just whitespace,
 ignore it but put it between every function.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif"><strong>int</strong> main()
 is a function that must be in every C++ program. Its like your motherboard to
 your PC, It cant be run with out it.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">{ is the opening bracket
 and just for time keeping, } is the closing bracket.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">cout prints to the console
 (<< must be present, cant be the other way round)</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">system(<font color="FF0000">"PAUSE"</font>); stops the
 script from running after it, making the program to stop after it has printed
 to the console instead of printing then closing. Thank this for giving you the
 pleasure on seeing your pride joy in your first C++ program.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">return 0; returns 0 to close
 the program.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">On to Part 2 : The Juicey
 Stuff</font></p>
<p> </p>
<p><font face="Verdana, Arial, Helvetica, sans-serif"><strong>Part 2 : The Juicey
 Stuff</strong></font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Now click the New Code button
 again. Now we are gonna stick our fork in the steak this time and not the chips.
 </font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Click on the first whitespace
 and press enter then type :</font></p>
<blockquote>
 <blockquote>
 <p><font face="Courier New, Courier, mono"><strong>int</strong> clouds;</font></p>
 </blockquote>
</blockquote>
<p><font face="Verdana, Arial, Helvetica, sans-serif">then in the next white space
 put : </font></p>
<blockquote>
 <blockquote>
 <p><font face="Courier New, Courier, mono"> cout << <font color="#FF0000">"How
  many clouds do you see?\n"</font>;<br>
  cin >> clouds;<br>
  cout <font color="#FF0000">"\nThere are "</font> << clouds
  << <font color="#FF0000">" in the sky!\n"</font>;</font></p>
 </blockquote>
</blockquote>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Now you should have something
 like this :</font></p>
<blockquote>
 <blockquote>
 <p><font color="#009900" face="Courier New, Courier, mono">#include <iostream.h><br>
  #include <stdlib.h></font></p>
 <p><font face="Courier New, Courier, mono"><strong>int</strong> clouds;<br>
  <strong>int</strong> main()<br>
  {<br>
       cout << <font color="#FF0000">"How
  many clouds are there?\n"</font>;<br>
       cin >> clouds;<br>
       cout << <font color="#FF0000">"\nThere
  are " << clouds << " in the sky!"</font>;<br>
       system(<font color="#FF0000">"PAUSE"</font>);<br>
       <strong>return</strong> <font color="#0000FF">0</font>;<br>
  }</font></p>
 </blockquote>
</blockquote>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Now compiler and run and
 test :)</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Now for the explanation
 :</font></p>
<p><font color="#FF0000" size="1" face="Verdana, Arial, Helvetica, sans-serif">*Note
 : I am only explaining things you have not already learnt</font></p>
<p><font color="#FF0000" size="1" face="Verdana, Arial, Helvetica, sans-serif"><font color="#000000"><br>
 </font></font><font color="#FF0000" face="Verdana, Arial, Helvetica, sans-serif"><font color="#000000">int
 clouds; is the variable, this stores the information you type in when you ran
 the program. Say for instance 86 its would say :</font></font></p>
<blockquote>
 <blockquote>
 <p><font color="#000000" face="Courier New, Courier, mono">There are 86 clouds
  in the sky!</font></p>
 </blockquote>
</blockquote>
<p><font face="Verdana, Arial, Helvetica, sans-serif">There are more types of
 Variable which I will explain in a later tutorial if you like my tutorial.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif"><< clouds <<
 in the cout command basically displays the variable. You can do this with any
 variable and is used when using endl (another way to linebreak, I prefer \n
 for programs like these) You can even add, subtract, multiply, etc with it.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Ok now you have enough knowledge
 to add to the program and make it more instresting and stuff, after my next
 tutorial you will be able to make a Questionaire!</font></p>
<p><strong><font face="Verdana, Arial, Helvetica, sans-serif">Other things!</font></strong></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Ok, if you want to get in
 contact with me, I dont use email, Only AIM! Contact me on chickenscooop if
 you need anything or want to recommend something.</font></p>
<p><font face="Verdana, Arial, Helvetica, sans-serif">Again, I would like feedback,
 please give me feedback :)</font></p>
<blockquote>
 <p><font face="Verdana, Arial, Helvetica, sans-serif">~James Dunne</font></p>
 <blockquote>
 <p><font face="Verdana, Arial, Helvetica, sans-serif"><br>
  </font></p>
 </blockquote>
</blockquote>
<p> </p>

