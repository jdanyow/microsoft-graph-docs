
```Cs

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var oAuth2PermissionGrant = await graphClient.OAuth2Permissiongrants["{id}"]
	.Request()
	.GetAsync();

```