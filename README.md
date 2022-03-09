// Go modules are disabled.

## About

This is a web crawler specifically designed to crawl e-learning website educative.io

## UseCase -
Sometimes, you are short on internet connectivity in a remote place, but you dont want to lose speed
on your courses. So, you might want to save the courses offline, so that you can read them even when 
the network connectivity is not there. 

## Solution
The design crawls through the educative website and stores screenshots of all the paths in the website.
You can go through the screenshots and continue your learning.

## Setup
Tools used to test locally
Java 1.8
Selenium 4.1.2
Gecko Driver 0.30
Clone the repository on your local device. Enter the username and password in the config. 
Run "go run main.go" inside the repo folder. You are good to go.
The code  saves all the screenshots in a folder called "output" inside your repository.
