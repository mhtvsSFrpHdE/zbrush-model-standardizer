# zbrush-zremesher-uniform-lines
A early implement of "zbrush-relax-uniform-lines".

**What's this**  
In sometimes using a sequence of brushes will result in a distorted or uneven mesh.  
This is bad for further sculpt, and also bad for some ZBrush features.  
Sometimes may even have bad looking.  
There're various of approach to solving the situation.  
**This** script is an early version of "zbrush-relax-uniform-lines",  
that use an old style to remesh the entire model and uniform the lines.  

The cons now seems:  
- Random lose details, typically because of the new model can't match the old one vertex by vertex.
- Too much required preprocess and end up with extreme long run time.

And the reason to left this script and keep its growing is:
- It can change the polycount by one-click.
- Use pure text to change interface argument instead of many keyboard & mouse operate.

In the future, it may use as a polycount change tool.  

**How to use**  
Clear the mask if there's any on the model.  
Open the TXT file by a text editor, adjust the values put on the top.
ZScript -> Load -> (If Run is not activate) Run.  
If Run is already activated, the script should start executing.  
In the end, a dialog appear says "Operation complete".  

**Principle**  
May change by time to time,  
the script now is very unsure status.  
Ignore the principle before it can be released.  

**Known issue**  
Many.  

**Special thanks**  
Grammarly for README.md
