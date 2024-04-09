# iOS recruitment test task

### Carbon Certificates app
Create the application displaying the list of available Carbon certificates with a possibility to save them to favourites.

##### Features
###### "Certificates" page - the list of available Carbon certificates 
- Saving the certificate as a favourite (client-side only)

###### "Favourites" page - the list of saved Carbon Certificates
- Same page as "Certificates" with a possibility to remove the certificate from favourites

##### Technical informations
For fetching the certificates use this endpoint:
`https://demo.api.agreena.com/api/public/carbon_registry/v1/certificates?includeMeta=true&page=1&limit=10`

(`API-ACCESS-TOKEN` header with value `Commoditrader-React-FE-Farmer` is needed to authenticate the endpoint)

Keep in mind that there could be more than 10 certificates.

Mockup for the certificates table:
![Mockup](/1.png)

Use this as a template for each row in the list:

```
ID: {id}
ORIGINATOR: {company name} / {country}
OWNER: {company name} / {country}
STATUS: {status}
```
Keep in mind that each row should have a bookmark button as well. 

##### Requirements
- Application should be written in Swift using Combine
- API calls can be made using any library but we suggest using Moya + MoyaCombine https://github.com/Moya/Moya
- Application should have a simple UX/UI
- Application code quality is very important
- Spend no more than 4 hours on the assignment

If you have any other ideas how to make this app working and looking better - feel free to implement it!

### Good luck!
