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
* [SalesForce mobile SDK](https://github.com/forcedotcom/SalesforceMobileSDK-Android)

## Development

##### Mobile

Available Ionic platforms: android, ios

1) Install cordova plugins & initialize platforms

Install all needed dependencies based on package.json definition.

```
ionic state restore
```

2) Add your platform to project (optional)

```
ionic platform add {platform}
```

3) Generate resources

```
ionic resources
```

4) Build project

```
ionic build {platform}
```

5) Start project

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

## Android manifest

Permissions to be added to manifest in case of any troubles:

```
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
```