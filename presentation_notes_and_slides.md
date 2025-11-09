


# 20251104 - nrdxp (Tim Deherrera) From Nix to Eka
Tim DeHerrera, a Nix contributor since 2017, critiques the limitations of traditional package managers, virtual environments, and Docker in handling dependency conflicts, reproducibility, and supply-chain security.

The core innovation presented is Atom — a packaging abstraction built on Git tree objects, but decoupled from full commit history. Each atom is a reproducible, detached Git commit referencing a specific tree object, enabling lightweight, cryptographically verifiable references to package outputs without requiring the entire repository history or unrelated files.

Package sets are modeled as mathematical sets: collections of atoms with globally unique names and content-addressed identities, enforced via cryptographic hashes. This eliminates version conflicts and supports decentralized, mirrorable distribution.

Eka is a Rust-based CLI providing a high-level interface to Nix, with:

    Atom creation and semantic versioning
    Decentralized dependency resolution
    Deterministic lock files with full provenance
    Compatibility with existing Nix expressions

Live demo: repository setup, atom publishing, dependency resolution, and lock-file generation.

Project: https://github.com/ekala-project/eka

Discord: https://discord.gg/DgC9Snxmg7

Presented on Tuesday, November 4, 2025

Slides
https://github.com/ekala-project/eka/pull/34
https://github.com/ekala-project/eka/tree/master/docs/talks/examples






# 202510 Structured Documentation the Backbone of Cyber Resilience for IT Operations Michael Lamb
https://www.youtube.com/watch?v=_30vFripcKI












# @kurodensetsu (Nathan Ritchie):
https://docs.google.com/presentation/d/15zBU1jI9eLAXlFbztQJN7sYfiKCDrH7TiT1jEF4cE6Q/edit?slide=id.g35e1fd85295_0_454#slide=id.g35e1fd85295_0_454









# qbit (Aaron Bieber): 
https://github.com/qbit/openbsd-tlotc/tree/main










# 20250902 - Csilla Brimer - Tools to Fight Back Against the Darkness
Join us to hear from our guest speaker, Csilla Brimer, a relentlessly cheerful privacy advocate and author of Gamify or Die, Blockchain Gamification, and Monero advocate.

Slides:
https://www.canva.com/design/DAGwnojVSHc/cwkgi657ChNh12Dd6aJcnw/view?utm_content=DAGwnojVSHc&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hb4721480ec















# THE EVOLVING PLAYBOOK OF ICS/SCADA CYBER ATTACKS - Austin Tapia
https://docs.google.com/presentation/d/1udeZyLyzeN82d4wHegeISM8aNJj8lEkl/edit?usp=sharing&ouid=112649556199426365922&rtpof=true&sd=true


# 20251024 - Introduction to Coze - zamicol (Zach Collier)

https://www.youtube.com/watch?v=5dxpcJ8FbPk
https://docs.google.com/presentation/d/1bVojfkDs7K9hRwjr8zMW-AoHv5yAZjKL9Z3Bicz5Too/edit?slide=id.g121f82e33f2_0_0#slide=id.g121f82e33f2_0_0