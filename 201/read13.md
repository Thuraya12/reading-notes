# Read13

# “The Past, Present, and Future of Local Storage for Web Applications”

One of the things that are good for native applications is taking advantage of accessing local storage to store data that are needed for the application in thr regitery, INI files, XML fils or other places, unlike web applications which lack this thing.
**Cookies** were found early in web's history and are used to store small data amounts, they slow down the application because they are sent with every HTTP request and limited with 4kb of data, and they send data without encryption.


## History of local storage hacks before HTML5
When browsers were competing, Microsoft ended the the first browser wars with it's **internet explorer** and added the great **DHTML Behaviors** which had a behavior called **userData** which increased web pages storage to 64kb and 640 kb for trusted domains such as intranet sites. Then adobe made the storage 100kb per domain with its flash cookies,and then the AJAX mssive storage system. 


## Introducing HTML5 storage
HTML5 storage was referred to as **web storage** and then changed for political reasons and it is referred to as **Local storage** and **DOM storage**.
HTML5 storage is the webpages way of saving named key/value pairs locally.

## using HTML5 storage
Using HTML5 storage by storing data on the key/value pairs name and we can access data back with the same key names.

## Tracking Changes toThe HTML5 Storage Area
We can use **storage** event to track storage area changes when setItem(), removeItem(), or clear() are used and the storage is fired in the window, and there's nothing fired when sitting an item to an existing value because there is no storage change.


## HTML5 storage in Action
With HTML5, you complete from where you left off, which means when exiting something like a game, you wont lose your progress, it stores progress locally.
This happens using a function which is called everytime changes are made.