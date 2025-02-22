---
title: "ISocialSessionLoggedOnUserID"
manager: soliver
ms.date: 11/16/2014
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
ms.assetid: 54377ab4-8c69-4d7a-b9b7-278241823c8d
description: "Returns a string that represents the social network user ID of the user who is currently logged on."
---

# ISocialSession::LoggedOnUserID

Returns a string that represents the social network user ID of the user who is currently logged on. 
  
```cpp
[propget] HRESULT _stdcall LoggedOnUserID([out, retval] BSTR* result);
```

## Property value

A string that contains the social network user ID of the logged-on user.
  
## See also

- [ISocialSession::LoggedOnUserName](isocialsession-loggedonusername.md)  
- [ISocialSession : IUnknown](isocialsessioniunknown.md)

