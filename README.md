## What is this?

This repo contains a Jupyter Notebook that details some of the practices I adopt in my JS code. It's an highly opinionated commentary and everything it contains is explained with an agenda in mind. E.g. When talking about Dependency Injection I'm not going to expose all the possible use cases for it - I'm just going to show you why and how **I** make use of it in my overall coding style.


## Installation

Make sure you have Jupyter installed along with the Javascript/Node.js kernel.

Clone the repo, enter the folder and run

    npm install

Then you can just open the notebook in Jupyter.


If you get an error related to the Javascript Kernel not working, or pressing shift+enter on a code cell doesn't seem to produce any output, please verify the console output of Jupyter.

Note that I've built the notebook using [this kernel](https://github.com/n-riesco/ijavascript) and, at the moment of writing this, it apparently only supports node v8.9.0. If you have nvm installed, try shutting down Jupyter and running the following:

```
nvm install v8.9.0
nvm use v8.9.0

ijsinstall --spec-path=full
```

Then run Jupyter again and load the notebook.
