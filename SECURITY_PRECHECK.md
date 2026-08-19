# Repository Security & Privacy Precheck

This is a pre-promotion checklist for Malik Hashir's GitHub consolidation.

The goal is not only to make repositories look better. A recruiter-facing account should also avoid exposing credentials, private client information, or unclear third-party provenance.

---

## 1. `ihashirr/Arduino` — fix before transfer or promotion

### Finding

The public Arduino sketch currently contains Wi-Fi network configuration directly in source code, including a hardcoded network name and password.

### Required action

Before transferring or featuring the project:

1. remove the real Wi-Fi credentials from tracked source
2. replace them with placeholders or a local ignored secrets/config header
3. add the secret/config file to `.gitignore`
4. rotate the exposed Wi-Fi password if it is still in use
5. review Git history if the credential should not remain recoverable from previous commits

Example public configuration pattern:

```cpp
#include "secrets.h"

const char* ssid = WIFI_SSID;
const char* password = WIFI_PASSWORD;
```

with an ignored local file such as:

```text
secrets.h
```

and a safe committed example:

```text
secrets.example.h
```

Do not promote this repository until that cleanup is complete.

---

## 2. `iamhashir/ipac-operations-app` — private repository secret hygiene

### Finding

The private repository contains a tracked `.env` file in addition to `.env.example`.

### Required action

Before any future publication or sharing:

1. confirm whether `.env` contains live credentials
2. ensure `.env` is ignored going forward
3. rotate live keys if they were ever exposed outside the intended private scope
4. never publish the repository without removing private business/client configuration and historical secrets

This repository should remain private and be represented publicly only through a sanitized case study unless there is explicit permission to release it.

---

## 3. `ihashirr/Qrcode_nisrine` — privacy/client-data review

### Finding

The repository is technically strong, but its public documentation contains company-specific operational information, product identifiers, contact details, and barcode/GTIN context.

### Required action

Before moving it onto the main recruiter-facing account:

1. confirm that the business/client information is intended to be public
2. remove or generalize details that are not necessary to demonstrate the engineering
3. keep enough implementation detail to explain validation, barcode generation, compositing and build-time checks
4. prefer sample/demo data when real operational identifiers are unnecessary

The technical story should survive even if the client-specific data is replaced with safe examples.

---

## 4. `iamhashir/clevland` — provenance / authorship clarity

### Finding

The project is technically interesting, but current repository presentation references cloning another source repository.

### Required action

Before featuring it:

1. identify what code is original vs. based on/upstream from another project
2. preserve attribution and license requirements
3. rewrite the README so Malik's actual contributions are explicit
4. do not imply authorship of upstream code

If the original contribution cannot be explained cleanly, keep it secondary rather than pinning it.

---

# Promotion gate

A repository should not become a flagship/pinned project until it passes:

- [ ] no live credentials in tracked public source
- [ ] no unnecessary private/client data
- [ ] third-party code/provenance is clearly attributed
- [ ] README claims match implementation
- [ ] demo links do not expose private systems
- [ ] screenshots do not contain confidential data

---

## Rule

> A strong GitHub profile is not only polished. It is safe to inspect publicly.
