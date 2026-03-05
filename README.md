# ChatGPT Chat Counter

Ts just sad 💀

## How to See How Many Chats You Have

1. Open ChatGPT in your browser.
2. Scroll through all your chats in the sidebar **until you reach the bottom** so everything loads.
3. Open the **Developer Console**:

   * **Windows / Linux:** `Ctrl + Shift + I`
   * **Mac:** `Cmd + Option + I`
4. Go to the **Console** tab.
5. Paste the script below and press **Enter**.

```javascript
document.querySelectorAll('nav a').length
```

6. The console will return a number — that is the **total number of visible chats** in your sidebar.

## Notes

* This **does not include deleted chats**.
* This **does not include hidden or archived chats**.
* Make sure you **scroll to the very bottom first**, otherwise some chats won’t be counted.

💀 If the number is huge… you might want to touch grass.
