
```Cs

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var comment = "Updating the latest guidelines";

await graphClient.Drives["{drive-id}"].Items["{item-id}"]
	.Checkin(checkInAs,comment)
	.Request()
	.PostAsync()

```