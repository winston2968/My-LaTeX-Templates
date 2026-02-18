# $ \LaTeX$ Templates

**Content** : All $\LaTeX$ templates used during my studies such as notes, report, CV and formal letters headers. 

## :memo: Templates 

Here you get a little presentation of each template, including used packages and formatting choices. 

### CV 

It's probably the most complex one. I define differents environments such as new ```\section``` formatting and experiences ```tocolorbox```. 

You also have a ```\skill``` command to put little scale with bullets. 

### Letter

Here is a classic $\LaTeX$ formal letter template. It's maybe a good idea to reformat page setting with ```\geometry``` package according to the letter destinator. 

### Report 

You have a clean project report template. You can add bibliography with bibtex. 

A ```Makefile``` is provided to build the project. So you have differents commands : 
- ```compile``` : during the writting phasis to see rendered $\LaTeX$ quickly. 
- ```clean``` : to delete build fiels and clean workspace. 
- ```cleanall``` : same as clean command but delete ```.pdf``` file too. 
- ```build``` : compile all project with bibliography. 

### Others

And then you have different other templates which don't need a specific subsection. 