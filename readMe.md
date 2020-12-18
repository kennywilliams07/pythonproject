Kenny Williams
==============

Python Project 2020 (https://github.com/kennywilliams07/pythonproject)
======================================================================

The Three Features Met:
-----------------------
* Create a class, then create at least one object of that class and populate it with data
* Read data from an external file, such as text, JSON, CSV, etc and use that data in your application
* Connect to an external/3rd party API and read data into your app

Crypto Tracker
==================

This is an application written in Python that utilizes Binance Exchange's API to track cryptocurrency prices and other information.
-----------------------------------------------------------------------------------------------------------------------------------

In order to run this program, you will first need to install the following dependencies:
----------------------------------------------------------------------------------------
* Python 3.8
* Pandas
* Numpy
* Requests

To download Python, if you don't already have it installed, visit this link: https://www.python.org/downloads/

After downloading, return to the project to install the rest of the dependencies (if you don't have them installed globally on your machine).

Open up a new terminal session in your project directory and run the following commands:
1. pip install pandas
2. pip install numpy
3. pip install requests
If the commands return errors, try these instead:
1. pip3 install pandas
2. pip3 install numpy
3. pip3 install requests
    1. sudo pip3 install pandas
    2. sudo pip3 install numpy
    3. sudo pip3 requests

The program is now ready to run. Run the script by typing in the shell "crypto.py". After running the script, you'll notice that data prints to the terminal, returning prices, increases/decreases, etc. The script automatically converts the data
into a CSV file named 'myBinanceData.csv' but you can freely delete the already-supplied file and run it again and you'll see that a new one is created instantly. You can also comment out 'print(bnn_df)' located on line 26 if you'd like the data to be returned only in CSV format.