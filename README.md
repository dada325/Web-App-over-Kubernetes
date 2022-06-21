# Web-App-over-Kubernetes

The Application folder is the root folder of our application. It contains all of the necessary files that make up the application, namely:

Dockerfile: This file is not a part of the application. However, it contains all the commands that are needed to create a Docker image.
package.json: This file is responsible for handling all of the required dependencies for the project.
package-lock.json: This file contains the tree that is generated when the node modules tree or the package.json file is modified.
public: This folder contains HTML files and other assets of the application.
src: This folder is where the main code of the application lies.
Now that we have all the essentials to make an application, we need to create a Dockerfile for it. This Dockerfile will be responsible for executing all of the commands that are required to create an image, and for executing the application successfully.
