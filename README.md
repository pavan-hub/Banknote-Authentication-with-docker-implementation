# Bank Note Authentication 
## Data
* Data is extracted from images that were taken from genuine and forged banknote-like specimens. 
* For digitization, an industrial camera usually used for print inspection is used. 
* The final images have 400x 400 pixels. Wavelet Transform tool is used to extract features from images.

## Model Creation
* A Random Forest Classifier model with an accuracy score of 0.99 is saved as a pickle file.

## Web App
* A working front end web app is built using Swagger Api of the Flasgger library.
* Another version of the front end web app is created using streamlit library.
![streamlit](https://user-images.githubusercontent.com/55072093/146943387-b3ff18a5-1c38-44c6-adda-ef6c2bf5584f.JPG)

## Dockerization and Deployment
* The project was containerized and a docker image was created.
* The Dockerized modelis finally deployed on the heroku platform.





