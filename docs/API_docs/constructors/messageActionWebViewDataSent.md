---
title: "messageActionWebViewDataSent"
description: "Data from an opened reply keyboard bot web app was relayed to the bot that owns it (user side service message)."
nav_exclude: true
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messageActionWebViewDataSent  
[Back to constructors index](/API_docs/constructors/index.html)



Data from an opened [reply keyboard bot web app](https://core.telegram.org/api/bots/webapps) was relayed to the bot that owns it (user side service message).

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|text|[string](/API_docs/types/string.html) | Yes|Text of the [keyboardButtonSimpleWebView](../constructors/keyboardButtonSimpleWebView.html) that was pressed to open the web app.|



### Type: [MessageAction](/API_docs/types/MessageAction.html)


### Example:

```
$messageActionWebViewDataSent = ['_' => 'messageActionWebViewDataSent', 'text' => 'string'];
```  
