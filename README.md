# Baran Ayaztaş

Security researcher and full-stack developer based in Istanbul. Started in
security, now split between offensive/defensive tooling and web/mobile
product work.

Small, single-purpose security CLIs:

**AI & LLM security**

- [sift](https://github.com/ReazGan/sift) - scans AI agent instruction files (CLAUDE.md, .cursorrules, mcp.json) for hidden or planted instructions. `pip install siftscan`
- [ajar](https://github.com/ReazGan/ajar) - finds exposed, unauthenticated local AI servers (Ollama, ComfyUI, vLLM, ...). Single binary, Go.

**CI/CD & supply chain**

- [cicheck](https://github.com/ReazGan/cicheck) - security linter for GitLab CI, CircleCI, Azure, Bitbucket, Drone, Travis. `pip install cicheck`
- [depsweep](https://github.com/ReazGan/depsweep) - supply-chain risks in npm/pip dependencies: install hooks, typosquats, insecure sources. `pip install depsweep`
- [dockaudit](https://github.com/ReazGan/dockaudit) - Dockerfile and docker-compose security. Single binary, Go.

**Web, recon & hardening**

- [spill](https://github.com/ReazGan/spill) - API keys and secrets left in a site's client-side code. Single binary, Go.
- [subtakeover](https://github.com/ReazGan/subtakeover) - subdomain takeover scanner, CNAME fingerprints confirmed with a live HTTP check
- [wraith](https://github.com/ReazGan/wraith) - HTTP header/TLS/port misconfiguration scanner
- [urlgrave](https://github.com/ReazGan/urlgrave) - historical URL/subdomain harvester (Wayback + crt.sh)
- [subrecon](https://github.com/ReazGan/subrecon) - subdomain enumeration
- [pathbrute](https://github.com/ReazGan/pathbrute) - HTTP directory/path brute-forcer with soft-404 filtering
- [jwtlint](https://github.com/ReazGan/jwtlint) - offline JWT analyzer: alg:none, RS/HS confusion, kid injection, weak secrets. `pip install jwtlint`
- [sshield](https://github.com/ReazGan/sshield) - SSH server/client configuration hardening audit. `pip install sshield`
- [leakscan](https://github.com/ReazGan/leakscan) - secret/API-key scanner for local files
- [cellar](https://github.com/ReazGan/cellar) - local encrypted secrets vault

**Game servers**

- [fxsweep](https://github.com/ReazGan/fxsweep) - FiveM server backdoor scanner: Cipher/Blum Panel loaders, encoded payloads, webhooks leaked to players. Single binary, Go.

**Stack:** Python, Go, TypeScript/React, Next.js.

**Contact:** [LinkedIn](https://tr.linkedin.com/in/baranayaztas)
