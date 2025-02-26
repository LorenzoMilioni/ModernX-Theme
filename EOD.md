# ModernX has declared end of support.

Thank you for all the love and support you all have given the theme. But sadly I do not have the time to maintain it anymore.

## Alternatives

If you want to continue using ModernX-like theme, please try out one of these alternatives:

- Alexis's Modern Theme + Onkofonko's fix (Find it [here.](https://discord.gg/V3UNb4bYB7))

You can also add the following to the CSS file to have RadialStatus:

```CSS
@import url("https://discordstyles.github.io/RadialStatus/dist/RadialStatus.css");
```

and this:

```CSS
/*RadialStatus*/
:root {
  --rs-small-spacing: 2px; /* Gap between avatar and status for members list/dms | MUST end in px */
  --rs-medium-spacing: 3px; /* Gap between avatar and status for User popout | MUST end in px */
  --rs-large-spacing: 4px; /* Gap between avatar and status for User profiles | MUST end in px */

  --rs-small-width: 2px; /* Thickness of status border for members list/dms | MUST end in px */
  --rs-medium-width: 3px; /* Thickness of status border for User popout | MUST end in px */
  --rs-large-width: 4px; /* Thickness of status border for User profile | MUST end in px */

  --rs-avatar-shape: 50%; /* 50% for round - 0% for square */

  --rs-online-color: #43b581; /* Colour for online status */
  --rs-idle-color: #faa61a; /* Colour for idle status */
  --rs-dnd-color: #f04747; /* Colour for dnd status */
  --rs-offline-color: #636b75; /* Colour for offline status */
  --rs-streaming-color: #643da7; /* Colour for streaming status */
  --rs-invisible-color: #747f8d; /* Colour for invisible status - Note: this will only show for your own invisibility */
  --rs-phone-color: var(--rs-online-color); /* Colour of the ring and phone icon when a user is on their phone |  */

  --rs-phone-visible: none; /* Visibility of the phone icon next to a users avatar. | block = visible | none = hidden */
}
```