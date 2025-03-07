# Changelog

## WIP

### Added

- Add tile hover hooks

### Fixed

- Fix toggle behavior in Toggle component

## 3.7.2 (August 6, 2021)

### Fixed

- Fix text alignment if tabs are left or right aligned in Tab component

## 3.7.1 (July 15, 2021)

### Fixed

- Fix animation classes only partially being removed in Scrollspy component
- Fix scrollIntoView did not return Promise if element is hidden 

## 3.7.0 (June 29, 2021)

### Added

- Add text decoration modifier to Text component
- Add width variable to range thumb in to Form Range component
- Add Bag icon

### Change

- Change default search width and horizontal padding in Search component
- Change badge width and font size in Badge component
- Change button link color and text decoration in Button component
- Change card badge height in Card component
- Remove margin from the navbar item last-child in Navbar component
- Add white space gap for navbar item in Navbar component
- Allow text after icon in Iconnav component

### Removed

- Remove badge hover color variable in Badge component

### Fixed

- Fix input type list showing picker indicator in Chrome
- Fix focus background in Form and Search component
- Fix form size modifier for textarea in Form component
- Fix icon alignment in Nav, Subnav and Tab components
- Fix default dropdown selector in Navbar component
- Fix show behavior in Drop component for multiple toggles
- Fix ScrollspyNav component triggering 'active' event on every scroll
- Fix prevent updates on disconnected components

## 3.6.22 (May 18, 2021)

### Added

- Add animation set to `false` in Filter component

### Changed

- Animation classes toggled by Scrollspy component are removed after animation finishes

### Fixed

- Fix box-shadow bottom being clipped in Safari if container is animated

## 3.6.21 (May 4, 2021)

### Added

- Add divider modifier to Nav component

### Fixed

- Fix passing an array of classes to class utility functions
- Fix boundary option in Drop component

## 3.6.20 (April 22, 2021)

### Change

- Toggle component in hover mode toggles on focus and blur

### Fixed

- Fix inverse colors for link toggle in Base component

## 3.6.19 (April 7, 2021)

### Change

- Update card badge style

### Fixed

- Fix animation set to `false` in Sortable component
- Fix Tooltip on elements with class 'uk-active' applied
- Fix Slider parallax states

## 3.6.18 (March 12, 2021)

### Added

- Add Discord, Twitch and TikTok icons

### Removed

- Remove Google Plus icon

### Fixed

- Fix filter initial state

## 3.6.17 (February 25, 2021)

### Added

- Add background-size modifier for width and height to Background component 

### Fixed

- Fix dragging time control starts dragging slide in Safari

## 3.6.16 (February 5, 2021)

### Change

- Make multiple select resizable

### Fixed

- Fix dragging slide correctly prevents click event

## 3.6.15 (January 29, 2021)

### Added

- beforeSend in 'ajax' function may return Promise
- Add 'container' option to Notification component

### Fixed

- Fix showing/hidding Modal/Offcanvas programmatically

## 3.6.14 (January 26, 2021)

### Fixed

- Fix 'scrolledOver' function uses closest scrollable parent
- Fix Lightbox closes on drag if slide background is dragged
- Fix Drop component applies stack class wrongly

## 3.6.13 (January 20, 2021)

### Fixed

- Fix slidenav icons

## 3.6.12 (January 20, 2021)

### Fixed

- Fix IE11 compatibility
- Fix changing ratio does not correctly apply width and height in SVG component
- Fix issues from hiding an already hidden Modal 

## 3.6.11 (January 14, 2021)

### Fixed

- Fix regression in SVG component

## 3.6.10 (January 11, 2021)

### Changed

- Refactor Sortable behavior

### Fixed

- Fix regression in sticky component
- Fix calculating max scroll height
- Fix regression with calling watchers

## 3.6.9 (January 7, 2021)

### Fixed

- Fix component update handling
- Fix Tooltip position
- Fix Tooltip component applied to button elements in iOS
- Fix regression in Switcher component

## 3.6.8 (January 5, 2021)

### Fixed

- Fix regression in class util

## 3.6.7 (January 4, 2021)

### Fixed

- Fix regression in class util

## 3.6.6 (January 4, 2021)

### Added

- Add filter animation delayed-fade

### Changed

- Filter animation fade does not stagger

### Fixed

- Fix filter animations
- Fix slider drag behavior on iOS
- Fix Scroll component now supports hash starting with any character

## 3.6.5 (December 21, 2020)

### Fixed

- Fix missing imports

## 3.6.4 (December 21, 2020)

### Changed

- Improve context selectors to use a dom path selector

### Fixed

- Fix IE11 compatibility
- Fix Accordion component toggles
- Fix regression in Toggle component

## 3.6.3 (December 18, 2020)

### Fixed

- Fix filter tests

## 3.6.2 (December 18, 2020)

### Changed

- IMPORTANT: Change options 'animationMode' to 'animation', 'animation' to 'duration'
- IMPORTANT: Rename 'shift' animation to 'slide'

## 3.6.1 (December 17, 2020)

### Fixed

- Fix regression in Toggle component

## 3.6.0 (December 17, 2020)

### Added

- Add fade animation to Filter component
- Add 'priority' param to 'css' function

### Fixed

- Fix 'aria-expanded' value on toggles
- Fix responsiveness in Switcher component

## 3.5.17 (December 16, 2020)

### Added

- Offcanvas component hides if invisible

### Changed

- Image component will load images eagerly in IE11
- Improved Tooltip accessibility
- Set 'aria-expanded' on toggles

### Fixed

- Fix regression in Slider component
- Fix do not set 'aria-hidden' if element has already been removed from the accessibility tree
- Fix Switcher component does not ignore disabled toggles
- Fix Toggle component in queued mode

## 3.5.16 (December 11, 2020)

### Fixed

- Fix Sortable lets sort items between lists if no 'group' is set
- Fix 'scrollParents' checks for `position: fixed`

## 3.5.15 (December 10, 2020)

### Fixed

- Fix regression in Scrollspy Nav

## 3.5.14 (December 9, 2020)

### Fixed

- Fix Scrollspy Nav using wrong viewport as reference
- Fix Slider component skipping animation if slide item wider than its list

## 3.5.13 (December 8, 2020)

### Changed

- Sorting starts after traversing half the items height/width in Sortable component

## 3.5.12 (December 7, 2020)

### Fixed

- Fix 'isInView' function

## 3.5.11 (December 7, 2020)

### Fixed

- Fix 'positionAt' function did not flip within its targets scroll container
- Fix drag gets 'overflow: hidden' in Sortable component

