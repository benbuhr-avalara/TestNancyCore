# TestNancyCore

### Required Dependencies

- Docker
- .NET Core 1.0

### Getting Started

Run the following command to publish the app:

    dotnet publish

Then run this command to build the docker image:

    docker build -t testnancycore .

Finally run this command to run the docker container in an interactive terminal:

    docker run -it -p 5000:5000 testnancycore