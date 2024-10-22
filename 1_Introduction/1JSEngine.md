### Node.js
- an open-source, cross-platfrom JS runtime environment

***Open source***: source code is publicly available for sharing and modification

***Cross platform***: available on Mac, Windows and Linux

***JS runtime environment***: provides all the necessary **components** in order to use and run a JS program **outside the browser**

---
### JS Engine & Node.js
- `V8 Engine` open source JavaScript Engine, developed by Google, sitting at the **core of Node.js**
- embedding V8 into C++ application, you can write C++ node that gets executed when a user writes **JS code**
- `Node` enables you to add new features to JS, and C++ has its own benefits of handling low level functions like file handling, database connections and network operations.
- `C++` program can run `ECMAScript` and additional features that you choose to incorporate.
- `Node.js` consists of C++ files which **form the core features** and JS files which expose **common utilities** and some of the **C++ features** for **easier consumption**.

#### Chrome Browser JS Runtime
1. V8 JS Engine - Memory + Call stack
2. Event Loop
3. Microtask Queue + Callback / Task Queue
4. WEB/BROWSER APIs(DOM, Storage, Timers), not included in `Node.js`

#### Constructure of Node.js Source Code
1. `deps`-v8, libuv
2. C/C++ features
3. `lib`-JS lib