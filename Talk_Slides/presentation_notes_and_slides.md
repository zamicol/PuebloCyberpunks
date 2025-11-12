
PuebloCyberpunks.com
https://www.youtube.com/@PuebloCyberpunks
https://odysee.com/@PuebloCyberpunks










##########################
##########################
##########################
# 20251104 - Nix Sucks; Everything Else is Worse - Building Better Software Supply Chains - nrdxp (Tim Deherrera)
https://youtu.be/L8BBtBZXKac
https://odysee.com/@nrdxp:6/Nix-Sucks-Everything-else-is-Worse:4
Tim DeHerrera, a Nix contributor since 2017, critiques the limitations of
traditional package managers, virtual environments, and Docker in handling
dependency conflicts, reproducibility, and supply-chain security.

The core innovation presented is Atom — a packaging abstraction built on Git
tree objects, but decoupled from full commit history. Each atom is a
reproducible, detached Git commit referencing a specific tree object, enabling
lightweight, cryptographically verifiable references to package outputs without
requiring the entire repository history or unrelated files.

Package sets are modeled as mathematical sets: collections of atoms with
globally unique names and content-addressed identities, enforced via
cryptographic hashes. This eliminates version conflicts and supports
decentralized, mirrorable distribution.

Eka is a Rust-based CLI providing a high-level interface to Nix, with:

    Atom creation and semantic versioning
    Decentralized dependency resolution
    Deterministic lock files with full provenance
    Compatibility with existing Nix expressions

Live demo: repository setup, atom publishing, dependency resolution, and
lock-file generation.

Project: https://github.com/ekala-project/eka

Discord: https://discord.gg/DgC9Snxmg7

Talk given:20251104
Slides: https://github.com/ekala-project/eka/pull/34
https://github.com/ekala-project/eka/tree/master/docs/talks/examples





##########################
##########################
##########################
# 20251024 - Introduction to Coze - zamicol (Zach Collier)
https://www.youtube.com/watch?v=5dxpcJ8FbPk
Coze is a cryptographic JSON messaging specification that uses digital signatures and hashes to ensure secure, human-readable, and interoperable communication.

The meat of the presentation starts @27:30

https://github.com/Cyphrme/Coze

Talk given: 20251024
Slides: https://docs.google.com/presentation/d/1bVojfkDs7K9hRwjr8zMW-AoHv5yAZjKL9Z3Bicz5Too/edit?slide=id.g121f82e33f2_0_0#slide=id.g121f82e33f2_0_0




##########################
##########################
##########################
# 20251007 Structured IT Documentation: The Backbone of Cyber Resilience for IT Operations - Michael Lamb-Rollison
https://www.youtube.com/watch?v=_30vFripcKI
Structured IT documentation is the foundational backbone of cyber resilience,
driving efficiency, compliance (NIST, ISO 27001, SOC 2), and rapid incident
response while reducing downtime and enabling team coordination. The agenda
covers essential practices including uniform formats and centralized storage
(e.g., SharePoint, ITGlue, or ITFlow), configuration templates with automation
tools like Ansible to prevent drift, detailed Standard Operating Procedures
(SOPs) distinguishing processes from procedures, network diagrams with switch
interface descriptions, hardware/server inventories, and documentation for
wireless, WAN, shares, VoIP, ticketing, and change management. Emphasizing
scheduled reviews, actionable visuals, and real-world impacts—such as halving
outage resolution times—Lamb-Rollison concludes with key takeaways urging
quarterly document reviews to strengthen defenses, ensure auditable changes, and
mitigate breaches through consistency and preparedness.

Talk given 20251007
Slides: https://securesecond61-my.sharepoint.com/:b:/g/personal/michael_lambrollison_second-61_com/EW0Skct8xmhAvSH-T0yosDEBUkViDij6CdSdg2Mr--se5Q?e=ZbKPcz




##########################
##########################
##########################
# 20250902 - Tools to Fight Back Against the Darkness - Csilla Brimer
https://www.youtube.com/watch?v=K8dCp8CVxZ4
Join us to hear from our guest speaker, Csilla Brimer, a relentlessly cheerful privacy advocate and author of Gamify or Die, Blockchain Gamification, and Monero advocate.

