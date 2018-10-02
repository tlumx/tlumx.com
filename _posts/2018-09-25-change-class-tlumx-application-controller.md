---
layout: post
title: "Tlumx Framework 2.0.1 released"
description: "Make changes in Tlumx\\Application\\Controlle base class"
---
Tlumx Framework 2.0.1 released.

We changes Tlumx\Application\Controlle base class. 

Now, each action method of controller, that inherited from the base class "Tlumx\Application\Controlle", takes the current request object as parameter.

```bash
public function indexAction(ServerRequestInterface $request)
{
	...
}
```
