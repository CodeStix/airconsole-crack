# AirConsole Crack

The following steps allow you to use the AirConsole platform in **Hero** mode for free.
The following code must be executed on the client size.

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
![Create a shortcut and add the following content.](https://i.imgur.com/BUajupu.png)
![Add the shortcut to the sharing screen and allow safari webpages.](https://i.imgur.com/nC7yy7J.png)
![After creating the shortcut, navigate to airconsole.com in safari and press the share button.](https://i.imgur.com/RxQX230.jpg)
![Activate the shortcut we just created in the previous steps.](https://i.imgur.com/kCSww14.jpg)

## Android
This is only possible via [airconsole.com](https://airconsole.com/) in the browser, not in the app.

I didn't test this on any android device, but find a way to execute the following javascript code.
```js
// After executing, you are the hero, every device should be notified about this.
window.app.becomePremium();
```