Talk give: 20250902
Slides: https://www.canva.com/design/DAGwnojVSHc/cwkgi657ChNh12Dd6aJcnw/view?utm_content=DAGwnojVSHc&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hb4721480ec





##########################
##########################
##########################
# 20250802 Hacking Laboratory Information Medical Systems for Fun and Profit - Tyler Cox
https://www.youtube.com/watch?v=vOdTrPb5_2A&t=56s
Tyler recounts his experience automating a overwhelmed COVID-19 testing lab's
information system during the pandemic's peak. Facing massive backlogs in manual
result processing that delayed critical patient notifications, especially around
holidays. Tyler exposes the fragile, rate-limited software riddled with
vulnerabilities like static basic authentication and unsigned automation tools.
From initial failures with Power Automate farms and SSH blocks, they pivot to
Fiddler Classic for HTTPS traffic decryption, craft shell scripts for CLI
access, and build robust database-tracked automation to blitz through thousands
of negative tests. The result? Cleared delays, faster public health decisions,
and a candid reflection on ethical hacking for the greater good, juxtaposed with
the lab's profits and the hacker's lack of recognition in a broken healthcare
ecosystem.

Talk given: 20250802
Slides: https://github.com/zamicol/PuebloCyberpunks/blob/master/Talk_Slides/20250802_Hacking_laboratory_information_medical_systems_for_fun_and_profitTyler_Cox.pdf




##########################
##########################
##########################
# 20250603 OpenSense - @kurodensetsu (Nathan Ritchey):
https://www.youtube.com/watch?v=RW8IIDCaEI8
Join network engineer Nathan Ritchey as he dives into OPNsense, the powerful
open-source firewall and router forked from pfSense, built on FreeBSD with a
user-friendly web GUI, modular plugins, and enterprise-grade features. Discover
why OPNsense outperforms off-the-shelf routers in security, stability, and
customization—complete with robust firewall rules, NAT, GeoIP blocking, 2FA,
traffic shaping, VLANs, VPN support (including WireGuard), and IDS/IPS via
Suricata. Learn to build your own high-performance OPNsense router for under
$140 using upcycled hardware like Dell Optiplex desktops, Intel NICs, and SSDs,
plus tips on ruleset tuning, plugins like Zenarmor and HAProxy, and essential
setup steps. Perfect for home labs, learning enterprise networking, or replacing
vulnerable ISP gateways!

Talk given: 20250603

Slides: https://docs.google.com/presentation/d/15zBU1jI9eLAXlFbztQJN7sYfiKCDrH7TiT1jEF4cE6Q/edit?slide=id.g35e1fd85295_0_454#slide=id.g35e1fd85295_0_454




##########################
##########################
##########################
# 20250401 OpenBSD the Little OS That Could - qbit (Aaron Bieber): 
https://www.youtube.com/watch?v=h80Ykfk4Odw
In this talk, "OpenBSD: The Little OS That Could," qbit traces OpenBSD's journey
from its 1995 NetBSD fork to a compact, security-first Unix-like system known
for clean code, proactive audits, and default-hardened design. Covering
milestones like W^X (2003), LibreSSL (2014), and pledge/unveil system calls for
runtime confinement, the presentation highlights OpenBSD’s sub-500MB base
install, pf firewall, and reliable use in routers and embedded devices. With
annual releases, aggressive fuzzing, and a philosophy prioritizing correctness
and minimalism, qbit shows why OpenBSD remains a trusted, understated powerhouse
for secure infrastructure despite its small footprint and developer base.

Talk given: 20250401
Slides: https://github.com/qbit/openbsd-tlotc/blob/main/openbsd-tlotc.pdf
https://github.com/qbit/openbsd-tlotc/tree/main





##########################
##########################
##########################
# 20241001 The Evolving Playbook of ICS/SCADA Cyber Attacks - Austin Tapia
https://docs.google.com/presentation/d/1udeZyLyzeN82d4wHegeISM8aNJj8lEkl/edit?usp=sharing&ouid=112649556199426365922&rtpof=true&sd=true


Talk given: 20241001
Slides: 