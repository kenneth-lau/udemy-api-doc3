# Notes from the "The Art of API Documentation" course

GitHub Pages website: https://kenneth-lau.github.io/udemy-api-doc3

For more information on this course, see [The Art of API Documentation](https://www.udemy.com/the-art-of-api-documentation) at Udemy.

## 2.2 Conceptual material
* Overview
  * Why
  * Requirements
  * Key concepts
  * Workflow
  * Visual information, diagrams,
* Getting started
  * Lead people through a simple task
  * WEB APIs
    * registration
    * get an app key
    * authorization
    * doing something simple
  * Platform APIs
    * Downloading SDK
    * Setting up IDE
    * doing something simple
* Tutorials
  * common tasks
  * step-by-step
  * screenshots
  * start with basic tasks then advanced
* Sample code
  * short, simple programs that work
  * able to copy and modify
  * common tasks
  * well commented
  * different from production code

## 2.3 Overview material
* Important because
  * What can the API do?
  * What is required to use the API?
  * Is it well-designed?
* High-level view
* Explain why?
  * describe key features
  * provide a few use cases
* Requirements
  * WEB APIs
    * usually not required
  * Platform APIs
    * programming languages supported?
    * OS, SDKs, IDEs required?
    * versions required?
* Key concepts
  * write a paragraph or two for each concept. what does the API do?
* Architecture
  * diagram
  * explain major pieces and how they fit together
* Workflow
  * describe order of tasks
  * order of API calls
* Diagrams
  * architecture diagram
  * workflow diagram

## 2.4 Getting started
* Why
  * to make the API less intimidating
* Hello world
  * simplest program that demonstrates feature of API
  * TTHW - time to hello world
* Structure
  * step-by-step instructions
  * include lots of screenshots
* Web APIs
  * registration
  * getting app key
  * making one or two HTTP requests
* Platform APIs
  * how to download SDK
  * setting up IDE
  * creating an app that does a simple task

## 2.5 Tutorials
* Purpose
  * hold hands and lead developers through common tasks
* Cover common tasks
* Same structure as getting started
* Sample HTTP requests or sample code
* Screenshots
  * Web APIs
  *   not many screenshots needed
  * Platform APIs
    * not many screenshots
    * maybe for IDE or something visual
* How many?
  * 3-5 usually

## 2.6 Sample code
* Guidelines
  * prioritize languages
  * relevant information grouped together
  * clarity over efficiency
* Importance
  * developers want sample code
  * can copy, paste, and modify
* Web APIs
  * can be called from any language
* Platform APIs
  * in the language of the SDK
* Illustrate workflow
  * show a series of API calls
* Use hard-coded values
  * Never use hard-coded values in production code
  * group relevant information together means use hard-coded values in sample code
  * exception: app keys and access tokens
* plenty of comments
  * they are critical
  * every class, function, or method should have at least one line
* Meaningful names
  * variable, class, and member names should be clear
  * clarity is more important than efficiency (in sample code)
  * long, unwieldy names are fine: they add clarity
  * never use meaningless names like "foo"
* Object oriented programming
  * does not "group relevant information together"

## 3.7 Tools
* GUI Tools
  * Postman
* command line tools
  * easy to include in Documentation
  * cURL or "curl"

## Exercise 2: cURL
* `curl --help` or `curl -h`
* flags
  * -X, --request (indicates method)
  * -H, --header
  * -d, --data
