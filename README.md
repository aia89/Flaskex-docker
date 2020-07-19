How To Build and Deploy a Flask Application Using Docker on Ubuntu 18.04


Introduction
Docker is an open-source application that allows administrators to create, manage, deploy, and replicate applications using containers. Containers can be thought of as a package that houses dependencies that an application requires to run at an operating system level. This means that each application deployed using Docker lives in an environment of its own and its requirements are handled separately.

Flask is a web micro-framework that is built on Python. It is called a micro-framework because it does not require specific tools or plug-ins to run. The Flask framework is lightweight and flexible, yet highly structured, making it preferred over other frameworks.


Deploying a Flask application with Docker will allow you to replicate the application across different servers with minimal reconfiguration.

In this tutorial, you will create a Flask application and deploy it with Docker. This tutorial will also cover how to update an application after deployment.

    docker build --tag=dockerhubname/flask .
    docker run -d  -p 5000:5000  dockerhubname/flask
 
