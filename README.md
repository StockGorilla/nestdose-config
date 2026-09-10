# nestdose-config

Public feature flags + minimum-supported-build config for the Nestdose iOS app.

The app polls `app-config.json` on launch and every time it foregrounds. Bumping
`minSupportedBuild` here immediately gates users on older builds behind a
"please update" screen.

There are no secrets in this repo — everything here is intentionally public.
