
```Cs

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Me.Outlook.TaskGroups["AAMkADIyAAAhrbe-AAA="]
	.Request()
	.DeleteAsync();

```