## 3.5.10 (November 27, 2020)

### Added

- Add container offset to prevent box-shadow clipping to Slider component

### Changed

- Add '50vw' default horizontal root margin to Image component

### Fixed

- Remove space between inline block elements in Breadcrumb component

## 3.5.9 (October 20, 2020)

### Changed

- Improve breadcrumbs wrapping into the next line
- Sortable drag is no longer clamped to viewport

### Fixed

- Prevent content overflow in Breadcrumb component
- Fix prefix script
- Fix 'scrollIntoView' does not align to top

## 3.5.8 (September 25, 2020)

### Added

- Add lightbox button active hook

### Changed

- IMPORTANT: Set `@pagination-margin-horizontal` to `0` and use new `@pagination-item-padding-vertical` and `@pagination-item-padding-horizontal`

### Fixed

- Fix lightbox button focus state
- Fix Slider component transition bug in iOS 14.0

## 3.5.7 (August 27, 2020)

### Fixed

- Fix Switcher component no longer toggles an already active item
- Fix 'positionAt' function not detecting flip state correctly
- Fix 'z-index' for stacked Modals

## 3.5.6 (August 13, 2020)

### Changed

- Sticky component uses window.Date instead of window.performance
- Sticky component with sticky-on-up no longer hides when Dropdown shows

### Fixed

- Fix slidenav color in Lightbox component
- Fix inverse colors for link toggle in Link component
- Sticky component remains inactive if hidden
- Revert dropbar mode `push` is only applied if Navbar is positioned static
- Fix animations not resolving if user canceled

## 3.5.5 (July 14, 2020)

### Added

- Add list marker utility support for WebKit
- Add `uk-text-default` to Text component 
- Add multiple targets to Filter component

### Fixed

- Updates no longer throw error after too many recursions, but delay into next frame
- Fix empty slider throws exception
- Fix pointer events ignored on SVGs in Sortable component
- Fix Grid component divider rendering
- Fix `<select>` closes Drop component in hover mode in Firefox 

## 3.5.4 (June 12, 2020)

### Added

- Image component triggers 'error' event on failing to load image

### Fixed

- Fix prop observer for dataSrc option in Image component
- Fix ajax function supports responseType 'json' in IE 11 
- Fix Accordion component with `multiple: true` and `collapsible: false`

## 3.5.3 (May 29, 2020)

### Fixed

- Fix regression in Grid component with parallax option

## 3.5.2 (May 29, 2020)

### Fixed

- Fix uglifyjs removes self-assignments

## 3.5.1 (May 29, 2020)

### Fixed

- Fix regression in Animation API
- Fix regression Drop component
- Fix regression in Sass source

## 3.5.0 (May 28, 2020)

### Added

- Add type, color and size modifiers to List component

### Changed

- IMPORTANT: Renamed Less variable parts `xxlarge` to `2xlarge`
- Replace clearfix by creating a block formatting context with display flow-root

### Deprecated

- Width XXLarge: Use `uk-width-2xlarge` instead of `uk-width-xxlarge`

### Fixed

- Fix positioning issue with Drop components in Firefox
- Fix Dropbar causing endless loop in Firefox

## 3.4.6 (May 11, 2020)

### Fixed

- Fix regression in Switcher component

## 3.4.5 (May 11, 2020)

### Added

- Add inBrowser check to enable server-side rendering 

### Fixed

- Fix Switcher responsiveness
- Fix `isInView()` no longer returns true for adjacent rectangles
- Fix compatibility with browsers that support `Object.prototype.watch()`

## 3.4.4 (May 7, 2020)

### Fixed

- Fix Scrollspy component stuck in wrong state
- Fix regression in Grid component with masonry

## 3.4.3 (May 5, 2020)

### Changed

- Improve attribute state observer performance

### Fixed

- Fix Search Icon with large modifier
- Fix Grid divider in RTL mode
- Fix Slider component responsiveness

## 3.4.2 (April 20, 2020)

### Added

- Hide Drop components on `Esc` keypress

### Fixed

- Fix `quote-right` icon empty in RTL mode
- Revert: Fix Sticky component correctly updates on `update`

## 3.4.1 (April 16, 2020)

### Fixed

- Fix `bottom` if offset is `0` in Sticky component
- Fix dropbar mode `push` is only applied if Navbar is positioned static
- Fix Sticky component correctly updates on `update`
- Fix Sticky component handles `vh` values for `top`and `bottom` options
- Fix Sticky component sets its width with fraction
- Fix Sticky component with `show-on-up` and `bottom` option updates correctly
- Fix Tooltip component no longer disappears on SVG shape elements
- Fix regression with Modal/Offcanvas component not opening in IE 11

## 3.4.0 (April 9, 2020)

### Added

- Add `attrs` option to Lightbox items
- Add additional url parameters to YouTube/Vimeo embed URLs in Lightbox component

### Changed

- Change default dimensions to 1920x1080 for YouTube in Lightbox component 

### Fixed

- Fix subnav not wrapping into the next line correctly when using `uk-margin` attribute
- Fix selected `uk-text-background` text being visible in Firefox
- Fix Scrollspy Nav component activating previous item in Firefox
- Fix toggling Offcanvas component
- Fix Sortable component unable to sort table rows
- Fix autoplay for YouTube and Vimeo videos in Lightbox component
- Fix dragging slides in Lightbox component in Chrome mobile

## 3.3.7 (March 19, 2020)

### Fixed

- Fix Height Match component not matching empty elements
- Fix Scrollspy Nav component activating wrong elements
- Fix Modal/Drop close on bgClick behaviour 
- Fix `z-index` on Modal stacked dialogs

## 3.3.6 (March 12, 2020)

### Added

- Add `offset` option to Accordion component

### Changed

- Removed `duration` option from Scroll component

### Fixed

- Fix regression in Accordion component

## 3.3.5 (March 12, 2020)

### Fixed

- Fix regression in Sortable component

## 3.3.4 (March 12, 2020)

### Changed

- `getEventPos` returns client coordinates only

### Fixed

- Fix Drop component does not close on pointerleave in Firefox
- Fix Switcher component sets active state on ignored item
- Fix Accordion component triggers events on elements only
- Fix Accordion component no longer wraps its content without transition
- Fix missing `$emit` function
- Fix Sortable component performance
- Fix prevent showing/hiding of Tooltip component

## 3.3.3 (February 25, 2020)

### Changed

- Improve Tooltip component performance
- Notifications remove their container if it's empty
- The promise object returned by Modal Dialogs holds a reference to the Modal component itself.

