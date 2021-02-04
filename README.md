# project-interview-api
API for running code for Project Interview. Capable of executing Python right now.

API hosted on https://project-interview-api.herokuapp.com/

## Installation
Clone repo
```bash
git clone https://github.com/Slingshot-mentoring/Project-Interview-API.git
```

Install node modules
```bash
npm install
```
Run the project
```bash
npm start
```
The project will now be live on http://localhost:3000/ .

## Usage
Install an API development tool like Postman. Send a request like this (Use the same body parameters).

![api-guide](./readme-media/API.png)

## Inputs for python
The only way to feed in inputs for python is using the sys module currently (in-built module).

```py
imoprt sys
```
For the first variable you'll need to refer it as sys.argv[1] and for the second variable you'll need to refer it as sys.argv[2].

```py
a=sys.argv[1]
b=sys.argv[2]
```

## Todo
- Add C++, Java
- Add support for infinite inputs instead of limited inputs (2) that we have right now. 