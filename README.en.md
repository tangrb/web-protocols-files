# web-protocols-files

[中文](README.md)

This repository hosts legal and policy documents for mobile applications—such as privacy policies and terms of service—served as static HTML pages for App Store submissions, app marketplaces, and compliance review.

## Directory Structure

```
web-protocols-files/
├── index.html                          # Index page listing all documents
├── JuZiShu/
│   └── iOS/
│       └── privacy-policy.html         # JZS EPager Privacy Policy
├── MapAlarm/
│   └── iOS/
│       ├── privacy-policy.html         # Map Alarm Privacy Policy
│       └── support.html                # Map Alarm Support
├── README.md                           # Chinese documentation
└── README.en.md                        # English documentation (this file)
```

## Documents

| App | Platform | File | Description |
|-----|----------|------|-------------|
| JZS EPager | iOS | [JuZiShu/iOS/privacy-policy.html](JuZiShu/iOS/privacy-policy.html) | Privacy Policy |
| Map Alarm | iOS | [MapAlarm/iOS/privacy-policy.html](MapAlarm/iOS/privacy-policy.html) | Privacy Policy |
| Map Alarm | iOS | [MapAlarm/iOS/support.html](MapAlarm/iOS/support.html) | Support |

Once deployed, browse all document links from the repository root [index.html](index.html).

Public pages are served by **GitHub Pages**:

`https://tangrb.github.io/web-protocols-files/{path}`

| App | Public URL |
|-----|------------|
| JZS EPager | https://tangrb.github.io/web-protocols-files/JuZiShu/iOS/privacy-policy.html |
| Map Alarm · Privacy | https://tangrb.github.io/web-protocols-files/MapAlarm/iOS/privacy-policy.html |
| Map Alarm · Support | https://tangrb.github.io/web-protocols-files/MapAlarm/iOS/support.html |

Pages publishes the repository tree as-is.

## Adding a New Document

1. Create an HTML file under the appropriate app and platform directory, following the path pattern `{AppName}/{Platform}/{document-name}.html`.
2. Add an entry link in the document list on [index.html](index.html).
3. Update the document table in this file and [README.md](README.md).

## License

This project is licensed under the [Apache License 2.0](LICENSE).
