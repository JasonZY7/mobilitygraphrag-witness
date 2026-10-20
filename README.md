# MobilityGraphRAG — public witness

This repository holds nothing but hashes. The file `stage1/registry_seal_witness.txt` will carry, once and
exactly once, the RFC 3161 receipt message of the Stage-1 test-set registry seal of the private repository
`JasonZY7/MobilityGraphRAG` (`registry-seal|<ledger-line sha256>|<commit>|<ledger blob sha256>`) and the
sha256 of the TSA token over it. Its public, third-party-timestamped capture by the Internet Archive
(`https://web.archive.org/cdx/search/cdx?url=https://raw.githubusercontent.com/JasonZY7/mobilitygraphrag-witness/main/stage1/registry_seal_witness.txt&output=json`)
is what the draw tool verifies at the seed reveal and at every replay (protocol section 5, amendment A-031).
Files under `rehearsal/` are rehearsals of the procedure and carry no authority.
