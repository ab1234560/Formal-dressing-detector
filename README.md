# Formal-dressing-detector
This project helps detect a person's outfits and identify if it is formal or appropriate for the occasion. In most of the situations suits will most fit and indicate the respectful purpose. In the project whenever you import a picture without a formal outfit (suit) the project will print the line “Your outfit is not formal". On the other hand, if you have your formal dress you will pass the project by receiving a sentence of  "You dress up correctly".	

# The Algorithm
I use imangenet through the help of Nvidia's Jetson Nano Kit in the project to categorize the difference between a suit, which is a formal outfit, and a casual outfit, which can be anything. If the outfit is not identified as the class code of "suit", then it will be categorized to the not formal dressing part. 

# Running the Program
1. Connect your computer with the Nano and obtain the IP address
2. Open Visual studio code and enter your IP address as SSH which you obtained from the previous step
3. Upload pictures in the same directory as your python file - "imagenet.py"
4. In the terminal enter - python3 imagenet.py [inputfilename].jpg [outputfilename].jpg
