# IG_Reciprocate
An application that extracts followers and following list to figure out the one's that are not following back so we can reciprocate.
![IG_Reciprocate]
(https://github.com/xerzen/IG_Reciprocate/Images/app1.png)

### Tutorial:
1. Login in using your account and Click *RECIPROCATE* to process
![IG_Reciprocate 2](/Images/app2.png)

2. View Results
![IG_Reciprocate 3](/Images/app3.png)

![IG_Reciprocate 3](/Images/app4.png)

### Installation Guide:

1. Download Chrome if you haven't already
2. Check your Chrome Version

  1. Go to Settings
  ![Check Chrome Version Step 1](/Images/Chrome1.png)
  
  2 Click on About Chrome tab and get your Chrome Version
  ![Check Chrome Version Step 1](/Images/Chrome3.png)
  
*if you have Chrome Version 84, skip steps 3 & 4 (chromedriver is already included)*
3. Download chromedriver from https://chromedriver.chromium.org/downloads 

4. Replace chromedriver in /assets/ folder

5. Download and Install Python 3 from https://www.python.org/downloads/

*feel free to use conda or any Python package manager of your choice*
6. Install Selenium using pip:
`pip install selenium`

7. Install Pillow using pip:
`pip install pillow`

8. TkInter should come installed with python
If you get a TkInter Error, install Tkinter using this tutorial https://tkdocs.com/tutorial/install.html


### Final Step: Run IG_Reciprocate using,
`python3 reciprocate.py`





