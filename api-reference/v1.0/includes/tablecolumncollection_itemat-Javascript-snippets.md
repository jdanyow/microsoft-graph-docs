
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const workbookTableColumn = {
  index: 3
};

let res = await client.api('/me/drive/items/{id}/workbook/tables/{id|name}/columns/itemAt')
	.post({workbookTableColumn : workbookTableColumn});

```