# T. Burke Real Estate

A single-page Monmouth County and New Jersey Shore real estate website. Built with plain HTML, embedded CSS and a small scroll interaction script. No build step or application dependencies.

## Page structure

Hero → Buying / Selling / Towns → About T → Expandable town details → Property search → Direct contact.

Call, text and email are available without JavaScript. Mobile visitors have a fixed contact bar with safe-area spacing. Town details use native HTML disclosures.

## Visual direction and motion

Bold sans-serif typography, oversized T. Burke lettering and a split portrait hero retain the navy, cream and restrained gold palette. Scroll interactions include a moving Shore banner, subtle portrait movement, section reveals, a compact navigation bar and a reading progress line. The existing portrait and logo are retained.

Animation respects reduced-motion preferences. Content stays visible without JavaScript; native links and town disclosures work independently of the animation.

## RealScout setup

1. In T. Burke’s RealScout account, open Marketing → Widgets and choose Simple Search.
2. Customize the available color settings to match the navy and cream palette.
3. Copy the account-specific script into `index.html` inside `<head>` once.
4. Replace the temporary help content inside `#realscout-widget` with the corresponding widget markup. Keep the surrounding section and text contact link.
5. Add the verified account search URL as a direct fallback link. Do not invent a URL or reuse another agent’s embed code.
6. Check search results, account attribution and any sign-up flow on desktop and mobile. Confirm the widget’s required listing attribution remains visible.

Official instructions: https://support.realscout.com/en/articles/11954493-using-the-customizable-widgets

The current page offers contact assistance while the actual account embed is unavailable; it does not present a simulated search or listings feed.

## Before publishing

- Confirm phone and email destinations with T. Burke.
- Supply verified brokerage identity and applicable advertising disclosures for the footer. None have been invented.
- Activate and test the RealScout integration once the account code and search URL are supplied.

## Local information sources

Town details use conservative descriptions and practical comparison prompts, with visible links for visitors:

- Atlantic Highlands municipal harbor: https://www.ahnj.com/ahnj/Harbor/Amenities
- Highlands borough: https://highlandsnj.gov/
- Red Bank RiverCenter: https://www.redbank.org/red-bank/
- Sea Bright municipal beach: https://www.seabrightnj.org/sbnj/Departments/Beach/History/History/
- Rumson borough: https://www.rumsonnj.gov/

## Verification

Open `index.html` in a browser, or serve this directory with a local static server. Check narrow and wide screens, keyboard navigation, all five town disclosures, section links, direct contact destinations and reduced-motion behavior. No tracking code, third-party widgets or new dependencies are included in this revision.

Source checks passed for HTML nesting, unique IDs, internal section links, image paths and JavaScript syntax. Live desktop browser verification passed: both images load, all five town disclosures open, and the page has no horizontal overflow at 1363px. Direct contact destinations were checked without initiating calls or sending messages. Desktop navigation contrast was corrected after visual review. Rendered mobile verification remains outstanding.
