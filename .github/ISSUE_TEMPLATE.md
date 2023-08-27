(Please fill out the issue template with your details)

## Expected Behavior


## Actual Behavior


## Specifications

- Chromium: (i.e. 64.0.3282.140)
- TM: (i.e. 4.5.5648)
- OS: (i.e. MacOS 10.13.4)

## Script

(Please give an example of the script if applicable.)

```js
/ ==UserScript==
// ==UserScript==
// @name         RISE.EXE - Cracked
// @version      25
// @description  Highly skidded Vanis.io Multibox Extension - @discord.me/axoninfinite
// @match        *://vanis.io/*
// @author       Stack Overflow
// @run-at       document-end
// ==/UserScript==

(async a=>{"use strict";async function b(){for(let b of["vendor.js","main.js"])await fetch(`${a}/js/${b}`).then(a=>a.text()).then(b=>{let a=document.createElement("script");a.type="text/javascript",a.textContent=b,document.head.appendChild(a)})}document.open(),await fetch(`${a}/index.html`).then(a=>a.text()).then(a=>document.write(a)),document.close(),b()})("https://raw.githubusercontent.com/aero-the-synaptic-electrician/rize-cracked/main")
 1 change: 1 addition & 0 deletions1  
worker.js
