
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const directoryObject = {
  directoryObject: {
  }
};

let res = await client.api('/applications/{id}/owners')
	.version('beta')
	.post({directoryObject : directoryObject});

```