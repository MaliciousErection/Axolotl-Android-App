## Description

Axolotl is the companion Android application to go along with Malicious Erection's "Pentesting Exploits Noted In Smartphones" training course. You are free to use this application however you want, but it is recommended that you take the course to fully understand this application.

* Information about the "Pentesting Exploits Noted In Smartphones" course can be found here: <URL coming soon>
* Video lectures of the "Pentesting Exploits Noted In Smartphones" course can be found here: <URL coming soon>

Axolotl is essentially split into two parts:

* The "Examples Part"
  * In this area, the user is taught about a specific topic
* The "Main Part"
  * The rest of Axolotl is vulnerable to different vulnerabilities
  * You should learn about the topics demonstrated in the "Examples Part" before trying to find and exploit the rest of Axolotl

## Download

The latest version of Axolotl can be found in the Releases section of this repo (https://github.com/MaliciousErection/YayAndroidTrainingYay_Axolotl-App/releases)

## List Of Topics

Below are the list of vulnerabilities that Axolotl teaches and is vulnerable to. As previously stated, you should take the "Pentesting Exploits Noted In Smartphones" course to fully understand the below vulnerabilities:

1. **Understand `getIntent()`** - An overview on what `getIntent()` does in Android applications and how to create Intents
2. **Browsable Intents (and DeepLinks)** - How to craft Browsable Intents and craft exploits via one-tap browser clicks
3. **NFC Intents** - Crafting Intents via NFC Tags (requires a physical phone with a NFC reader)
4. **Unexported Content Provider** - Abusing the `grantUriPermissions` setting in unexported Content Providers
5. **Executing JavaScript Bridges** - Learn what JavaScript Bridges are and how they can be dangerous in WebViews
6. **Exfiltrating files via WebView Misconfiguration** - Learn about the `setAllowFileAccessFromFileURLs` WebView setting and how they can be abused
7. **Abusing Custom Permissions** - Creating Android applications with custom permissions for exploitation
8. **File Theft Via Mime Type** - Hijacking files via an application's "share" functionality
9. **Execute Custom DEX File** - Crafting custom DEX files that get dynamically loaded into an application
