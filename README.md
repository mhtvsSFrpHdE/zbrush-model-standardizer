# zbrush-model-standardizer
**Contact**  
See https://github.com/mhtvsSFrpHdE/contact-me  

**What's this**  
There are many cases that before doing sculpt,  
a model has to be compatible with a wide-used standard in your organization.  
So you may not able to find that the script is good for you to use.  
It's very customized for specific occasions.  
For example, raw object imported from other software,  
sculpt on a boolean after model, etc.  
They have mainly use zremesher with project to create subdivisions, and so on.  

**How to use**  
Clear the mask if there's any on the model.  
Open the TXT file by a text editor, adjust the values put on the top.
ZScript -> Load -> (If Run is not activate) Run.  
If Run is already activated, the script should start executing.  
In the end, a dialog appear says "Operation complete".  

**Principle**  
There is some condition value on the top op the script.  
By condition, it may apply close hole, dynamesh, and dyna-project to the model.  
then use zremesher, do smooth divide or sharp divide by condition,  
to get a multi-subdivision of original model.  

**Known issue**  
Autofix used as a feature collection, and can't only one of the features.  
No error catch.  

**Special thanks**  
Grammarly for README.md
