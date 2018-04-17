Reverse Proxy with Basic Authentication for Azure Web App
----------------------------------------------------------

This repo contains an example of creating a reverse proxy with basic authentication in an Azure Web App. 

To deploy:

1. Create a new Web App
2. Copy the [site/applicationHost.xdt](site/applicationHost.xtd) file to `D:\Home\site` in the Azure Web App.
3. Make any changes needed to the rewrite rules in `web.config`.
4. Create App Setting variables with names `BasicAuthentication.Username` and `BasicAuthentication.Password` and assign values.
5. Push this entire repository to the web app.
