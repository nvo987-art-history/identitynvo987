This directory contains the signed identity profile
for did:web:identity.nvo987.us.

Files:
- person.jsonld — signed identity document
- person.jsonld.sha256 — SHA256 checksum
- person.jsonld.ots — OpenTimestamps proof

Verification:

sha256sum -c person.jsonld.sha256
ots verify person.jsonld.ots
