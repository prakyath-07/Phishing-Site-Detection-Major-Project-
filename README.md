# Hello Developers  :clap:

Code to dectect a phishing-site using Machine-Learning.

##### Functionality of Code {<>}
This code takes following as an input:

- URL from the address bar.
- Screen-shot of the current page.

Using these as inputs, the network test the data and checks if the given URL is legitimate or not.


##### About Code {<>}
This code is written in following languages:

- UI designs are done using HTML,CSS and JS with the combination of Django framework.
- Training and testing of data is done using Python.


##### File Details {<>}
Following are the details about the file inside phishApp/PhishingSiteDetection:

|    File Name   | Description                                                                                            |
|:--------------:|--------------------------------------------------------------------------------------------------------|
| site_list.txt  | These are the site details which you will be training the network for testing or for datasets          |
| openBrowser.py | Code to open the sites listed inside site_list.txt to take screen shot of it and store it as a dataset |
| save_model.py  | Code that is used to train the model (Updated the path based on your system)                           |
| screenshot.py  | Used to take the screen shot of the browser page                                                       |
| load_models.py | Used to test the sample model                                                                          |


#### Run code {<>}

Simply run the following code in terminal:
```
python3 manage.py runserver
```

##### Note {<>}

Explore other files in  *phishingUrlDetectionUsingML* 
