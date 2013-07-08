# jQbrick

`jQbrick` is a **components library for Mobile App** I like do define _"Bricks for Mobile App Directors"_.  
It is build over _jQuery_ and _BackboneJS_, and it uses _jQueryMobile_ as UI toolkit to produce well structured Mobile Apps.

_RequireJS_ is the glue between all blocks and allow to optimize your Application in production stage.


## Where "jQbrick" cames from?
`jQbrick` comes from a `jQMBR` reengineering process.  
The name is a mix of "bricks" to highlight the **components library** nature of this project.

You speak "jQubrick" as "jay" + "Kubrick" (the American film director).  
I like to refer to a very important film director because - in my intention - **you will use
`jQbrick` components as actors in you Mobile Application**.




## What's Provided?

Forkig or downloading this repo will provide you a fully functional test application:
a "kitchen sink" where I put all provided features into a real Mobile App.


## Documentation:
To create documentation it is a real challenge for no-profit projects!  
For the moment all documentation is provieded through comments in demonstrational code blocks
but I hope to find the time to write down a wiki here in GitHub!

Contributors are welcome!


## Targets:
- full AMD
- no static HTML, JS templates are welcome
- code declarative!
- run apps on iOS and Android browser
- run apps on GoogleChrome, Safari, Firefox (IE? What that s**t?)
- wrap apps with PhoneGap, deploy on iOS and Android

## Optimize for Production:
`jQbrick` comes with a built-in _RequireJS_ optimization script you can find under
`/js` folder.

**NOTE:** You need _node.js_ running on your machine to perform following actions!

To run optimizer:
- open a console window 
- navigate to the `.../jQbrick/js/` folder
- `node r.js -o require.build.js`

a new folder named **"AppDeploy"** will be created under your app's root:  
`.../jQbrick/AppDeploy/`

Here you can completely remove `/js` and `/less` directory obtaining a **compressed
production version** of you App.