---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var group = new Microsoft.Graph.TermStore.Group
{
	DisplayName = "myGroup"
};

await graphClient.TermStore.Groups
	.Request()
	.AddAsync(group);

```