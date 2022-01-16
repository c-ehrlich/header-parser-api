# [Request Header Parser Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/request-header-parser-microservice)

This is an API that returns information about the HTTP Request header.

Part of the FreeCodeCamp Back End Development Certification.

## Sample deployment
https://fcc-headerparsermicroservice.herokuapp.com/

## Deployment
Heroku is shown as a sample deployment because it's free and doesn't required a Procfile.

With the [Heroku CLI](https://devcenter.heroku.com/categories/command-line) installed,
```
heroku login -i
heroku create <app name>
heroku git:remote -a <app name>
git push heroku main
```

## Sample Requests

### Get Header Information
`GET https://fcc-headerparsermicroservice.herokuapp.com/api/whoami`
```json
{
    "ipaddress": "::ffff:10.1.3.172",
    "language": "en-GB,en-US;q=0.9,en;q=0.8",
    "software": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/97.0.4692.71 Safari/537.36"
}
```
