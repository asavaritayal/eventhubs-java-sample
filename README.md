# Send events to Azure Event Hubs using Java

To run the sample, you need to set the `eventhubconnection` environment variable. 

```bash

export eventhubconnection="{Event Hubs connection string}"
```

## Build and run

The sample can be built independently with 

```bash
mvn clean package
```

and then run with (or just from VS Code or another Java IDE)

```bash
java -jar target/simplesend-1.0.0-jar-with-dependencies.jar
```