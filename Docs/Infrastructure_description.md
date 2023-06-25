### User
Http requests are sent by the user and recieved by the S3 hosting website. Http request are send to the followng url:
http://udacity-pipeline-bucket-v2.s3-website-us-east-1.amazonaws.com/

HTTP request are non-secure meaning that sent on port 80.


### S3
S3 hosts a website. S3 looks for a index.html file that enables the dynamic Udagram website.

When the user creates a new account, create a post, or view posts a requests to made to the api via javascript assocaited in index.html file.


### Elastic Bean Stalk
Elastic Bean stalk host our api. Elastic Bean stalk enables to specify env vars in our app. These env vars include credentials, DB information etc. Elastic bean stalk also provisions a domain on our behalf. We supply this domain name to the front end app. This enables communication between the api and the front end.

### Database
A postgres database was created via the AWS RDS console. The Elastic Beank Stalk EC2 instances connects to this database via credentials created in the RDS console and passed to the api server via environment variables. 


