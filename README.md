# Rails

Rails is a web application development framework written in the Ruby programming language. It is designed to make programming web applications easier by making assumptions about what every developer needs to get started. It allows you to write less code while accomplishing more than many other languages and frameworks. Experienced Rails developers also report that it makes web application development more fun.

Check out their official documentation [here](https://guides.rubyonrails.org/getting_started.html)

## Deploy a Rails App

### Deployment Instructions

In this tutorial, we advice creating a Dockerfile and using Docker as the build system

1. Fork/Clone this [Hostless-Rails-Example](https://github.com/Hostless-Examples/Hostless-Rails-Example.git) repo from github
2. Click on 'Create New App'
3. Choose a suitable app name
4. Choose your github account
5. Choose the forked github repo/the cloned remote repo
6. Choose a build system

    1. 'Docker' - looks for a Dockerfile in the root of the project and build based on the instructions

7. Input a start command(optional)
8. The PORT environment variable is set by Hostless
9. In production, set SECRET_KEY_BASe environment variable

#### Sample configuration
![sample](https://res.cloudinary.com/do58rrxug/image/upload/v1714682424/Screenshot_2024-05-02_at_21.40.11_dcmh5t.png)

#### Example project
An example project is hosted on [https://hostless-rails-example.hostless.app/](https://hostless-rails-example.hostless.app/)
