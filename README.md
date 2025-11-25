VirtualBox Host-Only Intrusion Detection Lab
Overview

This repository provides a hands-on cybersecurity lab built with VirtualBox to simulate attack and defense scenarios in a controlled environment. The lab consists of two virtual machines:

    KaliAttacker: Kali Linux Purple Edition configured with penetration testing tools.

    UbuntuDefender: Ubuntu Desktop with Snort IDS installed for intrusion detection.

Both machines are connected via a VirtualBox Host-Only Adapter, ensuring complete isolation from external networks. This setup allows safe experimentation with intrusion detection, traffic monitoring, and custom rule development.
Features

    🔒 Isolated Lab Network: Host-only adapter prevents exposure to external systems.

    ⚔️ Attacker VM: Kali Linux Purple Edition with offensive security tools.

    🛡️ Defender VM: Ubuntu Desktop running Snort IDS for real-time detection.

    📡 Traffic Monitoring: Analyze and log suspicious activity with customizable Snort rules.

    🎓 Educational Focus: Ideal for students, researchers, and professionals learning IDS concepts.

Prerequisites

    VirtualBox (latest version recommended)

    ISO images for:

        Kali Linux Purple Edition

        Ubuntu Desktop (20.04 or later recommended)

    Basic knowledge of networking and Linux command line

