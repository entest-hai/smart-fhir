# Simple Demo SMART on FHIR 
### 1. Using an open FHIR server, just open "open_fhir_server.html" using a liveserver in vscode. 
### 2. Using an authenticated FHIR server
  - index.html click button and perform window.FHIR.oauth2.authorize({clientId,scope,redirectUrl:"launch.html"})
  - launch.html and a token or code will be returned after authenticated 
  - app.html window.FHIR.oauth2.ready()... do api call 
### 3. Reference 
- http://docs.smarthealthit.org/client-js/
- http://docs.smarthealthit.org/client-js/client
- http://docs.smarthealthit.org/client-js/fhirjs-equivalents 
- https://docs.smarthealthit.org/tutorials/javascript/ 
![111](https://user-images.githubusercontent.com/20411077/135294332-a6778ac0-fd90-4186-b7cf-4751d52bac07.png)
