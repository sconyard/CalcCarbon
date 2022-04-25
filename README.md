# CalcCarbon

###  Dockerfile

Builds image based on python:3.9-slim, updates pip, installs requirements and launches Streamlit to serve page as defined by app.py

### Requirements.txt

Contains python requirements for app.py

streamlit
numpy
plotly

### app.py

Contains the calculations to workout the carbon output of server estates based on information inputs.  Guidance, formating and governance for inputs provided by streamlit module.

![Carbon Calculator](https://user-images.githubusercontent.com/29428448/165064101-bbb8bf84-9d15-415e-942f-8d7c1b4c1019.png)

Forecasting of anticipated carbon usgage based on data inputs and anticipated growth is also provided.

![Carbon Forcasting](https://user-images.githubusercontent.com/29428448/165064195-0d8450a1-2d0f-4fa2-a4cd-e59d26b356d4.png)



