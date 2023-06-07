# DISProject
DIS Project made by Thomas (tnr653), Lasse (nhs881) and Magnus (xzb187). Group 101 on absalon with TA Axel Højmark.

To make the web app run do:
1. Run "pip install -r requirements.txt"
2. Change path in choice.py to the absolute path for the dataset (called "nutz.csv").
3. Comment line 4 out in choice.py ("from GreenGroceries import app")
4. Change password and databse name in the ".env" file
5. run "init_db.py"
6. Remove the comment from step 3
7. Run "flask run"

This should work (it worked for us somehow). But something might be different for your pc.

E/R diagram is given in the folder "/attachments" as well as a couple of screen shots from our web app, in case you can't make it run.

The web app is based on the Green Groceries example given in class.

Do note we spent at lot of time on many different issues, and thus therefore some naming etc. is still from the original example.
