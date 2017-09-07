# Grails Restful API
>http://guides.grails.org/creating-your-first-grails-app/guide/index.html
Grails Version: 3.2.3
JVM Version: 1.8.0_144

```
grails create-app api
cd RESTService
grails create-domain-class api.City
```

Add Data into the database grails-app/init/api/BootStrap.groovy

```
grails create-controller api.CityController
```

Edit controller grails-app/controllers/api/CityController.groovy

```
grails dev run-app
```