### Fixed

- Fix style for breadcrumbs without last active item
- Fix infinite loop in Slider component
- Fix IE 11 compatibility
- Fix Spinner component in RTL mode
- Fix animating `stroke` in Parallax component when element is hidden

## 3.3.2 (February 17, 2020)

### Fixed

- Fix accessing computed properties after component has been disconnected
- Fix Modal dialogs not being removed from DOM after close
- Fix Lightbox opening only once
- Fix updates having wrong type

## 3.3.1 (February 4, 2020)

### Changed

- Improve update performance

### Fixed

- Fix countdown separator line-height
- Fix Cover component covers positioned parent element

## 3.3.0 (January 23, 2020)

### Added

- Add container xlarge modifier

### Changed

- IMPORTANT: Change `uk-container-large` width. Use `uk-container-xlarge`

### Fixed

- Fix `position` takes offsetParent's border width into account

## 3.2.7 (January 13, 2020)

### Fixed

- Fix Drop component has wrong state after disconnect
- Fix `repeat` option in Scrollspy component in Firefox

## 3.2.6 (December 17, 2019)

### Fixed

- Fix regression with custom icons build task

## 3.2.5 (December 17, 2019)

### Added

- Prevent content overflow if `max-width: 100%` is used inside Position component
- Add `parent` util function
- Add `children` util function
- Add `isElement` util function

### Fixed

- Accordion component triggers scroll on page load
- Fix regression in Scroll component in Edge and IE

## 3.2.4 (December 3, 2019)

### Added

- Parallax, Scroll, Scrollspy Nav components work inside of scrollable container
- Expose `scrollIntoView` utility function

### Fixed

- Fix scrolling containers while dragging in Sortable component
- Fix show/hide behaviour in Drop component 
- Fix Accordion component will scroll title into view if needed
- Fix component initialization without element

## 3.2.3 (November 6, 2019)

### Fixed

- Fix initializing components with jQuery elements

## 3.2.2 (October 23, 2019)

### Added

- Prevent endless update loops

### Changed

- Improve event.preventDefault behaviour in Toggle component
- Improve initial boot

### Fixed

- Fix event delegation with `self` filter

## 3.2.1 (October 1, 2019)

### Added

- Add support for `input type="submit"` to Button component
- Add `selSlides` option to Slider/Slideshow component

### Fixed

- Fix Slider throws error if initialized with no slides
- Fix Slider/Slideshow crash in IE
- Fix Slider/Slideshow drag no longer starts on input elements
- Fix Slider/Slideshow Parallax shows wrong initial state
- Fix `isPlainObject` to work across iframes
- Fix Scrollspy causes endless update loop

## 3.2.0 (September 5, 2019)

### Added

- Add column and row gutter to Grid component

### Removed

- Remove `@text-bold-font-weight` variable

### Fixed

- Fix countdown line-height on small devices

## 3.1.9 (September 2, 2019)

### Added

- Add `last` utility function

### Fixed

- Fix Slideshow invisible after switching tabs in Switcher
- Fix lazy loading images in Img component in UC Browser
- Fix opening Offcanvas/Modal through buttons

## 3.1.8 (August 29, 2019)

### Added

- Add font weight and style modifier
- Add `self` option to `on` function

### Changed

- Improve `padding-bottom` calculation for Grid with `parallax: true`
- Make `selMinHeight` in the Flex Bug mixin a prop

### Fixed

- Fix Modal close on bgClick behaviour
- Fix spreading event args on delegated event listeners
- Fix clicking an empty link within itself no longer closes the Drop
- Fix IE 11 compatibility
- Fix empty tooltips will no longer show

## 3.1.7 (July 31, 2019)

### Changed

- By default, the Offcanvas `container` option is `false` now
- The `focusable` attribute on SVG/Icon component makes SVG focusable in IE

### Fixed

- Fix Slideshow/Slider triggering show events to often initially
- Fix swipe gestures in Switcher component (Android)
- Ensure at most one Height Viewport component set to `expand` is active
- Height Viewport component no longer calculates its height if invisible
- Fix using Sortable in scrolling container 
- Fix lazy loading images if parent element is fully clipped
- Fix clicking Slideshow with `draggable: false` no longer pauses autoplay
- Fix toggling modal while transition is in progress
- Fix Height Viewport component growing indefinitely if positioned above document
- Fix Height Viewport component uses height with fractions
- Fix Margin component for rows 1 pixel in height

## 3.1.6 (June 19, 2019)

### Added

- Add style for input with datalist

### Fixed

- Fix image shrinking in centered and absolutely positioned navbars
- Fix Custom Form not resetting on form `reset` event
- Fix leader inverse hook
- Fix divider vertical inverse hook

## 3.1.5 (May 17, 2019)

### Added

- Add link toggle to Link component
- Add breakpoint classes for margin auto and remove
- Add Etsy icon

### Fixed

- Fix Dropbar closing unexpectedly
- Fix Sortable `click` event prevention in Firefox
- Fix JS error in Offcanvas component on touch devices
- Icon components no longer have a primary option
- Icon/Svg components no longer reset initially

## 3.1.4 (April 24, 2019)

### Fixed

- Fix selector engine
- Fix CSS selector in Lightbox component
- Fix Drop not closing when Toggle component is clicked
 
## 3.1.3 (April 23, 2019)

### Fixed

- Fix Scrollspy Nav component
- Fix closing Lightbox causes text selection in Firefox

## 3.1.2 (April 18, 2019)

### Changed

- IMPORTANT: Change `@deprecated` variable to `false`

### Fixed

- Fix filter controls active state in Filter component

## 3.1.1 (April 18, 2019)

### Fixed

- Fix Sass distribution
- Fix Lightbox opens with wrong index

## 3.1.0 (April 17, 2019)

### Added

- Add deprecated flag to Less variables
- Add size modifiers to Heading component
- Add SVG stroke animation to Animation component
- Add option to animate SVG strokes to SVG component
- Add option to animate SVG strokes to Parallax component
- Add support for more units to Parallax component
- Add lazy loading support if Image component is used with SVG component
- Add text secondary to Text component
- Add `dataSrc` as primary option to Image component
- Add `webp` as image type to Lightbox Panel component

### Changed

- Refactor divider, bullet and line modifiers in Heading component
- Improve dimension handling in SVG component
- Improve performance of Image, Leader and Toggle component
- Autoplay is halted while Slideshow/Slider are active
- Lightbox filters duplicate items by `source`
- Rename `getPos` to `getEventPos`
- Move code with side effects to `core.js`

