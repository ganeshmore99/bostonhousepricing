# End-to-End Boston House Pricing Prediction Machine Learning Project

![house](https://github.com/ganeshmore99/bostonhousepricing/assets/85934803/a372527c-b176-439e-911b-18078f90ef37)


## Introduction
This project is an end-to-end machine learning implementation for predicting Boston house prices. The project covers the entire machine learning pipeline, from data preprocessing and training to deployment of the model. The final application is deployed using Docker and CI/CD pipelines with GitHub Actions, and the deployment is hosted on Heroku.

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)


## Project Setup and Requirements Installation
To get started with the project, you need to set up your environment and install the necessary dependencies. Follow the steps below:

## Clone the repository:

```
git clone https://github.com/ganeshmore99/End-to-end-Boston-House-Pricing-Prediction.git
```
```
cd End-to-end-Boston-House-Pricing-Prediction
```

## Create and activate a virtual environment:

```
conda create -p venv python==3.8 -y
```
## Install the required packages:

```
pip install -r requirements.txt
```


## User Application
A user-friendly web application is created to allow users to input data and get house price predictions. The app is built using Flask and can be run locally with the following command:

```
python app.py
```

## Docker
Docker is used to containerize the application for consistent and reproducible deployments. To build and run the Docker container.

## GitHub Actions
GitHub Actions is used to automate the CI/CD pipeline. The workflow file in the .github/workflows directory defines the steps for testing, building, and deploying the application. To enable GitHub Actions, simply push your changes to the repository, and the workflow will be triggered automatically.

Final CI/CD Deployment on Heroku
The final step is to deploy the application to Heroku. Ensure you have the Heroku CLI installed and configured. Then, follow these steps:

Log in to Heroku:

```
heroku login
```

## Create a new Heroku app:

heroku create boston-house-pricing-app
Deploy the Docker container to Heroku:

```
heroku container:push web -a boston-house-pricing-app
heroku container:release web -a boston-house-pricing-app
```

## Open the deployed app in your browser:

```
heroku open -a boston-house-pricing-app
```

## Conclusion
This project demonstrates a comprehensive workflow for developing and deploying a machine learning model. By following these steps, you can replicate the process and apply it to similar projects. Feel free to contribute to the project by opening issues or submitting pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any inquiries, please contact Ganesh More (Author).
