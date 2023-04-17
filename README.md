# Simple Flask Application

The application is containarized so you should have docker installed on your system to make sure this application works.

Follow the below mentioned steps to run this application.

Clone the repository by either http method or ssh method

```
git clone
```
Chaning branch from main to chore/project1

```
git checkout chore/project1
```
Building the image for the application

```
docker build --tag <give any name> .
```

Running the image on a Container

```
docker run -p 5000:5000 -d <name of the image>
```