### Deprecated

- Primary Heading: Use `uk-heading-medium` instead of `uk-heading-primary`
- Hero Heading: Use `uk-heading-xlarge` instead of `uk-heading-hero`

### Removed

- `cls` option no longer accepts a list of classNames in Scrollspy component

### Fixed

- Fix rendering issue for scale in Transition component
- Fix Filter component's initial active state
- Fix translating `x` and `y` properties simultaneously in Parallax component
- Fix drag closes Lightbox
- Fix Tooltip component (touch device)
- Fix `hover` mode for Toggle component (touch device)
- Fix Slideshow not setting `min-height` if ratio is set to `false`
- Default prevent `click` event in Slider/Slideshow component after drag
- Fix images being selected while dragging in Slider/Slideshow component

## 3.0.3 (January 29, 2019)

### Added

- Computeds can be watched now
- Parallax supports `<SVG>` and its child elements now

### Changed

- Image Component uses IntersectionObserver now

## Removed

- Remove `isReady` function
- Form Custom component no longer sets `uk-hover` and `uk-focus` classes

### Fixed

- Fix touch event detection
- Fix background images are shown too large on retina displays in Img component
- Fix correctly calculate offsetLeft in Img component
- Fix autofocus elements not blurring within Toggable on hide

## 3.0.2 (January 15, 2019)

### Fixed

- Fix offcanvas overlay transition
- Fix active state in Switcher component
- Fix background images on displays with higher devicePixelRatio in Img component

## 3.0.1 (January 14, 2019)

### Fixed

- Fix Sass distribution

## 3.0.0 (January 14, 2019)

### Added

- Add active states for sub nav items in Nav, Navbar and Dropdown component
- Add emoji default fonts to the system font stack

### Changed

- Improve offcanvas reveal and push animations
- Improve animation, transition and visibility toggles for touch devices
- Improve update performance
- `css` function: Setting a CSS property to `NaN` no longer removes the property
- Slide/Slideshow navs and Drops no longer blur after hiding
- Changed the default `toggle` option for Switcher component to `> * > :first-child`
- SVG component no longer moves `id` from element to svg

### Removed

- Remove `uk-hover` class
- Remove artificial `click` event on mobile devices

### Fixed

- Fix visible toggle and its child elements not being focusable through keyboard navigation
- Fix Img component correctly escapes urls on background images

## 3.0.0 rc 26 (January 3, 2019)

### Added

- Add expand classes to Container component

### Changed

- @notification-message-margin-bottom to top in Notification component
- Improve swipe gesture detection
- `isInView` checks relative to viewport only

### Fixed

- Fix `flex bug` mixin (IE 11)
- Fix properly resolving css custom properties in scss
- Fix order of variable assignments in scss
- Fix background images are shown too large on retina displays in Img component
- Fix lazy loading images in Img component in Safari
- Limit positioned element to container width and margin in Position component

## 3.0.0 rc 25 (November 30, 2018)

### Fixed

- Fix `hasClass` in IE11 again
- Fix workaround to mitigate the duplicating icons issue

## 3.0.0 rc 24 (November 23, 2018)

### Changed

- Drop positioning uses window as secondary boundary

### Fixed

- Fix modal not opening on first click in Angular apps
- Fix filter controls active state in Filter component
- Fix Masonry Grid in RTL mode
- Make sure autoplay does not resume after user interaction in slider-autoplay mixin
- Fix `hasClass` in IE11

## 3.0.0 rc 23 (November 16, 2018)

### Changed

- Destroy Lightbox Panel upon closing

### Fixed

- Fix sticky not recalculating after update
- Fix clicking on items not triggering `click` event in Sortable component
- Fix Offcanvas changing viewport upon opening

## 3.0.0 rc 22 (November 9, 2018)

### Fixed

- Fix regressions in Modal component

## 3.0.0 rc 21 (November 7, 2018)

### Added

- Add threshold before Sticky with `Show On Up` changes state
- Add `draggable` option to Slider and Slideshow component

### Fixed

- Fix toggling Offcanvas component while transition in progress
- Fix Offcanvas height on mobile devices

## 3.0.0 rc 20 (October 24, 2018)

### Added

- Add print, reddit, microphone, file-text, file-pdf, chevron-double left and right icons
- Add text emphasis to Text component
- Add `src` as primary option to SVG component

### Changed

- Offcanvas no longer requires a wrapping content div
- Change video-camera icon style to outline

### Fixed

- Fix sorting in Sortable component on touch devices with page scrolled down
- Fix height of Masonry Grid
- Fix Sticky hiding with Offcanvas in overlay mode
- Fix Parallax in combination with Offcanvas in overlay mode

## 3.0.0 rc 19 (October 11, 2018)

### Fixed

- Fix regression in Icon component

## 3.0.0 rc 18 (October 11, 2018)

### Added

- Add divider vertical modifier to Divider component

### Fixed

- Fix preserve color not working if class is set on svg element in Icon component
- Fix inverse hover color for accordion title
- Fix close color being overwritten from toolbar in Lightbox component
- Fix Modal not hiding upon being destroyed
- Fix using node as offset in position mixin
- Fix using Height Match component on elements with different offsetParents
- Fix rounding error in Height Match component
- Fix `scope` command for already scoped css, comments are removed from generated css files
- Fix Sticky placeholder height on resize
- Fix starting/stopping of autoplay in Lightbox
- Fix initially wrong position of background image in Parallax component
- Fix calling `isActive` on `undefined` in Navbar component

## 3.0.0 rc 17 (September 27, 2018)

### Added

- Dom functions support selectors

### Changed

- Viewport Height component no longer sets a `height` except for IE
- Viewport Height component no longer forces `box-sizing: border-box`
- Improve Tooltip performance
- Improve Parallax performance
- Improve Sticky performance

### Removed

- Remove `::-moz-selection` which is not needed anymore
- Remove component `init` hook
- Remove component `ready` hook

### Fixed

- Fix `UIkit.mixin()`
- Fix issue with list bullet in combination with multi-column layouts
- Allow for special characters in URI hash in Scroll Component
- Height Match also sets a `height` in IE
- Slideshow sets `min-height` instead of `height`


## 3.0.0 rc 16 (September 12, 2018)

### Fixed

- Fix regression in Overflow Auto component

## 3.0.0 rc 15 (September 11, 2018)

### Changed

- Rename `selModal` to `selContainer` and `selPanel` to `selContent` in Overflow Auto component

### Fixed

- Fix `isInView` function for elements with zero width and height

## 3.0.0 rc 14 (September 4, 2018)

