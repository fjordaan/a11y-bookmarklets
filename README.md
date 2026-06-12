# A11Y Bookmarklets

A collection of browser bookmarklets for accessibility testing and inspection.

---

## Installation

### 📥 Download

Download **[A11Y bookmarks.html](./A11Y%20bookmarks.html)** from this repository.

---

### 🦊 Firefox

1. Save the downloaded file somewhere easy to find (e.g. your Desktop).
2. Open the Bookmarks Library:
   - **Windows/Linux:** `Ctrl` + `Shift` + `O`
   - **macOS:** `⌘` + `Shift` + `O`
   - Or go to **Bookmarks → Manage Bookmarks** in the menu bar.
3. In the Library window, click **Import and Backup** in the toolbar, then choose **Import Bookmarks from HTML…**
4. Browse to the downloaded file and click **Open**.
5. The **A11Y** folder will appear in your Bookmarks Toolbar. If the toolbar isn't visible, right-click the Firefox toolbar area and select **Bookmarks Toolbar → Always Show**.
6. Navigate to any webpage and click a bookmarklet from the A11Y folder to run it.

> **Note:** Importing does not overwrite your existing bookmarks — Firefox adds the imported folder alongside whatever you already have.

---

### 🌐 Chrome / Edge / Brave

1. Save the downloaded file somewhere easy to find.
2. Open the Bookmarks Manager:
   - **Windows/Linux:** `Ctrl` + `Shift` + `O`
   - **macOS:** `⌘` + `Shift` + `O`
   - Or go to **⋮ menu → Bookmarks → Bookmark manager**.
3. Click the **⋮** (three-dot) menu at the top-right of the Bookmark Manager page and choose **Import bookmarks**.
4. Browse to the downloaded file and click **Open**.
5. The **A11Y** folder will appear in your Bookmarks Bar. If the bar isn't visible:
   - **Windows/Linux:** `Ctrl` + `Shift` + `B`
   - **macOS:** `⌘` + `Shift` + `B`
6. Navigate to any webpage and click a bookmarklet from the A11Y folder to run it.

> ⚠️ **Chrome security note:** Chrome may block bookmarklets pasted directly into the address bar. Always *click* the bookmarklet from the bookmarks bar — do not drag the URL into the address bar to run it.

---

## Usage

Once installed, navigate to any webpage and click a bookmarklet from the **A11Y** folder in your bookmarks bar. Most tools inject a panel or overlay directly into the page. Click again or press `Esc` to dismiss overlays where supported.

No extensions, accounts, or internet connection required for most tools — everything runs locally in your browser.

---

## What's included

| Bookmarklet | Description |
|---|---|
| 🔍 Look up WCAG Success Criteria | Search and browse all WCAG 2.2 success criteria, filter by level and version, copy as Markdown/HTML links |
| 🏷️ Highlight `aria-label` | Outlines all elements with `aria-label` and displays their values |
| 🔗 Highlight `for` and `id` | Shows label–input associations via `for`/`id` pairs |
| 🔗 Highlight `aria-labelledby` | Outlines elements using `aria-labelledby` and their referenced elements |
| 🔗 Highlight `aria-describedby` | Outlines elements using `aria-describedby` and their referenced elements |
| 🔗 Highlight `aria-controls` and `id` | Shows `aria-controls` relationships |
| ⚠️ Highlight `required` / `aria-required` | Marks all required form fields |
| ❌ Highlight `aria-invalid` | Marks all fields currently in an invalid state |
| ✅ Highlight `autocomplete` | Displays `autocomplete` attribute values on form fields |
| 🖼️ Highlight image alternatives | Outlines images and overlays their `alt` text |
| 🔢 Reveal Focus Order | Lists all focusable elements in tab order and optionally draws the tab path |
| 👁️ Show focus styles | Forces focus on every focusable element to reveal its focus style |
| 🎨 Contrast Checker | Opens the WebAIM contrast checker as a draggable overlay |
| 📋 Easy Checks headings checker | Displays the page's heading structure in a side panel |
| 🖼️ List images | Opens a new window listing all images with accessible names and flagged issues |
| 🔗 List links | Opens a new window listing all links with accessible names and flagged issues |
| 📊 Tables | Highlights table structure and attributes |
| 🗺️ Landmarks | Visualises ARIA landmark regions on the page |
| 🎯 WTFocus | Shows accessible name, role, and description for the focused element |
| 📑 Headings Bookmarklet | Highlights all headings on the page |
| 🔢 Tabindex Bookmarklet | Displays `tabindex` values on all elements that have them |
| ⌨️ Keypress visualizer | Shows a real-time overlay of keys being pressed |
| 📐 Viewport Details | Displays viewport size, zoom level, and colour scheme in an overlay |

---

## Credits and acknowledgements

The bookmarklets in this collection are the work of talented accessibility practitioners. I did not create them — I have simply gathered them in one place for convenience. My sincere thanks to all the authors.

| Bookmarklet(s) | Author | Source |
|---|---|---|
| Look up WCAG Success Criteria | **Ian Lloyd (Lloydi)**, Principal Accessibility Specialist at TetraLogical | [a11y-tools.com](https://a11y-tools.com/blog/2025/08/new-bookmarklet-wcag-lookup-tool/) |
| Reveal Focus Order, Show focus styles, List images, List links, WTFocus, Viewport Details | **Ian Lloyd (Lloydi)** | [a11y-tools.com/bookmarklets](https://a11y-tools.com/bookmarklets/) |
| Headings Bookmarklet, Tabindex Bookmarklet, Tables | **Paul J. Adam**, Web & Mobile Accessibility Consultant | [pauljadam.com/bookmarklets](https://pauljadam.com/bookmarklets/) |
| Landmarks | **Landi Lark, Nick Hoyt, Jon Gunderson** and contributors (Pixo / DRES, University of Illinois) | [accessibility-bookmarklets.org](https://accessibility-bookmarklets.org/) |
| Highlight autocomplete | **Rachele DiTullio**, Senior Accessibility Engineer | [racheleditullio.com](https://racheleditullio.com/blog/2023/11/autocomplete-accessibility-bookmarklet/) |
| Contrast Checker | **WebAIM** | [webaim.org](https://webaim.org/resources/contrastchecker/) |
| Easy Checks headings checker | **W3C Web Accessibility Initiative (WAI)** | [w3.org/WAI/test-evaluate/easy-checks](https://www.w3.org/WAI/test-evaluate/easy-checks/headings/) |
| Highlight aria-label, aria-labelledby, aria-describedby, aria-controls, aria-invalid, aria-required, autocomplete, for/id, image alternatives | Source unknown — please [open an issue](../../issues) if you know the origin |  |

If you are the author of any bookmarklet listed here and would like to be credited, have corrections, or would prefer your work not be included, please [open an issue](../../issues) or get in touch.
