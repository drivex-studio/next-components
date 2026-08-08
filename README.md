# next-components

current structure:

next-components
├── README.md
├── jsconfig.json
├── next.config.mjs
├── package.json
├── public
│   ├── app.css
│   └── fonts
│       ├── AktivGroteskCorp-Regular.woff2
│       ├── GeistMono-Medium.woff2
│       └── GeistMono[wght].woff2
└── src
    ├── app
    │   └── layout.js
    ├── components
    │   ├── shared
    │   │   ├── LazyCustomCursor.js
    │   │   └── useDualLayerScramble.js
    │   └── ui
    │       └── CustomCursor.js
    ├── contexts
    │   ├── PageEnterProvider.js
    │   ├── PageTransitionProvider.js
    │   ├── PreloaderProvider.js
    │   ├── ScrambleGroupContext.js
    │   └── shared
    │       ├── useIdleGSAP.js
    │       ├── usePageEnter.js
    │       └── usePageTransition.js
    ├── features
    │   ├── animations
    │   │   ├── AnimatedButton.js
    │   │   ├── AnimatedLink.js
    │   │   ├── ScrambleText.js
    │   │   └── pageLoader.js
    │   └── services <— CMS ( sanity data )
    │       └── SanityLink.js
    ├── pages
    │   ├── NotFoundPage.jsx
    │   └── app.js
    └── utilities
        └── smoothScroll.js

14 directories, 27 file

