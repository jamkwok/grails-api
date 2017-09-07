# Grails Restful API
> https://jolorenz.wordpress.com/2014/02/28/create-a-restservice-api-with-grails-2-3-x-in-15-minutes/
 Grails Version: 3.2.3
 JVM Version: 1.8.0_144

```
grails create-app api
cd api
grails create-domain-class api.City
```

Add Data into the database (Basically initialises Data) grails-app/init/api/BootStrap.groovy

```
grails create-controller api.CityController
```

Edit controller grails-app/controllers/api/CityController.groovy

```
grails dev run-app
```

Add routing to /api/city @ grails-app/controllers/api/UeiMappings.groovy

Check postman with GET

```
http://localhost:8080/api/city
```