### Fixed

- Fix regression in `removeClasses` function

## 3.0.0 rc 13 (September 4, 2018)

### Added

- Add border pill to Utility component

### Changed

- Use `min-height` instead of `height` for navbar nav items

### Removed

- Remove `filterAttr` function

### Fixed

- Fix SVGs not preserving their aspect ratio in IE11
- Fix lazy loading images in Edge

## 3.0.0 rc 12 (August 27, 2018)

### Added

- Add responsiveness to SVGs in Base component
- Make remaining components reactive
- Boolean attributes coerce to `true` if the prop is defined as Boolean

### Changed

- Allow icons to shrink in Iconnav
- Add more margin between accordion title and icon
- `UIkit.mixin` can now be used to extend existing components

### Removed

- Remove fix for uppercase SVGs attributes in Edge on Windows 10 older than build 16251

### Fixed

- Fix form placeholder color in Edge
- Fix accordion icon position if title is wrapping into the next line
- Fix Slider incorrectly showing navigation
- Fix element queuing in Scrollspy component
- Fix parallax translating to subpixels
- Fix issue with scrolling on mobile devices in Sortable component

## 3.0.0 rc 11 (August 8, 2018)

### Changed

- Pass error object to callback function instead of message only in Upload component

### Removed

- Remove deprecated prevention of the 300ms delay for touch devices

### Fixed

- Fix bug in `pointInRect` function

## 3.0.0 rc 10 (July 25, 2018)

### Added

- Add container xsmall modifier

### Changed

- Improve Height Viewport component performance

### Fixed

- Fix performance regression in Grid component
- Fix Height Viewport jumping in size on mobile devices if BottomOffset was set
- Fix offsetParent detection

## 3.0.0 rc 9 (July 13, 2018)

### Changed

- Allow thumbnav items to shrink if `flex-wrap: nowrap` is set

### Fixed

