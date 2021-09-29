# smart-fhir
perform simple smart on fhir 
1. Using an open FHIR server, just open "open_fhir_server.html" using a liveserver in vscode. 
2. Using an authenticated FHIR server
  - index.html click button and perform window.FHIR.oauth2.authorize({clientId,scope,redirectUrl:"launch.html"})
  - launch.html and a token or code will be returned after authenticated 
  - app.html window.FHIR.oauth2.ready()... do api call 
