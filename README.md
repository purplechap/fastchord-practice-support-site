# fastchord-practice-support-site

Public support/configuration pages for the FastChords iOS and Android apps.

## Should pages be separated by platform?

Yes—keep platform-specific pages in separate folders, and keep only truly shared content in a common folder.

Recommended structure:

```text
/
├── ios/
│   ├── config/
│   ├── legal/
│   └── support/
├── android/
│   ├── config/
│   ├── legal/
│   └── support/
└── shared/
    ├── legal/
    └── support/
```

Use platform folders when app store metadata, app behavior, or required links differ by platform.  
Use `shared/` only for pages that are intentionally identical across both apps.
