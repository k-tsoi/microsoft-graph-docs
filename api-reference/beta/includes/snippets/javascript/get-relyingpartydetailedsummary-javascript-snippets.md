---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/reports/getRelyingPartyDetailedSummary(period='period_value')')
	.version('beta')
	.get();

```