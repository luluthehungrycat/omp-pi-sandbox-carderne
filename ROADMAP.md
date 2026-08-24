# Carderne Sandbox OMP Roadmap

## Completed

- [x] OMP 18 runtime/type/UI import port.
- [x] Public no-token install: `omp plugin install github:luluthehungrycat/omp-pi-sandbox-carderne#v0.6.6`.
- [x] GitHub Packages publication: `@luluthehungrycat/omp-pi-sandbox-carderne@0.6.6`.
- [x] 22/22 unit tests and TypeScript check.
- [x] Bun CI, public Git smoke CI, and release verification.
- [x] Podman containment gate.
- [x] Legacy official-npm release workflow removed.

## Next

- [ ] Run the shared OMP/Bun compatibility matrix on every supported release.
- [ ] Add package-loaded sandbox tool-call runtime coverage to the shared release gate.
- [ ] Keep the Carderne runtime policy and OMP permission UI behavior covered by integration fixtures.

## Release gate

No release is complete unless public Git install, package install, `omp plugin doctor`, and the containment probe pass.
