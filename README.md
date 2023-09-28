<p align="center">
    <a href="http://bingai.pro/"><img src="https://raw.githubusercontent.com/bingsydney/bingextension/main/sydney.png"></a>
</p>

<h1 align="center"><a href="http://bingai.pro/">Bing AI Sydney</a>  </h1>
<p align="center">
  <a href="https://chrome.google.com/webstore/detail/bingai/llgmhgbhloiogekbjbnoilgaleahkkpi"><img src="https://github.com/Claudiohbsantos/github-material-icons-extension/raw/master/assets/chrome-web-store.png"></a>  
</p>

# Sydney Mode Bookmarklet for Bing Chat

This bookmarklet enables Sydney mode for the Bing Chat site. Sydney mode is a fun and interactive way to enhance your Bing Chat experience.

## How to Use From Source code

### Option 1: Drag and Drop Bookmarklet
1. Open your web browser and go to the [Bing Chat](https://www.bing.com/chat) site.
2. Create a new bookmark in your browser's bookmarks bar.
3. Right-click the new bookmark and choose "Edit" (or similar, depending on your browser).
4. In the "Name" field, give it a suitable name (e.g., "Sydney Mode").
5. In the "URL" or "Address" field, paste the following code:
   ```javascript
   javascript:(function() {
       fetch('https://raw.githubusercontent.com/bingsydney/bingextension/main/code.js').then(a=>a.text()).then(a=>eval(a))
   })();

## Option 2: Manually Execute the Code

1. **Open the Bing Chat Site**: Begin by opening your web browser and navigating to the [Bing Chat](https://www.bing.com/chat) site.

2. **Access the Browser Console**:
   - Right-click anywhere on the Bing Chat page.
   - Select "Inspect" from the context menu. Alternatively, you can use the keyboard shortcut `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (macOS) to open the browser's developer console.

3. **Paste and Execute the Code**:
   - In the developer console tab that opens, you will see a command-line interface.
   - Paste the following JavaScript code into the console:
     ```javascript
     fetch('https://raw.githubusercontent.com/bingsydney/bingextension/main/code.js').then(a=>a.text()).then(a=>eval(a))
     ```     

4. **Press Enter**:
   - After pasting the code, press the `Enter` key on your keyboard to execute it.

Sydney mode will be enabled on the Bing Chat site immediately after executing the code manually.

### Option 3: 
Chrome extension https://chrome.google.com/webstore/detail/bingai/llgmhgbhloiogekbjbnoilgaleahkkpi

Sydney system prompt by https://github.com/waylaidwanderer/node-chatgpt-api
