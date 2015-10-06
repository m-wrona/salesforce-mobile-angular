# salesforce-mobile-ionic

Sample project for SalesForce using Ionic and AngularJS. 

Project created based on tutorials and found meterials regarding SalesForce.

## Required

* NodeJS
* NPM
* force-server
* ionic
* cordova
* mobile SDK (android, ios)

## Set-up

1) Salesforce OAuth plugin:

```
cordova plugin add https://github.com/forcedotcom/SalesforceMobileSDK-CordovaPlugin
```

## Development

##### Mobile

Available platforms: android, ios

1) Add your platform to project

```
ionic platform add {platform}
```

2) Generate resources

```
ionic resources
```

3) Build project

```
ionic build {platform}
```

4) Start project

```
ionic emulate {platform}
```

##### Web-server

1) Go to www directory

```shell
cd www
```

2) Run project locally

```shell
force-server
```

Then check your [browser](http://localhost:8200). Application will be run on port 8200


## Salesforce

[REST API](http://www.salesforce.com/us/developer/docs/api_rest/api_rest.pdf)