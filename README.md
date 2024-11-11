# Flask GPU App

This project showcases how to run a Flask web application with a GPU backend using Google Colab and ngrok.

## Overview

This app provides an example of deploying a Flask application with free GPU resources, ideal for applications requiring significant computational power, such as machine learning or image processing.

- **Read the blog post**: [Build a Free Stable Diffusion App with a GPU Backend](https://www.assemblyai.com/blog/build-a-free-stable-diffusion-app-with-a-gpu-backend/)

## Getting Started

Follow the steps below to set up and run the Flask app:

1. **Open the Colab Notebook**:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AssemblyAI-Examples/flask-gpu-app/blob/main/notebook.ipynb)

2. **Set Up ngrok**:
   - Go to [ngrok.com](https://ngrok.com), sign up for a free account, and get an API token.
   - Replace `YOUR-AUTHTOKEN-HERE` in the Colab notebook with your ngrok token.

3. **Configure the Runtime**:
   - In Colab, set the runtime to use **GPU**: `Runtime` -> `Change runtime type` -> Set `Hardware accelerator` to `GPU`.

4. **Run the Notebook**:
   - Click on `Runtime` -> `Run all` to execute all cells in the notebook.

5. **Access Your App**:
   - After execution, a cell will display a URL like `http://5fdc-104-196-187-169.ngrok.io`. Click this URL to access and use your Flask app.

## Features

- Uses GPU resources provided by Google Colab.
- ngrok is used to expose the local server to the internet, enabling easy access and testing.
- This setup is perfect for rapid prototyping and sharing GPU-powered Flask apps.

## Dependencies

Ensure your Colab environment has the necessary Python packages. The notebook includes cell code for installing any required packages automatically.

## Additional Resources

- **Flask Documentation**: [Flask](https://flask.palletsprojects.com/)
- **ngrok Documentation**: [ngrok](https://ngrok.com/docs)

Enjoy building and sharing your GPU-powered Flask app!
