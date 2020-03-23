# Note-Keynote-Chrome-Dev-Summit-2019

## Keynote
- PWA (new installation for desktop)
- Trusted Web Activities (For Android development which show web pages)
- Notifications (Action Images, Buttons, Notification triggers)
- Contact Picker API
- Native File System API
- WebAssembly

## Instant, responsive web experiences
- Signed exchanges
- Portals
- Periodic Background Sync API
- Content Indexing API
- Web Bundles
- Backdrop filter
- CSS.registerProperty()
- LayoutNG
- Display Locking

## Seamless, smooth transactions
- WebAuthn
- SMS Receiver API
- Payment Request API (Web Payments)

## Monitoring
- PageSpeed Insights
- Google Search Console
- Largest Contentful Paint (LCP)
- Cumulative Layout Shift (CLS) (Layout Stable API)
- Lighthouse CI

## Chrome
- Lazy loading
- Paint Holding
- Blocking All Mixed Content
- Privacy Sandbox (Build-in protections, Password Manager, Site Isolation)

## Next-generation web styling (Chrome Dev Summit 2019)
- Scroll-snap
- :focus-within
- @media(prefers-*)
  - prefers-reduced-motion (hook to pacify movement for sensitive folks)
    - no-preference
    - reduce
  - prefers-color-scheme (hook to adapt your UI to be easier on the eyes of a user)
    - no-preference
    - light
    - dark
  - Coming soon
    - prefers-contrast
    - prefers-reduced-transparency
    - forced-colors
    - light-level
- Logical properties
- Sticky Situations
- backdrop-filter
- :is()
- gap (for flexbox - currently in firefox only)
- Houdini
- Properties & Values API
- Typed OM
- Paint API
- Animation Worklet
- size `.box { size: 50vw }`
- aspect-ratio `iframe { aspect-ratio: 16 / 9 }`
- min(), max(), clamp() `h1 { font-size: clamp(1.5rem, 6vw) }`
- list style type `ul { list-style-type: '🐶' }`
-  display: outer inner `section { display: grid inline-flex }`
- CSS regions `article { flow-into: articles }` `region { flow-from: articles }`

## Adaptive Loading - Improving web performance on slow devices (Chrome Dev Summit 2019)
- Different resources loading for different type of hardware
