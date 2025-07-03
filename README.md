# task-7


# 🧼 Task: Identify and Remove Suspicious Browser Extensions


# 🎯 Objective

To recognize potentially harmful browser extensions, understand their security implications, and clean up the browser environment.



# 🛠 Tools Used

* Google Chrome (latest version)
* Chrome Extension Manager
* Google Search (for extension reviews)
* System monitoring for browser performance



### 🔍 Steps Taken

1. Accessed Chrome Extensions:

   * Opened `chrome://extensions/` to view all installed extensions.

2. Reviewed Each Extension:

   * Checked names, developers, and ratings on the Chrome Web Store.
   * Reviewed permissions (e.g., access to all websites, clipboard, tabs, etc.).

3. Flagged Suspicious Extensions:

   * Extensions with vague names, low ratings, or unnecessary permissions were considered suspicious.

4. Removed/Disabled Unnecessary Extensions:

   * Removed 3 outdated or unused extensions.
   * Disabled one extension requesting excessive permissions.

5. Restarted the Browser:

   * Noted improvement in performance and reduced memory usage.

6. Documented Removed Extensions:

   * Removed: “Easy PDF Merge”, “Video Downloader Plus”, “Fast New Tab”
   * Reason: Low ratings, redundant features, or poor developer transparency.



# 🧠 Observations & Learnings

* Many extensions ask for permissions they don’t need.
* Even popular extensions can be bought out and turned malicious.
* Regularly auditing browser add-ons improves system security and browser performance.



#☠️ Risks of Malicious Extensions

| Risk Type               | Description                                                        |
| ----------------------- | ------------------------------------------------------------------ |
| Data Theft              | Access to clipboard or keystrokes may leak sensitive data.         |
| Phishing Redirects      | Redirecting to fake login pages via tab control.                   |
| Tracking & Surveillance | Browsing history, tab activity can be sent to third-party servers. |
| Code Injection          | Malicious JS code can be injected into pages you visit.            |





### 📚 Interview Questions & Professional Answers

1. How can browser extensions pose security risks?
They can access your browsing data, modify content on webpages, steal credentials, or install trackers if given excessive permissions.

2. What permissions should raise suspicion?
Permissions like *"Read and change all your data on the websites you visit"*, *"Access to clipboard"*, or *"Manage your downloads"* are red flags unless absolutely necessary.

3. How to safely install browser extensions?

* Install only from official web stores.
* Check developer name, reviews, and number of users.
* Avoid newly published or low-rated tools.

4. What is extension sandboxing?
Sandboxing limits what the extension can access in your system or browser. It prevents one extension from interfering with others or accessing OS-level resources.

5. Can extensions steal passwords?
Yes. Malicious extensions can record keystrokes, access password fields, or monitor clipboard contents.

6. How to update extensions securely?

* Allow auto-updates from trusted sources only.
* Regularly check the changelog and permissions.
* If permissions change unexpectedly, uninstall the extension.

7. Difference between extensions and plugins?

* **Extensions**: Add functionality to browsers and run within browser’s security model.
* **Plugins**: External software like Flash or Java that integrate with the browser (now mostly deprecated due to security risks).

8. How to report malicious extensions?

* Use the “Report abuse” option on Chrome Web Store.
* Provide details and screenshots.
* You can also report to Google Safe Browsing if it affects multiple users.
