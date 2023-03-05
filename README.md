Helloworld Servlet example with corresponding Dockerfile
Use testtest first to create war file in Target folder.
mvn clean package
Artifact will be created in target folder.
docker build -t testtest .
Once this is done u will see image using docker images
Use below command to run the container
docker run -d -p 8080:8080 --name testtest testtest
