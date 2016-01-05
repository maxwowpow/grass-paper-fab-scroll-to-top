grass-paper-fab-scroll-to-top
================

Functions as a FAB with icon arrow.

![alt tag](img/screenshot.png)

Example 1 - use as a normal page element - not bound to a specific container (uses "window") or pinned on the page:

`<grass-paper-fab-scroll-to-top></grass-paper-fab-scroll-to-top>`


Example 2 - use the button to scroll to top a specific div (default is the window):
add attribute `for-element="short-with-long-content"`

`<grass-paper-fab-scroll-to-top for-element="short-with-long-content"></grass-paper-fab-scroll-to-top>`


Example 3 - pin the button at bottom right of the page:
add `pin-bottom-right` attribute with no value

`<grass-paper-fab-scroll-to-top pin-bottom-right></grass-paper-fab-scroll-to-top>`
