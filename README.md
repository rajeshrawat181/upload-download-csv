# upload-download-csv

# Upload/Download CSV Files


## Run Spring Boot application

mvn spring-boot:run

## DB Connection
Change connection string in application.properties
location - src/main/resources

## Lombok 
Install Lombok in your IDE for reduce boilerplate code like setter and getter and logs
or
define settor and gettor and logger reference

## CSV Error File(error_fileName)
Change directory path in application.properties
path name = file.error.csv.path
location - src/main/resources

## Logs path
Change directory path in application.properties
path name  = logging.path
location - src/main/resources

## end points (on localhost)
http://localhost:8080/register
http://localhost:8080/download/errors_user.csv


