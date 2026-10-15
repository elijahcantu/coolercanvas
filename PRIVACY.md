# Privacy Policy for Cooler Canvas

Last updated: October 14, 2026

Cooler Canvas is a free, open-source browser extension that customizes the Canvas LMS with dark mode, themes, a GPA calculator, assignment reminders, and other improvements. This policy explains what data the extension uses and where it goes.

## Summary

- The extension does not send any of your data to the developer.
- There are no analytics, no tracking, no ads, and no accounts.
- Your Canvas data is only exchanged between your browser and your school's Canvas site.

## Data the extension reads

When you are on your school's Canvas site, the extension reads the following from that same site, using the session you are already signed in with:

- Your courses, course colors, and dashboard card order
- Your assignments, announcements, and planner items, including due dates and completion status, for the to-do list and reminders
- Your assignment scores and grading groups, only for the courses where you use the GPA calculator or grade features

This data is used only to display the extension's features inside Canvas. It is not sent anywhere else.

## Data the extension stores

The extension stores the following in your browser's extension storage (chrome.storage):

- Your settings, such as dark mode, theme colors, custom card images, custom font, and feature toggles
- Themes you save, and a backup of your settings from before you applied a theme, so you can revert
- Your Canvas site address, if you enter one manually
- Error messages produced by the extension, kept locally to help with troubleshooting. These are never transmitted.

Settings saved with chrome.storage.sync may be synced across your own devices by your browser if browser sync is turned on. This is handled by your browser, not by the developer.

When you mark a to-do item complete or change a course color, the extension saves that change to your own Canvas account through the Canvas API, so it also appears in Canvas.

## Network requests

The extension makes requests to:

- Your school's Canvas site, for the data described above
- Google Fonts (fonts.googleapis.com), to load the fonts used in the extension's settings pages, and to load a custom font on Canvas if you choose one
- Third-party image hosts, only when you apply a theme or enter a custom card image. Built-in themes use images hosted on public websites, and your browser requests those images directly from those sites when the theme is displayed. Those sites may see your IP address, as with any image on the web. You can avoid this by not using image themes.

The extension does not contact any server operated by the developer. The online theme gallery from the original Better Canvas extension has been removed; only built-in and locally saved themes are available.

## Sharing and selling data

The developer does not collect, sell, rent, or share any user data. Because no data is sent to the developer, there is nothing to share.

## Removing your data

Uninstalling the extension removes all data stored in extension storage. Changes saved to your Canvas account, such as completed to-do items and course colors, remain in Canvas and can be changed there.

## Changes

If this policy changes, the updated version will be posted here with a new "Last updated" date.

## Contact

Questions or concerns can be filed as an issue at https://github.com/elijahcantu/coolercanvas/issues.
