I'm a software developer specializing in information security, reverse engineering, browser fingerprinting & bot detection.

I maintain several open source repositories here on GitHub.

You can contact me at Joe@dreggle.com. My PGP key is available [here](https://keys.openpgp.org/search?q=Joe%40dreggle.com) if you for some reason require increased confidentiality.

That's about it.

--

Here are my current active projects as of June 2024:

- [detectIncognito](https://github.com/Joe12387/detectIncognito) - A TypeScript/JavaScript library for detecting the use of incognito mode or a similar private browsing mode when a browser visits a site. Works with all browsers with compatability for old browsers going back approximately 10 years.
- [Browser Fingerprinting Resistance Research Repo](https://github.com/Joe12387/browser-fingerprinting-resistance-research) - Documentation on the current state of browser fingerprinting, browsers' attempts at mitigating such techniques, and the current trackability of all browsers (hint: it's basically all of them).

These project(s) are currently stagnent or deprecated in favor of an unreleased replacement project:

- [Overpowered Browser Fingerprinting Script (OPFS)](https://github.com/Joe12387/OP-Fingerprinting-Script) - Released in 2022, this is a browser fingerprinting library that featured certain techniques that were non-public at the time of publishing such as [\[brave/brave-browser\] Issue #24681](https://github.com/brave/brave-browser/issues/24681). I am currently working on a replacement for this library that allows a certain level in change in the browser fingerprint while still being trackable, increasing the lifespans of fingerprint IDs from weeks or months to potentially multiple years. It also includes improved techniques including non-public ones. If you are a company that is interested in this technology and may be interested in purchasing licensing for commercial purposes, send me an email and if we make a deal I'll expedite development. There will also be an open source version of this library for non-commercial use only at some point, but some techniques will remain closed source in order to attempt to prevent Orwellian cross-site surveillance. Potential licencees may be required to sign a contract that requires user concent regardless of applicable privacy regulations prior to fingerprinting similar to a cookie dialog, so I can sleep at night knowing I haven't completely killed privacy.

--

Also, I don't have anywhere to put my list of reported security vulnerabilities, so here they are:

- Reported March 2024: [CVE-2024-27830](https://github.com/Joe12387/safari-canvas-fingerprinting-exploit) - addressed in Safari 17.5
- Reported August 2022: [\[brave/brave-browser\] Issue #24681](https://github.com/brave/brave-browser/issues/24681) - addressed in Brave 1.47
