# Instructions for Windows
*Make sure you have git installed*
[Git for Windows](https://git-scm.com/downloads/win)
*Creat a new directory*
>mkdir CLIP
*Change your working directory into this newly created directoy* 
```cd CLIP```
**Required step:**
*Make a copy of the github repository*    
>git clone https://github.com/KristerMartinez/CLIP.git`
*Create a new virtual environment. - not required but recomended*    
>python3 -m venv venv
*Turn on the Virtual enviroment if you created it in the step above*
>venv\Scripts\activate.bat
**Required step:** Install the needed packaged to run this code, if you get errors try creating the virtual envviroment if you did not*  
>pip3 install -r requirements.txt
**Finish line** *This runs the streamlit app*
```streamlit run streamlitV1.py```
*You should get a browser window pop up if not got to this link*
        [Local version of streamlit](http://localhost:8501/)
# Instructions for Linux/Mac
    *Make sure you have git installed*
        [Git for Linux and Mac](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
    *Creat a new directory*
 	    `mkdir CLIP`
    *Change your working directory into this newly created directoy* 
        `cd CLIP`
    **Required step:** *Make a copy of the github repository*    
        `git clone https://github.com/KristerMartinez/CLIP.git`
    *Create a new virtual environment. - not required but recomended*    
        `python3 -m venv venv.nosync`
    *Turn on the Virtual enviroment if you created it in the step above*
        `source venv.nosync/bin/activate`
    **Required step:** *Install the needed packaged to run this code, if you get errors try creating the virtual envviroment if you did not*  
        `pip3 install -r requirements.txt`
    **Finish line** *This runs the streamlit app*
        `streamlit run streamlitV1.py`
    *You should get a browser window pop up if not got to this link*
        [Local version of streamlit](http://localhost:8501/)