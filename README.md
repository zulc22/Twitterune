# Twitterune
CSS Userstyle for Twitter, mimicing Deltarune's dialog visuals

![](preview.png)

To use userCSS themes, you need to have the [Stylus extension](https://github.com/openstyles/stylus#releases) installed on your browser. (Click on 'Chrome Web Store' on their page for Chrome, 'Firefox add-ons' for Firefox)

Be aware that I only test this theme on Firefox; if you have any specific problems make sure to look in the [GitHub Issue tracker for this repo](https://github.com/zulc22/Twitterune/issues). Currently the custom buttons do not work at all in Chromium browsers (and I do not know how to fix it).

Make sure to set your Twitter theme to Dim or Lights Out with the theme applied for it to look right. (Click on "More"/the three dots on the left, Settings and Support, then Display to change it.)

Install the userCSS [directly from the repo](https://github.com/zulc22/Twitterune/raw/main/twitterune.user.css), or alternatively, there is [a userstyles.world page for this theme](https://userstyles.world/style/6884/twitterune).

Due to CSP (content security policy), the theme's buttons will not work correctly in Chrome, and even in Firefox (the browser I primarily develop it for), you need to manually install ["Determination Mono Web"](https://www.fontspace.com/determination-mono-web-font-f23209) (click the three dots next to 'Regular Style' and download) onto your system.

If anyone knows how to skirt CSP in Chrome for the SVG files, or for fonts, please let me know by making an issue, or even better a pull request to outright fix it. Otherwise I cannot help you, as it is an _intentional_ browser feature preventing it from working. It's possible a Userscript would be able to work around these issues, but I don't want to threaten the security of the people using this theme by injecting JavaScript into their Twitter pages.
