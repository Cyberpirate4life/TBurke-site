# T. Burke Real Estate

A single-page Monmouth County and New Jersey Shore real estate website. Built with plain HTML, embedded CSS and a small scroll interaction script. No build step or application dependencies.

## Page structure

Hero → Buying / Selling / Towns → About T → Expandable town details → Property search → Direct contact.

Call, text and email are available without JavaScript. Mobile visitors have a fixed contact bar with safe-area spacing. Town details use native HTML disclosures.

## Visual direction and motion

Bold sans-serif typography, oversized T. Burke lettering and a split portrait hero retain the navy, cream and restrained gold palette. An inset ten-photo Monmouth County carousel follows the hero with a cream-colored visual break. It advances every 5 seconds while visible, offers previous/next controls, and accepts horizontal touch swipes. Clicking a photo or the Pause button toggles playback; hover and keyboard focus do not pause it. Automatic advancement is suspended in hidden tabs, outside the viewport and for reduced-motion preferences. Scroll interactions retain the portrait movement, section reveals, compact navigation and reading progress line. The existing portrait and T. Burke logo file are retained; the logo is no longer displayed in About T. Separate brokerage affiliation blocks in About and the footer keep brokerage changes independent of personal branding.

The O'Brien image has not been installed because attachment transfer is blocked on this host; the footer currently uses the supplied brokerage name as text.

### Shoreline photographs

The carousel files are resized locally to 1600 pixels wide; their display viewports crop them. Credits and license links are visible on each slide:

- `spring-lake.jpg`: Nick Harris, Spring Lake beach at sunrise. https://commons.wikimedia.org/wiki/File:Spring_Lake,_New_Jersey_Beach_at_Sunrise.jpg — CC BY 2.5, https://creativecommons.org/licenses/by/2.5/
- `ocean-grove.jpg`: Nathan Siemers, Ocean Grove surf at sunrise. https://commons.wikimedia.org/wiki/File:Foam_-_Flickr_-_nosha.jpg — CC BY-SA 2.0, https://creativecommons.org/licenses/by-sa/2.0/
- `sandy-hook-quiet.jpg`: National Park Service, Sandy Hook beach. https://commons.wikimedia.org/wiki/File:Beach_at_Sandy_Hook.jpeg — U.S. public domain.
- `sea-bright.jpg`: Famartin, beach near Sandy Hook in Sea Bright. https://commons.wikimedia.org/wiki/File:2021-09-08_15_57_17_View_northeast_across_the_beach_from_the_east_side_of_the_pedestrian_overpass_over_New_Jersey_State_Route_36_at_the_entrance_to_Sandy_Hook_in_Sea_Bright,_Monmouth_County,_New_Jersey.jpg - CC BY-SA 4.0, https://creativecommons.org/licenses/by-sa/4.0/
- `belmar.jpg`: Constantino14, Belmar beach aerial. https://commons.wikimedia.org/wiki/File:Belmar7-23-23.jpg - CC BY-SA 4.0, https://creativecommons.org/licenses/by-sa/4.0/
- `asbury-boardwalk.jpg`: Acroterion, Asbury Park boardwalk in the morning. https://commons.wikimedia.org/wiki/File:Asbury_Park_boardwalk_NJ6.jpg - CC BY-SA 4.0, https://creativecommons.org/licenses/by-sa/4.0/
- `long-branch.jpg`: Curlyrnd, Long Branch dunes and beach. https://commons.wikimedia.org/wiki/File:Long_Branch,_NJ_beach,_Oct._2020_(1).jpg - CC BY-SA 4.0, https://creativecommons.org/licenses/by-sa/4.0/
- `manasquan.jpg`: James Loesch, Manasquan Inlet aerial. https://commons.wikimedia.org/wiki/File:Manasquan_Inlet_aerial_photograph_2022.jpg - CC BY 2.0, https://creativecommons.org/licenses/by/2.0/
- `avon.jpg`: Dough4872, Avon-by-the-Sea boardwalk. https://commons.wikimedia.org/wiki/File:Avon-by-the-Sea_boardwalk_looking_north_at_Lincoln_Avenue.jpeg - CC BY-SA 4.0, https://creativecommons.org/licenses/by-sa/4.0/
- `highlands.jpg`: Famartin, Shrewsbury River at the Highlands-Sea Bright bridge. https://commons.wikimedia.org/wiki/File:2024-09-13_15_12_13_View_northeast_from_New_Jersey_State_Route_36_(Highlands-Sea_Bright_Bridge)_over_the_Shrewsbury_River_on_the_border_of_Sea_Bright_and_Highlands_in_Monmouth_County,_New_Jersey.jpg - CC BY-SA 4.0, https://creativecommons.org/licenses/by-sa/4.0/

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
