Detection of Pnumonia in Chest X-rays Using Maching Learning 

Zachary Sowers
Miles Todtfeld
Data souce: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download&SSORegistrationToken=CfDJ8J1i-7MzxEhBg3BSP9qFZm8Uyi5IRo_a-L8rccwFjHzQpfR9q4V6gLTXjISfwmdFWHkzJYmhF_fpxwlO68TkyBvK8SDwls4BmvqZB0m1TV9HSGB1Vou5nEj5h9YD9y-rYnVpMEVnKjxEIF5RXVi-i0bhjpnpCLHYwoBzvJYRgFH7ONyS3tvLFkONx1igNoqVqEToF6L2GyvE2pyESH5O0ZQeC3bYAXUoIDBZV-Z49gO5wAWe4C7j9elDRkdJ2gCOPJNJLuFg4WV6DC5Ahdk00xm0wcSHlU-AqQEz5yEinABoWsPHN2lDVPJ16VhRl7CLuS6P5DD8a4N6HFwbFnydJFHAI78

Major Contributions:

Preparing data for training:
First download the data from the kaggle link. Delete the _MACOSX folder and the nested chest_xray folder. This nested chest_xray folder is a complete duplicate of the data in the test, train, and validation folders.  

How to setup virtual environment (REQUIRED):
Inside of the project folder run
python -m venv .venv

On Windows activate the environment with:
.venv\Scripts\Activate

On Mac/Linux activate it with:
source .venv/bin/activate

Install all libraries in the requirements.txt on pip
ex: pip install numpy


How to generate requirements.txt:
ip3 freeze > requirements.txt
