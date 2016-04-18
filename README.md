# angular2-facebook-connect

angular2-facebook-connect: 
a really simple Angular2 module which handles the login with facebook

Exemple here: http://www.nicolas2bert.com/chat

### Instalation

0) Build and run a super-simple Angular 2 application in TypeScript. https://angular.io/docs/ts/latest/quickstart.html

1) Download the angular2-facebook-connect package: download using the zip file 

2)

- Add app.component.html, app.component.ts and facebook.service.ts in your app 

- Replace your-app-id with your facebook app id inside /facebook.service.ts

```
  FB.init({
    appId: "your-app-id",
    xfbml: true,
    version: 'v2.5'
  });

```


3) Enjoy your login Facebook
