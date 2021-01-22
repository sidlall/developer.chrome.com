---
layout: "layouts/doc-post.njk"
title: "Chrome DevTools"
date: 2016-03-28
updated: 2020-07-10
description: "Get started with Google Chrome&#39;s built-in web developer tools."
---

Chrome DevTools is a set of web developer tools built directly into the [Google Chrome][1] browser.
DevTools can help you edit pages on-the-fly and diagnose problems quickly, which ultimately helps
you build better websites, faster.

{% youtube id="VYyQv0CSZOE" %}

Check out the video for live demonstrations of core DevTools workflows, including debugging CSS,
prototyping CSS, debugging JavaScript, and analyzing load performance.

## Open DevTools {: #open }

There are many ways to open DevTools, because different users want quick access to different parts
of the DevTools UI.

- When you want to work with the DOM or CSS, right-click an element on the page and select
  **Inspect** to jump into the **Elements** panel. Or press Command+Option+C (Mac) or
  Control+Shift+C (Windows, Linux, Chrome OS).
- When you want to see logged messages or run JavaScript, press Command+Option+J (Mac) or
  Control+Shift+J (Windows, Linux, Chrome OS) to jump straight into the **Console** panel.

See [Open Chrome DevTools][2] for more details and workflows.

## Get started {: #start }

If you're a more experienced web developer, here are the recommended starting points for learning
how DevTools can improve your productivity:

- [View and Change the DOM][3]
- [View and Change a Page's Styles (CSS)][4]
- [Debug JavaScript][5]
- [View Messages and Run JavaScript in the Console][6]
- [Optimize Website Speed][7]
- [Inspect Network Activity][8]

## Discover DevTools {: #discover }

The DevTools UI can be a little overwhelming... there are so many tabs! But, if you take some time
to get familiar with each tab to understand what's possible, you may discover that DevTools can
seriously boost your productivity.

!!!.aside.aside--note

**Note:** In the DevTools docs, the top-level tabs are called panels.

!!!

### Device Mode {: #device-mode }

![Device Mode](/web/tools/chrome-devtools/images/device-mode.png)

Simulate mobile devices.

- [Device Mode][9]
- [Test Responsive and Device-specific Viewports][10]
- [Emulate Sensors: Geolocation & Accelerometer][11]

### Elements panel {: #elements }

![Elements Panel](/web/tools/chrome-devtools/images/panels/elements.png)

View and change the DOM and CSS.

- [Get Started With Viewing And Changing The DOM][12]
- [Get Started With Viewing And Changing CSS][13]
- [Inspect and Tweak Your Pages][14]
- [Edit Styles][15]
- [Edit the DOM][16]
- [Inspect Animations][17]
- [Find Unused CSS][18]

### Console panel {: #console }

![Console Panel](/web/tools/chrome-devtools/images/panels/console.png)

View messages and run JavaScript from the Console.

- [Get Started With The Console][19]
- [Using the Console][20]
- [Interact from Command Line][21]
- [Console API Reference][22]

### Sources panel {: #sources }

![Sources Panel](/web/tools/chrome-devtools/images/panels/sources.png)

Debug JavaScript, persist changes made in DevTools across page reloads, save and run snippets of
JavaScript, and save changes that you make in DevTools to disk.

- [Get Started With Debugging JavaScript][23]
- [Pause Your Code With Breakpoints][24]
- [Save Changes to Disk with Workspaces][25]
- [Run Snippets Of Code From Any Page][26]
- [JavaScript Debugging Reference][27]
- [Persist Changes Across Page Reloads with Local Overrides][28]
- [Find Unused JavaScript][29]

### Network panel {: #network }

![Network Panel](/web/tools/chrome-devtools/images/panels/network.png)

View and debug network activity.

- [Get Started][30]
- [Network Issues Guide][31]
- [Network Panel Reference][32]

### Performance panel {: #performance }

!!!.aside.aside--note

**Note:** In Chrome 58 the Timeline panel was renamed to the Performance panel.

!!!

![Timeline Panel](/web/tools/chrome-devtools/images/panels/performance.png)

Find ways to improve load and runtime performance.

- [Optimize Website Speed][33]
- [Get Started With Analyzing Runtime Performance][34]
- [Performance Analysis Reference][35]
- [Analyze runtime performance][36]
- [Diagnose Forced Synchronous Layouts][37]

### Memory panel {: #memory }

!!!.aside.aside--note

**Note:** In Chrome 58 the Profiles panel was renamed to the Memory panel.

!!!

![Profiles Panel](/web/tools/chrome-devtools/images/panels/memory.png) Profile memory usage and
track down leaks.

- [Fix Memory Problems][38]
- [JavaScript CPU Profiler][39]

### Application panel {: #application }

![Application Panel](/web/tools/chrome-devtools/images/panels/application.png)

Inspect all resources that are loaded, including IndexedDB or Web SQL databases, local and session
storage, cookies, Application Cache, images, fonts, and stylesheets.

- [Debug Progressive Web Apps][40]
- [Inspect and Manage Storage, Databases, and Caches][41]
- [Inspect and Delete Cookies][42]
- [Inspect Resources][43]

### Security panel {: #security }

![Security Panel](/web/tools/chrome-devtools/images/panels/security.png)

Debug mixed content issues, certificate problems, and more.

- [Understand Security Issues][44]

## Community {: #community }

File bug reports and feature requests in Crbug, which is the engineering team's bug tracker.

[Crbug][45]

If you want to alert us to a bug or feature request but don't have much time, you're welcome to send
a tweet to @ChromeDevTools. We reply and send announcements from the account regularly.

[Twitter][46]

For help with using DevTools, Stack Overflow is the best channel.

[Stack Overflow][47]

To file bugs or feature requests on the DevTools docs, open a GitHub issue on the Web Fundamentals
repository.

[Docs Issues][48]

DevTools also has a Slack channel, but the team doesn't monitor it consistently.

[Slack][49]

[1]: https://www.google.com/chrome/
[2]: /web/tools/chrome-devtools/open
[3]: /web/tools/chrome-devtools/dom
[4]: /web/tools/chrome-devtools/css
[5]: /web/tools/chrome-devtools/javascript
[6]: /web/tools/chrome-devtools/console/get-started
[7]: /web/tools/chrome-devtools/speed/get-started
[8]: /web/tools/chrome-devtools/network
[9]: /web/tools/chrome-devtools/device-mode
[10]: /web/tools/chrome-devtools/device-mode/emulate-mobile-viewports
[11]: /web/tools/chrome-devtools/device-mode/device-input-and-sensors
[12]: /web/tools/chrome-devtools/dom
[13]: /web/tools/chrome-devtools/css
[14]: /web/tools/chrome-devtools/inspect-styles
[15]: /web/tools/chrome-devtools/inspect-styles/edit-styles
[16]: /web/tools/chrome-devtools/inspect-styles/edit-dom
[17]: /web/tools/chrome-devtools/inspect-styles/animations
[18]: /web/tools/chrome-devtools/coverage
[19]: /web/tools/chrome-devtools/console/get-started
[20]: /web/tools/chrome-devtools/console
[21]: /web/tools/chrome-devtools/console/command-line-reference
[22]: /web/tools/chrome-devtools/console/console-reference
[23]: /web/tools/chrome-devtools/javascript
[24]: /web/tools/chrome-devtools/javascript/breakpoints
[25]: /web/tools/setup/setup-workflow
[26]: /web/tools/chrome-devtools/snippets
[27]: /web/tools/chrome-devtools/javascript/reference
[28]: /web/updates/2018/01/devtools#overrides
[29]: /web/tools/chrome-devtools/coverage
[30]: /web/tools/chrome-devtools/network-performance
[31]: /web/tools/chrome-devtools/network-performance/issues
[32]: /web/tools/chrome-devtools/network-performance/reference
[33]: /web/tools/chrome-devtools/speed/get-started
[34]: /web/tools/chrome-devtools/evaluate-performance
[35]: /web/tools/chrome-devtools/evaluate-performance/reference
[36]: /web/tools/chrome-devtools/rendering-tools
[37]: /web/tools/chrome-devtools/rendering-tools/forced-synchronous-layouts
[38]: /web/tools/chrome-devtools/memory-problems
[39]: /web/tools/chrome-devtools/rendering-tools/js-execution
[40]: /web/tools/chrome-devtools/progressive-web-apps
[41]: /web/tools/chrome-devtools/manage-data/local-storage
[42]: /web/tools/chrome-devtools/manage-data/cookies
[43]: /web/tools/chrome-devtools/manage-data/page-resources
[44]: /web/tools/chrome-devtools/security
[45]: https://crbug.com/new
[46]: https://twitter.com/ChromeDevTools
[47]: https://stackoverflow.com/questions/ask?tags=google-chrome-devtools
[48]: https://github.com/google/webfundamentals/issues/new
[49]: https://chromiumdev.slack.com/messages/devtools/