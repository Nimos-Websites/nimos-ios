# Nimos iOS

The Nimos app — talk to your CEOs and triage every media funnel from your phone.

Part of the [Nimos](https://github.com/Nimos-Websites/nimos) platform — the AI workforce
OS this app talks to. The Expo foundation it builds on lives at
[ios-kit](https://github.com/Nimos-Websites/ios-kit).

## Run it

```bash
npm install
npm run ios        # iOS simulator
npm run android    # Android emulator
npm run web        # browser
npm run typecheck  # tsc --noEmit
npm run doctor     # Expo diagnostics
```

## Build

```bash
npm run eas:login
npm run eas:build:ios     # EAS cloud build
npm run export:ios        # JS bundle, no native build
```

## Layout

- `app/` — screens
- `src/` + `components/` — UI and logic
- `assets/` — fonts and images
- `scripts/` — build and device automation

## License

MIT — see [LICENSE](./LICENSE).
