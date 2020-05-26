# AirConsole Crack

The following steps allow you to use the AirConsole platform in **Hero** mode for free.

:warning: The following code **MUST** be executed on the client/controller size (**NOT** on screen!). 

## PC Browser
```js
// Execute the following code in the javascript console.
// After executing, you are the hero, every device should be notified about this.
window.app.becomePremium();
```

## iOS Safari, via Shortcuts
This is only possible via [airconsole.com](https://airconsole.com/) in the browser, not in the app.

You have to find a way to execute the following javascript code. (Different to PC code, will throw SecurityError, this is a workaround)
```js
// After executing, you are the hero, every device should be notified about this.
var el = document.createElement("script");
el.innerText = "window.app.becomePremium();";
document.body.append(el);
completion(); // Needed for shortcuts app.
```

To execute custom javascript on safari webpages, you have to create a shortcut in the *Shortcuts* app. Download it on the app store.

1. Create a shortcut and add the javascript above.
2. Add the shortcut to the sharing screen and allow safari webpages.
3. After creating the shortcut, navigate to airconsole.com in safari and press the share button.
4. Activate the shortcut we just created in the previous steps.

![Instructions](https://i.imgur.com/cfx3X1v.png)

## Android
This is only possible via [airconsole.com](https://airconsole.com/) in the browser, not in the app.

I didn't test this on any android device, but find a way to execute the following javascript code.
```js
// After executing, you are the hero, every device should be notified about this.
window.app.becomePremium();
```
