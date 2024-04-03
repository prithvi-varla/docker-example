#Run command
java -jar target/docker-0.0.1-SNAPSHOT.jar

#use below postman command
POST
http://localhost:8080/api/v1/movie
body:
{
"movieName": "Hero",
"category": "test"
}

