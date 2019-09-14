# Swagger UI HTML
HTML page having embed Swagger UI's code directly by using unpkg's interface

## Instructions to Use

Just copy and paste this file to your project directory and set the URL of your swagger JSON in the file below: 

```js
  SwaggerUIBundle({
    url: "https://petstore.swagger.io/v2/swagger.json", // <- Change Path Here
    dom_id: '#swagger-ui',
    presets: [
      SwaggerUIBundle.presets.apis,
      SwaggerUIBundle.SwaggerUIStandalonePreset
    ],
    layout: "StandaloneLayout" 
  })
```
Once added, you should be able to browse the following Swagger UI endpoints respectively:

***\<your-root-url\>/swagger.html***

For more information on controlling Swagger UI, please see the official documentation of the [Swagger UI](https://github.com/swagger-api/swagger-ui)
