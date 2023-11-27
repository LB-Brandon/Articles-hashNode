---
title: "[Android]Webcomic Viewer APP"
datePublished: Mon Nov 27 2023 05:46:01 GMT+0000 (Coordinated Universal Time)
cuid: clpghk9bq00050bkye41ydx1g
slug: androidwebcomic-viewer-app
tags: android

---

# Overview
This app allows users to conveniently manage their favorite webtoon pages. The app features three tabs for viewing webtoons, and a 'Back to Last Scene' button allows users to easily return to the episode they were watching. Users can customize the names of each tab, and access to URLs other than Naver Webtoon is blocked.

## What I learned
- Utilizing TabLayout with `ViewPager2`
- <u>SharedPreferences Implementation</u>
- <u>Custom Listener</u> for Dynamic Tab Name Change
- `WebView` and Its Functionality

## Troubleshooting
### Issue: `err_access_denied` Occurs on App Installation and Startup
- Symptoms: Users encounter the err_access_denied error when installing and launching the app.
- Resolution:
Action: Re-install the app
- Explanation: This error may be due to a glitch during the initial installation. Re-installing the app often resolves this issue by ensuring a clean and complete installation process.

## Something I’m not sure about
- How does the WebView know if it’s available to move back or not?

## What could be better
- Manage constant values in a separate file

##  GitHub link
%[https://github.com/LB-Brandon/WebcomicViewer_APP]