---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var bookingStaffMemberBase = await graphClient.Solutions.BookingBusinesses["{bookingBusiness-id}"].StaffMembers["{bookingStaffMemberBase-id}"]
	.Request()
	.GetAsync();

```