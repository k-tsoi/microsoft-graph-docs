
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/me/outlook/taskFolders/AAMkADIyAAAhrbPXAAA=')
	.version('beta')
	.delete();

```