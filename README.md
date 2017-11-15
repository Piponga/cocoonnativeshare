
###Example

```javascript
	Cocoon.Share.share({
            message: "I have scored more points on Flappy Submarine!! Chooo choooo",
            image: "http://www.myserver.com/myimage.png"
        }, function(activity, completed, error){
            console.log("Share " + completed ? 'Ok' : 'Failed');
        });
```

#License

Mozilla Public License, version 2.0

Copyright (c) 2015 Ludei 

See [`MPL 2.0 License`](LICENSE)
