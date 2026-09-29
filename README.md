# AdSilence for Chrome — Free Ad Blocker Extension (Manifest V3)

[![Chrome Web Store](https://img.shields.io/badge/Chrome-Web%20Store-4285F4?logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/aapplploeajcbogegjgnnfgapdjjmoin)
[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![Manifest V3](https://img.shields.io/badge/Manifest-V3-success)](https://github.com/businessLNU/adsilence)

The built release of **AdSilence**, a free, open-source **ad blocker for Google Chrome** and every Chromium browser: **Brave**, **Opera**, **Vivaldi** and **Microsoft Edge**. Version 1.0.3.

AdSilence is a **Manifest V3 ad blocker**, **pop-up blocker**, **tracker blocker** and **cookie banner blocker** in one Chrome extension. It does **not** request the `webRequest` permission: Chrome applies the rules itself through `declarativeNetRequest`, so your browsing history never passes through us. A **uBlock Origin alternative for Chrome** that runs under Manifest V3.

## What it blocks — free, no account

- Ads, video ads and sponsored content
- **YouTube ads**, using uBlock Origin's YouTube filters and scriptlets
- Pop-ups, pop-unders and forced redirects
- Trackers, analytics and disguised first-party trackers
- Malware and malvertising domains (URLhaus)
- Cookie consent banners (GDPR pop-ups)
- Sponsored posts on Facebook and Instagram

32 filter lists including EasyList, EasyPrivacy and uBlock filters; the regional list for your browser language is switched on automatically. No acceptable-ads whitelist.

**Premium (optional):** fingerprint protection, automatic cookie consent answers and phishing warnings.

## Install in Chrome

The easiest way: **[AdSilence in the Chrome Web Store](https://chromewebstore.google.com/detail/aapplploeajcbogegjgnnfgapdjjmoin)**. Requires Chrome 121 or newer. Brave, Opera, Vivaldi and Edge install from the same page.

To load this build manually (developer mode):

1. Download the ZIP from [Releases](../../releases) and unpack it
2. Open `chrome://extensions` and switch on **Developer mode**
3. Click **Load unpacked** and select the unpacked folder

## Measured

100 of 100 points on [adblock-tester.com](https://adblock-tester.com/) with factory settings (5 September 2026, version 1.0.0). Method and comparison: [adsilence.net/en/adblocker-test](https://adsilence.net/en/adblocker-test)

## FAQ

**Is this the same as the Chrome Web Store version?**
Yes. This repository is written automatically by the release pipeline, and every version matches, file for file, the package submitted to the Chrome Web Store — so you can check exactly what you install. Right after a release the store may still show the previous version until its review is done.

**Does it work in Brave, Opera, Vivaldi and Edge?**
Yes. All Chromium-based browsers install Chrome extensions from the Chrome Web Store.

**Where is the source code?**
In [businessLNU/adsilence](https://github.com/businessLNU/adsilence), under the GNU GPL v3.

## Links

- Website: [adsilence.net](https://adsilence.net)
- Ad blocker for Chrome: [adsilence.net/en/adblocker-for-chrome](https://adsilence.net/en/adblocker-for-chrome)
- Firefox version: [adsilence-firefox](https://github.com/businessLNU/adsilence-firefox)
- Bugs and questions: [Issues](../../issues)

---

**Keywords:** Chrome ad blocker · ad blocker for Chrome · adblock Chrome · free ad blocker · Manifest V3 ad blocker · MV3 · Chrome extension · uBlock Origin alternative · YouTube ad blocker · pop-up blocker · tracker blocker · cookie banner blocker · privacy extension · Brave · Opera · Vivaldi · Microsoft Edge · Chromium · Werbeblocker für Chrome · bloqueur de pub Chrome
