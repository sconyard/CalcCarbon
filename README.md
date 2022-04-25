# CalcCarbon

###  Dockerfile

For ease of distribution the solution is packaged into a Docker image.

Builds image based on python:3.9-slim, updates pip, installs requirements and launches Streamlit to serve page as defined by app.py.

### Requirements.txt

Contains python requirements for app.py

streamlit
numpy
plotly

### app.py

Contains the calculations to workout the carbon output of server estates based on information inputs.  Guidance, formating and governance for inputs provided by streamlit module.

![Carbon Calculator](https://user-images.githubusercontent.com/29428448/165064101-bbb8bf84-9d15-415e-942f-8d7c1b4c1019.png)

Forecasting of anticipated carbon usage based on data inputs and anticipated growth is also provided.

![Carbon Forcasting](https://user-images.githubusercontent.com/29428448/165064195-0d8450a1-2d0f-4fa2-a4cd-e59d26b356d4.png)

### Editing

Build a local virtual python environmnet with the requirements above. 

run "streamlit run app.py" to launch a local version of the code.

![local copy](https://user-images.githubusercontent.com/29428448/165065064-55cd3553-739c-4ed8-9ff9-8a26df340105.png)

Edit the app.py code as needed, the local running version will allow code to be refreshed to see the impact of changes.

![source changed refresh](https://user-images.githubusercontent.com/29428448/165065560-4545a7dd-8c9e-4f5b-8f31-564d0eb99d2b.png)


