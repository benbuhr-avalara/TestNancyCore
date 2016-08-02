# TestNancyCore

### Required Dependencies

- Docker
- .NET Core 1.0

### Getting Started

First we need to restore the dependencies for .NET Core. Do that by entering the following command:

    dotnet restore

Next, run the following command to publish the app:

    dotnet publish

Then run this command to build the docker image:

    docker build -t testnancycore .

Finally run this command to run the docker container in an interactive terminal:

    docker run -it -p 5000:5000 testnancycore