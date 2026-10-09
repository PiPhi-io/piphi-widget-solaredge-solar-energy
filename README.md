# SolarEdge Solar Energy widgets

Independent PiPhi Widget SDK package providing live energy flow and production summary cards.

The package is versioned and released independently. The PiPhi registry links it to compatible integrations and Core installs it as an automatic companion.

## Validate

```bash
npm ci
npm run validate
```

Release tags use `v<package-version>`. GitHub Actions signs the immutable archive with PiPhi's first-party widget publisher key and attaches the archive, signed manifest, and checksums to the release.
