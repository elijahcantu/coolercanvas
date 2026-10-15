# Cooler Canvas: Chrome Web Store listing text

Paste-ready text for the developer dashboard. Upload `cooler-canvas.zip` from the repo root.

## Store listing tab

**Title (from package):** Cooler Canvas

**Summary (from package):** A free, open-source way to customize Canvas: dark mode, themes, GPA calculator, reminders, and more.

**Category:** Education (or Workflow & Planning)

**Language:** English (United States)

**Description:**

```
Make Canvas easier on the eyes and easier to keep up with. Cooler Canvas adds dark mode, custom themes, a GPA calculator, assignment reminders, and a better to-do list to your school's Canvas site.

Based on the last MIT-licensed open-source release of Better Canvas (5.12.6) by ksucpea. Free forever, no account, no paywall. Not affiliated with Better Canvas, BetterCampus, or Instructure.

FEATURES
• Dark mode with adjustable colors, plus auto dark mode on a schedule or matching your device
• Custom dashboard card images, names, and colors
• Assignments due shown directly on each course card
• Grade percentage badge on each card and a GPA calculator with weighted and cumulative options
• A better to-do list with announcements, labels, custom tasks, and completion tracking
• Pop-up reminders for assignments due soon, even when you are not on Canvas
• Custom fonts, condensed cards, dashboard notes, and custom CSS
• Built-in themes and import/export so you can share your setup
• Available in 11 languages

PRIVACY
Your data stays in your browser. The extension only talks to your school's Canvas site and never sends anything to the developer. No tracking, no analytics, no ads.

OPEN SOURCE
Source code and issue tracker: https://github.com/elijahcantu/coolercanvas

Canvas is a trademark of Instructure, Inc. This extension is not affiliated with or endorsed by Instructure.
```

**Store icon:** `icon/icon-128.png`

**Screenshots:** `store/screenshot-1-dashboard.png` (1280x800)

**Small promo tile:** `store/promo-440x280.png`

**Marquee promo tile:** `store/marquee-1400x560.png`

**Homepage URL:** https://github.com/elijahcantu/coolercanvas

**Support URL:** https://github.com/elijahcantu/coolercanvas/issues

**Mature content:** No

## Privacy tab

**Single purpose description:**

```
Cooler Canvas customizes the appearance of the Canvas LMS (dark mode, themes, fonts, card images) and adds study aids to the Canvas dashboard: assignments due on each course card, a grade badge and GPA calculator, a better to-do list, and assignment reminders.
```

**storage justification:**

```
Used to save the user's settings (dark mode colors, themes, custom card images, fonts, feature toggles), saved themes, custom to-do items, and a backup of settings for the "revert" feature. All of this is stored in the browser via chrome.storage and is never sent to the developer.
```

**Host permission justification:**

```
Canvas is hosted on each school's own domain (for example canvas.university.edu or school.instructure.com), so there is no fixed list of hosts. The content script must run on HTTPS pages to detect whether the page is a Canvas site; on any other site it does nothing except show the user's own assignment reminders if that option is on. On Canvas pages it calls that same school's Canvas API (same origin, using the user's existing session) to read courses, assignments, and grades for the dashboard features.
```

**Remote code:** No, I am not using remote code.

**Data usage:** check **Website content** only. Check all three certifications.

**Privacy policy URL:** https://github.com/elijahcantu/coolercanvas/blob/main/PRIVACY.md

## Test instructions tab

Leave credentials blank unless you set up a test account. Additional instructions:

```
Requires a Canvas LMS student account; the extension does nothing on other sites. A free Canvas account can be created at canvas.instructure.com (Free for Teacher). Create a course with a few assignments due this week, then open the Dashboard. Dark mode applies immediately; each course card shows a grade badge and its upcoming assignments, and the right sidebar shows the improved to-do list. Click the toolbar icon to open settings and themes.
```

## Distribution tab

Free, all regions, Public (or Unlisted to test with a link first).