- Fix Filter component height during transition
- Fix Filter/Sortable component in IE 11
- Fix Overflow Auto component triggering `resize` event indefinitely
- Fix Slider/Slideshow capture slide during transition in Safari 11
- Fix Slider/Slideshow drag behavior in iOS 11.3+ (https://bugs.webkit.org/show_bug.cgi?id=184250)
- Fix `toEventTargets` in IE 11

## 3.0.0 rc 8 (July 5, 2018)

### Fixed

- Fix regression in dev dependencies

## 3.0.0 rc 7 (July 5, 2018)

### Added

- Allow `data-` prefixed attributes as component options

### Changed

- Improve Image component performance
- Improve Cover component performance
- Improve resize reactivity on Image/Video load

### Fixed

- Fix Dropbar in Navbar in IE 11
- Fix single components did not get exported from their modules
- Fix Lightbox reactivity

## 3.0.0 rc 6 (June 15, 2018)

### Added

- Add development builds to npm registry (`npm i uikit@dev` / `yarn add uikit@dev`)

### Fixed

- Fix single components to auto-install only when UIkit is attached to window object
- Fix component naming (camelCase) in single component auto-install wrapper
- Fix active row style for striped table
- Fix height of Masonry Grid
- Fix attribute change listener
- Cover component updates on image load
- Fix Lightbox options handling

## 3.0.0 rc 5 (June 4, 2018)

### Fixed

- Fix missing standalone component installment
- Fix passing Lightbox options to Lightbox Panel
- Fix not appearing fixed background images for Chrome 67
- Fix having a Slider within a Slideshow element
- Fix filter animation in Edge
- Fix accessing sessionStorage if that's prevented
- Fix lazy loading images if no width and height are provided

## 3.0.0 rc 4 (May 30, 2018)

### Changed

- Delay loading images by one frame in Image Component

### Fixed

- Fix clipping of dropdowns in Dropbar

## 3.0.0 rc 3 (May 28, 2018)

### Changed

- Improve Lightbox type detection
- UIkit.icon.add supports resetting component icons now

### Fixed

- Fix lazy loading of images with same source
- Fix lazy loading of background images on elements with no height and width attributes
- Fix late component registration
- Fix resizing behavior of Sticky component
- Fix media mode in Toggle default preventing click events on touch devices

## 3.0.0 rc 2 (May 16, 2018)

### Fixed

- Fix regression in Scrollspy in IE 11
- Fix Sass distribution
- Fix large close icon

## 3.0.0 rc 1 (May 15, 2018)

### Added

- Add Img component to lazy load images
- Add Filter component to filter and sort any kind of layout
- Add `masonry` option to Grid component
- Add inverse style for form icon
- Add smaller font-sizes on mobile for h1, h2, primary and hero heading and article title

### Changed

- Break long words into the next line for comment body
- Move grid `parallax` option to Grid component and remove Grid Parallax component
- Move Height, Leader, SVG and Video from Utility component into their own components
- Allow left and right icons at the same time in form and search component
- Rename `target` to `target-offset` in Sticky component
- Remove hyphenating for text break

### Fixed

- Fix option color in select dropdowns for Inverse component
- Fix dropcap font size in Edge
- Fix dropcap line height in Firefox
- Fix Scrollspy being stuck in endless update loop
- Fix Slideshow combined with Height Viewport component
- Fix Height Match component's `row` matching
- Fix height calculation in Height Match component
- Fix regression with Video component not auto play/pause

## 3.0.0 beta 42 (April 5, 2018)

### Fixed

- Fix regression in Offcanvas

## 3.0.0 beta 41 (April 4, 2018)

### Added

- Add table large modifier
- Add `Autoplay` as primary option for Video component
- Add core and component dist files to NPM package

### Changed

- Make `uk-form-icon` padding work with size modifier
- Make heading line position top a variable
- Allow dropdowns in Iconnav component
- Allow any property in `svg-fill` mixin
- Move progress normalization to progress component
- Video component sets `preload="false"` if `autoplay` is set to `inview`
- Global `update` method now updates element itself as well as its parents and children

### Removed

- Remove the instance method `$update`

### Fixed

- Fix browser compatibility in Navbar component
- Fix preventClick function on touch devices
- Fix LightboxPanel props
- Fix Player ids in Vimeo videos
- Dropbar opens on bottom positioned drops only
- Fix setting height of drag in Sortable component
- `isInView` checks for element visibility now
- Fix check for backgroundSize: cover resetting backgroundSize in Parallax
- Fix "Uncaught (in promise) DOMException" in Player
- Fix Slideshow `fade` effect
- Fix `type` option in Upload component
- Fix misplaced Drop on fast toggling
- Fix Modal close on bgClick behaviour
- Fix Sets calculation in Slider on iOS

## 3.0.0 beta 40 (February 8, 2018)

### Changed

- Improve Form Custom reactivity
- Improve Scrollspy component reactivity

### Fixed

- Fix using Scrollspy component with default values
- Fix Scrollspy if UIkit is loaded async
- Fix YouTube short urls in Lightbox component
- Fix empty select in Form Custom component
- Fix Slider reactivity

## 3.0.0 beta 39 (January 31, 2018)

### Added

- Add link heading to Link component
- Add Slider Parallax component
- Add support for privacy enhanced mode in YouTube urls

### Changed

- _Active_ classes are applied to all fully visible slides in Slider component
- Allow all Lightbox Panel options to be set through Lightbox component

### Fixed

- Fix Slider Nav initially has no state
- Fix Esc closing on Confirm and Prompt dialogs
- Fix using Grids in Slider component in Safari
- Fix edge scrolling in Sortable component in IE 11
- Fix touch scrolling in Slideshow/Slider in Edge
- Fix tap event on touch devices
- Fix initial Drop positioning

## 3.0.0 beta 38 (January 18, 2018)

### Added

- Add support to center elements outside of a container to Position component

### Changed

- Add `uk-slider-container` class to clip the Slider component
- Remove auto-clipping from Slider items. Use `uk-cover-container` instead

### Fixed

- Fix Tooltip in Accordion loosing title
- Fix Inverse mode (Light and Dark) in tests
- Fix component getter

## 3.0.0 beta 37 (January 16, 2018)

### Added

- Add `beforeConnect` and `beforeDisconnect` component hooks

### Fixed

- Fix origin modifier for programmatically triggered animations
- Dialogs correctly cleanup after closing
- Fix missing container option on Tooltip component
- Fix positioning of Dropdowns in Dropbar
- Fix browser freezing on Slider resize
- Fix Custom Form initial value
- Fix Tooltip removing title attribute

## 3.0.0 beta 36 (January 11, 2018)

### Added

- Add Slider component
- Add RTL support to Slideshow component
- Add reactive navigation to Slideshow component
- Hide slideshow navigation if slideshow contains single slide only
- Add support to play/pause Video component as it enters/leaves the viewport
- Add file size restriction `maxSize` to Upload component
- Add option to pass `data-alt=""` to images in Lightbox component
- Component DOM attributes like `uk-grid` are being observed for changes
- Improve `UIkit.container` setter (allows for assigning selector strings)
- Make some util methods more error resilient
- Add config options to build scripts, type `./build/build.js -h` for options
- Add UIkit version banner to generated CSS files
- Add option to skip minification during Less compiling (`./build/less.js -d`)
- Add parametrization for prefix and scope scripts. Use `scope/prefix -h` (e.g. `npm run prefix -- -h`) to list the available options.

### Changed

- IMPORTANT: Use `a` element instead of headings for the accordion title
- Calling a component constructor with data on an already initialized component will reset the component
- Dropbar no longer repositions Dropdowns in DOM upon opening

### Deprecated

- Deprecate `uk-gif`

### Removed

- Remove support for IE 10
- Remove support for iOS < 9.1
- Remove most -webkit and -moz vendor prefixes
- Remove named component Constructors

### Fixed

- Make Accordion component accessible through keyboard
- Make `uk-visible-toggle` accessible through keyboard
- Make `uk-transition-toggle` accessible through keyboard
- Fix scrolling with scrollbar on Modal closes Modal
- Fix `container` options
- Fix initializing Icon components programmatically
- Fix accordion initial active option
- Fix webpack builds (npm run test)
- 'uk-scrollspy-class' attr may now be `data-` prefixed too
- Fix dialogs not being removed from DOM after closing

## 3.0.0 beta 35 (November 13, 2017)

### Added

- Parallax supports RGB and RGBA now

### Fixed

- Fix Modal toggling if Tab components media setting is active
- Fix Tab component regression
- Fix context selectors that are applied to elements with ids containing special characters
- Fix reactivity in Leader component
- Fix events triggered by Accordion component
- Fix text wrapping for Firefox in Position component
- Fix Scrollspy triggering before other components have been applied at least once
- Fix Accordion title click behavior
- Fix Sortable on iOS
- Fix Sticky Navbar (IE 11)

## 3.0.0 beta 34 (November 7, 2017)

### Fixed

- Fix "Illegal invocation" error in Slideshow component
- Fix Offcanvas animations
- Fix Tab component if no lists are connected

## 3.0.0 beta 33 (November 3, 2017)

### Added

- Add Thumbnav component
- Add large margin modifier to Position component

### Changed

- IMPORTANT: Remove `@slidenav-padding`. Use new `@slidenav-padding-vertical` and `@slidenav-padding-horizontal`
- IMPORTANT: Sortable component now triggers `moved`, `added` and `removed` events instead of `change`
- Update Dotnav and Slidenav style
- Lightbox navigation no longer stacks on keyboard input
- Allow text selection within the Slideshow component
- Prevent vertical scrolling while swiping the Slideshow
- Remove tap highlighting when swiping the Slideshow in iOS

### Fixed

- Prevent Modal from toggling if event was defaultPrevented
- Fix using Scrollspy Nav within Sticky component
- Hide Slidenav in Lightbox if single item only
- Fix Parallax background image positioning
- Fix setting headers in AJAX request
- Fix dotnav box-sizing
- Fix Slideshow animations
- Fix Sortable component sorting animation when sorting between lists
- Fix event registration if `el` option is array
- Slideshow navigation items may now be `data-` prefixed too

## 3.0.0 beta 32 (October 27, 2017)

### Added

- Add `min-height` option to Height Viewport component

### Changed

- Improve accelerated slide animations in Slideshow component
- Improve slide dragging behaviour in Slideshow component

### Fixed

- Fix slide animations stacking when tab is not focused in Slideshow component
- Fix overlay not showing in Offcanvas component
- Fix Slideshow Parallax in Slideshow component for IE11
- Fix default border-radius for button elements in Chrome 62.

## 3.0.0 beta 31 (October 20, 2017)

### Added

- Add Slideshow component
- Add style support for radio and checkbox in Firefox
- Add `autoplay` setting to Lightbox
- Add `poster` setting to Lightbox items

### Changed

- IMPORTANT: Remove jQuery dependency
- Remove `uk-section-media` from Section component
- Change `uk-tab-left` text alignment to left
- Update Overview in tests
- Rename `isWithin` to `within`
- Allow fullscreen mode for YouTube and Vimeo videos in Lightbox
- Video component now stops playing the video regardless of the `autoplay` setting

### Fixed

- Fix responsive images in modal for IE11
- Fix close button outside causing a scrollbar on small devices
- Fix inverse style for `uk-hr`
- Fix video size of Vimeo videos in Lightbox component
- Fix closing stacked modals

## 3.0.0 beta 30 (August 18, 2017)

### Fixed

- Fix regression for IE11

## 3.0.0 beta 29 (August 18, 2017)

### Changed

- Media options now support any valid media query syntax

### Fixed

- Fix whitespace trimming in dist
- Fix active drop in `click` mode close on `hover` in Navbar component
- Fix `selTarget` option in Sticky component
- Fix icons not displaying if connected/disconnected in rapid succession
- Ensure Navbar component does not initialize Drop components if Dropdown is already present
- Fix scrollbar jumping in Switcher
- Fix usage of Scroll component in Drop, Dropdown, Navbar and Offcanvas in `overlay` mode
- Fix cursor set to pointer for icons
- Fix Scrollspy Nav not working correctly when zoomed in
- Fix animations for Firefox
- Fix icons not displaying if lazy loaded

## 3.0.0 beta 28 (August 01, 2017)

### Added

- Add Sticky Navbar test
- Add inverse style for button link

### Changed

- IMPORTANT: Rename `closeAlert` method to `close` in Alert component
- IMPORTANT: Rename `close` param to `selClose` in Alert component
- IMPORTANT: Rename `scrollToElement` method to `scrollTo` in Scroll component
- Add box-shadow to dropbar slide

### Fixed

- Fix icon color for Edge
- Add workaround to mitigate the duplicating icons issue
- Fix issue with multilevel dropdown
- Fix compatibility issue with Prototype and MooTools
- Fix Sticky Navbar behaviour
- Fix Parallax for IE11
- Fix swiping in Lightbox
- Fix alert close animation

## 3.0.0 beta 27 (July 20, 2017)

### Fixed

- Remove stacking context for `uk-inline`
- Prevent scrolling in Lightboxes with one slide only

## 3.0.0 beta 26 (July 20, 2017)

### Added

- Add Lightbox component
- Add Video component

### Changed

- IMPORTANT: Remove caption from Modal component. Use Lightbox component instead
- IMPORTANT: Remove lightbox modifier from Modal component. Use Lightbox component instead
- IMPORTANT: Remove center option from Modal component. Use `uk-margin-auto-vertical` modifier
- IMPORTANT: Renamed `@modal-dialog-margin-vertical` to `@modal-padding-vertical-s`
- IMPORTANT: Renamed `@modal-dialog-margin-vertical-xs` to `@modal-padding-vertical`
- Refactored Modal component
- `offsetTop` in Height Viewport component only applies if its element's top position is smaller than half the viewport
- Larger width for form width x-small

### Fixed

- Offcanvas will keep scroll position if anchor link was clicked
- Fix margin modifier in Position component for IE11
- Fix divider-small text alignment for `hr` elements Edge and IE
- Fix setting the ratio of Spinner component
- Fix event handling in Sortable component
- Fix grid calculation (Firefox)
- Fix dropdown margins in the dropbar
- Fix opening Modals from Offcanvas

## 3.0.0 beta 25 (June 9, 2017)

### Added

- Add size modifier to Tile component
- Add link text to Link component
- Add 500px icon

### Changed

- Larger horizontal padding for form input, select and textarea
- Improve Parallax Background Position behaviour

### Removed

- Remove padding xlarge from Padding component

### Fixed

- Fix touch event handling
- Fix cursor height for active forms in Safari
- Fix Grid and Margin component for cells with no height
- Fix Parallax if element is translated vertical
- Fix Grid divider in RTL mode

## 3.0.0 beta 24 (May 22, 2017)

### Changed

- Make Icon component work with button elements

### Fixed

- Fix margin bottom behaviour in Grid Parallax
- Fix error thrown by Notification component
- Fix `expand` mode in Height Viewport component
- Fix background position behaviour in Parallax component
- Fix removal of classes after sorting in Sortable component

## 3.0.0 beta 23 (May 18, 2017)

### Added

- Add Parallax component
- Add Grid Parallax component
- Add Form Range component
- Add Marker component
- Add hidden classes for touch devices to Visibility component
- Add padding xlarge to Padding component
- Add transform center to Utility component
- Add `clsBelow` option for Sticky component (uk-sticky-below)

### Changed

- IMPORTANT: Move LESS/Sass imports into one file. Use `components/_import.less`
- IMPORTANT: Renamed `transition` option to `easing` in Scroll component
- Improve flip behaviour in Drop component
- Improve `class` handling

### Fixed

- Fix support for more than two digits in Countdown component
- Fix typo in Togglable mixin name
- Fix form select image for RTL
- Fix Scrollspy `cls` option
- Fix HeightMatch not working on initial page load
- Fix touch events
- Fix click event firing twice (iOS <= 9.2)
- Fix missing table hook
- Prevent initial page jump (Safari)
- Fix document height calculation (IE 10)
- Fix Tooltip recreates on hovering the already focused input

## 3.0.0 beta 22 (April 24, 2017)

### Added

- Add Countdown component
- Add divider, justify and responsive modifier to Table component
- Add inverse support for Table component
- Add box-shadow bottom to Utility component

### Changed

- IMPORTANT: Remove style from default Table component. Use `uk-table-divider` modifier
- Move border style to table row instead of table cell
- Remove margin from the last-child in Table component cell

### Fixed

- Fix swiping in Switcher
- Fix scrolling in Scrollspy Nav (Firefox)
- Fix Navbar Dropbar
- Fix Tooltip with different animations
- Fix Sass showing error when using different color mode in certain components

## 3.0.0 beta 21 (April 11, 2017)

### Added

- Add Gitter icon
- Attribute observer listens for changes to `component` attribute too

### Fixed

- Fix Instagram, Tumblr and Vimeo icons
- Fix unexpected closing of Modal Dialog
- Fix `click` default behaviour prevention in Toggle
- Fix memory leak in Icons

## 3.0.0 beta 20 (April 5, 2017)

### Added

- Add breakpoint classes for flex alignment

### Fixed

- Fix Drop positioning
- Fix imports in Modal
- Fix `click` default behaviour prevention in Toggle
- Fix queued Toggle
- Fix closing Offcanvas with swipe gesture (Android)
- Fix Toggle icons preventing Drops from opening
- Fix loading UIkit deferred

## 3.0.0 beta 19 (March 31, 2017)

### Added

- Add Sass support
- Add Leader to Utility component
- Add Offcanvas close button
- Add margin auto vertical classes
- Add padding left/right remove classes
- Add Tripadvisor and Yelp icons
- Add computed properties

### Changed

- IMPORTANT: Offcanvas requires to wrap page in extra div
- Refactored Offcanvas component
- Update Instagram, Tumblr and Vimeo icons
- Component Constructor initializes multiple components at once

### Fixed

- Fix Offcanvas scrolling on touch devices
- Fix Scrollspy in view check
- Fix text wrapping for Firefox in Position component
- Fix closing Accordion without animation

## 3.0.0 beta 18 (March 10, 2017)

### Fixed

- Fix regression with positioning

## 3.0.0 beta 17 (March 10, 2017)

### Added

- Add Tile component
- Add grid item match modifier to Grid component
- Tooltip is now attribute reactive

### Changed

- Rename `uk-background` to `uk-background-default`
- Drop, Dropdown, Toggle component's mode is a comma separated list now (to support hover only mode)

### Fixed

- Fix deferred UIKit loading
- Fix Dropdowns not closing immediately upon hovering other navbar item in Navbar component
- Fix navbar groups center left/right (IE 11)
- Fix "sticky on up" behaviour in Sticky component
- Fix Offcanvas closing without animation
- Fix links in Notification message clickable
- Fix overriding default icons
- Fix Scrollspy nav when scrolling beyond last item

## 3.0.0 beta 16 (March 01, 2017)

### Fixed

- Fix Notification component

## 3.0.0 beta 15 (March 01, 2017)

### Fixed

- Fix dist

## 3.0.0 beta 14 (March 01, 2017)

### Changed

- Rename `.rtl` dist files to `-rtl`
- Include none minified JS files in dist

### Fixed

- Fix UMD/AMD dist

## 3.0.0 beta 13 (March 01, 2017)

### Added

- Add Receiver icon
- Add Hero heading modifier
- Add text background
- Add ID for AMD bundles

### Changed

- Move Icons into JavaScript
- Component Constructor initializes and returns single component only
- Rename function `show` to `toggle` in Accordion component
- Switcher no longer "swipes" with mouse
- Sticky component applies active class after scrolling below top

### Removed

- Remove text primary hook

### Fixed

- Fix npm not watching LESS
- Modal no longer closes immediately when toggled from custom `click` handler
- Fix Accordion component
- Fix container for Tooltip component
- Fix Dropdowns closing in Navbar component
- Fix Drops closing on click on hash links
- Fix Tab component not initializing
- Fix icon duplication

## 3.0.0 beta 12 (February 17, 2017)

### Added

- Add nested Drops
- Add text primary hook

### Changed

- Make Accordion selectors more specific
- Optimized margin modifier in Position component
- Drop component no longer forces `click` on touch devices

### Removed

- Remove obsolete webkitFontSmoothing workaround

### Fixed

- Fix text wrapping in Position component
- Fix icons in Safari's private browsing mode
- Fix right click triggers click event
- Fix empty targets in HeightMatch component
- Fix Tooltip component on touch devices

## 3.0.0 beta 11 (February 13, 2017)

### Fixed

- Fix icons not showing

## 3.0.0 beta 10 (February 13, 2017)

### Added

- Height Viewport component supports selector for Offset Bottom option
- Allow to preserve all color with one class when using `uk-svg`
- Add RTL support (RTL first)

### Changed

- Percentage value for Offset Bottom in Height Viewport component is calculated against the whole viewport

### Fixed

- Fix Notification component initialization
- Fix beta 8 regression with missing class in Navbar component
- Fix context selectors
- Sticky components sets inactive class initially
- Fix path to icons.svg in /custom folder
- Fix wrapping grid columns (IE + Edge)

## 3.0.0 beta 9 (February 3, 2017)

### Fixed

- Fix prefixed JavaScript not working
- Fix beta 8 regression with Scrollspy targets
- Fix width-expand not wrapping into next row in rare cases (Safari)

## 3.0.0 beta 8 (February 2, 2017)

### Added

- Apply class `uk-svg` to SVG component

### Changed

- Update event registration
- Use native Promises instead of jQuery Deferred

### Fixed

- Fix Cover component if the container has padding
- Fix Scrollspy component targeting wrong elements
- Switcher supports `data-` prefixed items now
- Fix beta 7 regression (IE <= 11)

## 3.0.0 beta 7 (February 1, 2017)

### Added

- Add sub groups center left/right to Navbar component
- Add box-shadow-hover to Utility component
- Height Viewport component supports pixel / percentage values for Offset Bottom option

### Changed

- LESS no longer uses component attribute selectors
- Accordion close and open icons using variables

### Removed

- Remove `uk-cover` CSS only solution

### Fixed

- Fix icon `play-circle`
- Fix Spinner when `stroke-width` cannot be read
- Fix memory leak in SVG component
- Prevent transition-toggle from setting a transition
- Fix width-expand not wrapping into next row in rare cases
- Allow a fixed width on nested grids with grid-match
- Fix Height Viewport offset calculation
- Fix Sticky (Chrome > 55)

## 3.0.0 beta 6 (January 24, 2017)

### Added

- Togglable triggers `shown`/`hidden` events, when animations complete

### Fixed

- Fix component initialization
- Fix Card component extending inverse
- Fix background-fixed (Firefox + IE)

## 3.0.0 beta 5 (January 18, 2017)

### Changed

- UIkit observes `body` element too now
- Performance improvements

### Fixed

- Fix regression with initialization (IE + Edge)
- Fix beta 2 regression for SVG’s (Safari)
- Fix Sticky width after resize
- Fix page width on resizing Offcanvas
- Fix props initialization for `data-uk-` components
- Fix sortable children loosing event bindings after sort

## 3.0.0 beta 4 (January 18, 2017)

### Fixed

- Fix Scrollspy Nav within Sticky (Safari)
- Fix beta 3 regression for Accordion
- Fix lazy initialized components

## 3.0.0 beta 3 (January 17, 2017)

### Added

- Add support for `data-uk-` prefixed component attributes
- Add support for Primary Arguments in components
- Add support for Functional Components
- Components reinitialize on added/removed children

### Fixed

- Fix sortable behaviour
- Fix link muted and link reset

## 3.0.0 beta 2 (January 11, 2017)

### Added

- Enable deferred loading of UIkit

### Changed

- Improve relative path to icons.svg

### Fixed

- Fix Icon component on canvas elements (Safari)

## 3.0.0 beta 1 (January 09, 2017)

### Added

- Initial release
