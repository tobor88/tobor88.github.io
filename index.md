---
layout: splash
title: "OsbornePro Security Research"
permalink: /
classes: wide
author_profile: false

header:
  overlay_color: "#11111b"
  overlay_filter: "0.25"
  caption: "Offensive Security · Systems · Architecture"
  actions:
    - label: "Browse Writeups"
      url: "#hack-the-box-writeups"
    - label: "Hack The Box Profile"
      url: "https://app.hackthebox.com/public/users/52286"

excerpt: >
  Practical security research focused on understanding how systems fail,
  how trust boundaries are crossed, and how better architecture can prevent it.

feature_row:
  - title: "Windows & Identity"
    excerpt: >
      Active Directory, authentication, privilege escalation,
      PowerShell, Windows services, and identity attack paths.
    url: "#windows-machines"
    btn_label: "Windows Writeups"
    btn_class: "btn--primary"

  - title: "Linux & Infrastructure"
    excerpt: >
      Services, permissions, applications, network exposure,
      local privilege escalation, and system misconfiguration.
    url: "#unix-linux-machines"
    btn_label: "Linux Writeups"
    btn_class: "btn--primary"

  - title: "Advanced Labs"
    excerpt: >
      Longer multi-system attack paths, chained vulnerabilities,
      lateral movement, and complex trust relationships.
    url: "#endgame-labs"
    btn_label: "Endgame Labs"
    btn_class: "btn--primary"
---

# Security Through Adversarial Thinking

I use offensive-security labs to study how systems fail in practice:
misconfiguration, weak trust boundaries, authentication flaws,
privilege escalation, identity weaknesses, application vulnerabilities,
and the interaction between operating systems, networks, and services.

The goal isn't simply to complete a machine. It's to understand
**why the vulnerability existed, how the attack path developed, and what
could have been designed differently to prevent it.**

That perspective directly informs how I approach cloud, infrastructure,
identity, automation, and security architecture.

> Offensive security is one of the ways I pressure-test my understanding of defensive architecture.

---

{% include feature_row %}

---

## What This Research Demonstrates

<div class="research-grid">

<div class="research-card">
<h3>Cross-Domain Troubleshooting</h3>
<p>
Working across Windows, Linux, networking, identity, applications,
services, and infrastructure rather than treating each technology
as an isolated system.
</p>
</div>

<div class="research-card">
<h3>Security Analysis</h3>
<p>
Examining authentication, privilege boundaries, service exposure,
protocol behavior, insecure configurations, and application weaknesses.
</p>
</div>

<div class="research-card">
<h3>Adversarial Thinking</h3>
<p>
Understanding how systems can be abused so defensive architecture
can account for real attack paths rather than idealized assumptions.
</p>
</div>

<div class="research-card">
<h3>Technical Depth</h3>
<p>
Following attack paths from enumeration and initial access through
privilege escalation, credential discovery, and system compromise.
</p>
</div>

<div class="research-card">
<h3>Documentation</h3>
<p>
Turning technical investigation into repeatable walkthroughs that
explain the path, techniques, and underlying failure conditions.
</p>
</div>

<div class="research-card">
<h3>Defensive Architecture</h3>
<p>
Using lessons from offensive research to identify where stronger
identity controls, trust boundaries, configuration, and monitoring
could prevent or limit compromise.
</p>
</div>

</div>

---

# Hack The Box Writeups

The writeups below cover **retired Hack The Box systems and labs only**.

They are retained as a technical research library and as a record of hands-on work across Windows, Linux, identity, applications, networking, and security.

---

## Endgame Labs

These labs involve longer, multi-stage attack paths and are useful for studying how individual weaknesses can combine into broader system compromise.

<div class="lab-links" markdown="1">

[POO (Endgame)](https://writeups.osbornepro.com/POO.pdf){: .btn .btn--primary}
[Xen (Endgame)](https://writeups.osbornepro.com/Xen.pdf){: .btn .btn--primary}
[Hades (Endgame)](https://writeups.osbornepro.com/Hades.pdf){: .btn .btn--primary}

</div>

---

## Unix / Linux Machines

<details markdown="1">
<summary><strong>Easy Machines</strong> <span class="machine-count">30 writeups</span></summary>

- [Academy](https://writeups.osbornepro.com/Academy.pdf)
- [Admirer](https://writeups.osbornepro.com/Admirer.pdf)
- [Analytics](https://writeups.osbornepro.com/Analytics.pdf)
- [Backdoor](https://writeups.osbornepro.com/Backdoor.pdf)
- [BoardLight](https://writeups.osbornepro.com/BoardLight.pdf)
- [Bizness](https://writeups.osbornepro.com/Bizness.pdf)
- [Chemistry](https://writeups.osbornepro.com/Chemistry.pdf)
- [Codify](https://writeups.osbornepro.com/Codify.pdf)
- [Devvortex](https://writeups.osbornepro.com/Devvortex.pdf)
- [Doctor](https://writeups.osbornepro.com/Doctor.pdf)
- [Editorial](https://writeups.osbornepro.com/Editorial.pdf)
- [Friendzone](https://writeups.osbornepro.com/Friendzone.pdf)
- [Headless](https://writeups.osbornepro.com/Headless.pdf)
- [Keeper](https://writeups.osbornepro.com/Keeper.pdf)
- [Laboratory](https://writeups.osbornepro.com/Laboratory.pdf)
- [LinkVortex](https://writeups.osbornepro.com/LinkVortex.pdf)
- [Luanne](https://writeups.osbornepro.com/Luanne.pdf)
- [OpenAdmin](https://writeups.osbornepro.com/OpenAdmin.pdf)
- [Pandora](https://writeups.osbornepro.com/Pandora.pdf)
- [Perfection](https://writeups.osbornepro.com/Perfection.pdf)
- [PC](https://writeups.osbornepro.com/PC.pdf)
- [Pilgrimage](https://writeups.osbornepro.com/Pilgrimage.pdf)
- [Postman](https://writeups.osbornepro.com/Postman.pdf)
- [Sau](https://writeups.osbornepro.com/Sau.pdf)
- [Tabby](https://writeups.osbornepro.com/Tabby.pdf)
- [Topology](https://writeups.osbornepro.com/Topology.pdf)
- [Traceback](https://writeups.osbornepro.com/Traceback.pdf)
- [Traverxec](https://writeups.osbornepro.com/Traverxec.pdf)
- [Usage](https://writeups.osbornepro.com/Usage.pdf)
- [Writeup](https://writeups.osbornepro.com/Writeup.pdf)

</details>

<details markdown="1">
<summary><strong>Medium Machines</strong> <span class="machine-count">25 writeups</span></summary>

- [AI](https://writeups.osbornepro.com/AI.pdf)
- [Bitlab](https://writeups.osbornepro.com/Bitlab.pdf)
- [Book](https://writeups.osbornepro.com/Book.pdf)
- [Bucket](https://writeups.osbornepro.com/Bucket.pdf)
- [Cache](https://writeups.osbornepro.com/Cache.pdf)
- [Clicker](https://writeups.osbornepro.com/Clicker.pdf)
- [Craft](https://writeups.osbornepro.com/Craft.pdf)
- [Jewel](https://writeups.osbornepro.com/Jewel.pdf)
- [Luke](https://writeups.osbornepro.com/Luke.pdf)
- [Magic](https://writeups.osbornepro.com/Magic.pdf)
- [Mango](https://writeups.osbornepro.com/Mango.pdf)
- [Meta](https://writeups.osbornepro.com/Meta.pdf)
- [Monitored](https://writeups.osbornepro.com/Monitored.pdf)
- [Obscurity](https://writeups.osbornepro.com/Obscurity.pdf)
- [OpenKeyS](https://writeups.osbornepro.com/OpenKeyS.pdf)
- [Passage](https://writeups.osbornepro.com/Passage.pdf)
- [Surveillance](https://writeups.osbornepro.com/Surveillance.pdf)
- [SneakyMailer](https://writeups.osbornepro.com/SneakyMailer.pdf)
- [Time](https://writeups.osbornepro.com/Time.pdf)
- [Timing](https://writeups.osbornepro.com/Timing.pdf)
- [Undetected](https://writeups.osbornepro.com/Undetected.pdf)
- [Unicode](https://writeups.osbornepro.com/Unicode.pdf)
- [Wall](https://writeups.osbornepro.com/Wall.pdf)
- [WifineticTwo](https://writeups.osbornepro.com/WifineticTwo.pdf)
- [Zipping](https://writeups.osbornepro.com/Zipping.pdf)

</details>

<details markdown="1">
<summary><strong>Hard Machines</strong> <span class="machine-count">13 writeups</span></summary>

- [Compromised](https://writeups.osbornepro.com/Compromised.pdf)
- [Drive](https://writeups.osbornepro.com/Drive.pdf)
- [Feline](https://writeups.osbornepro.com/Feline.pdf)
- [ForwardSlash](https://writeups.osbornepro.com/ForwardSlash.pdf)
- [Intense](https://writeups.osbornepro.com/Intense.pdf)
- [Patents](https://writeups.osbornepro.com/Patents.pdf)
- [Player](https://writeups.osbornepro.com/Player.pdf)
- [Quick](https://writeups.osbornepro.com/Quick.pdf)
- [Registry](https://writeups.osbornepro.com/Registry.pdf)
- [Scavenger](https://writeups.osbornepro.com/Scavenger.pdf)
- [Travel](https://writeups.osbornepro.com/Travel.pdf)
- [Unbalanced](https://writeups.osbornepro.com/Unbalanced.pdf)
- [Zetta](https://writeups.osbornepro.com/Zetta.pdf)

</details>

<details markdown="1">
<summary><strong>Insane Machines</strong> <span class="machine-count">9 writeups</span></summary>

- [Bookworm](https://writeups.osbornepro.com/Bookworm.pdf)
- [CTF](https://writeups.osbornepro.com/CTF.pdf)
- [CrossFit](https://writeups.osbornepro.com/Crossfit.pdf)
- [Dyplesher](https://writeups.osbornepro.com/Dyplesher.pdf)
- [Fortune](https://writeups.osbornepro.com/Fortune.pdf)
- [PlayerTwo](https://writeups.osbornepro.com/Player2.pdf)
- [Rope](https://writeups.osbornepro.com/Rope.pdf)
- [RopeTwo](https://writeups.osbornepro.com/Rope%202.pdf)
- [Smasher2](https://writeups.osbornepro.com/Smasher2.pdf)

</details>

---

## Windows Machines

<details markdown="1">
<summary><strong>Easy Machines</strong> <span class="machine-count">15 writeups</span></summary>

- [Bastion](https://writeups.osbornepro.com/Bastion.pdf)
- [Blunder](https://writeups.osbornepro.com/Blunder.pdf)
- [Buff](https://writeups.osbornepro.com/Buff.pdf)
- [CozyHosting](https://writeups.osbornepro.com/CozyHosting.pdf)
- [Crafty](https://writeups.osbornepro.com/Crafty.pdf)
- [Forest](https://writeups.osbornepro.com/Forest.pdf)
- [Heist](https://writeups.osbornepro.com/Heist.pdf)
- [Mailing](https://writeups.osbornepro.com/Mailing.pdf)
- [Nest](https://writeups.osbornepro.com/Nest.pdf)
- [NetMon](https://writeups.osbornepro.com/NetMon.pdf)
- [Omni](https://writeups.osbornepro.com/Omni.pdf)
- [Remote](https://writeups.osbornepro.com/Remote.pdf)
- [Sauna](https://writeups.osbornepro.com/Sauna.pdf)
- [ServMon](https://writeups.osbornepro.com/ServMon.pdf)
- [Timelapse](https://writeups.osbornepro.com/Timelapse.pdf)

</details>

<details markdown="1">
<summary><strong>Medium Machines</strong> <span class="machine-count">14 writeups</span></summary>

- [Authority](https://writeups.osbornepro.com/Authority.pdf)
- [Cascade](https://writeups.osbornepro.com/Cascade.pdf)
- [Fuse](https://writeups.osbornepro.com/Fuse.pdf)
- [Hospital](https://writeups.osbornepro.com/Hospital.pdf)
- [Jab](https://writeups.osbornepro.com/Jab.pdf)
- [Json](https://writeups.osbornepro.com/Json.pdf)
- [Manager](https://writeups.osbornepro.com/Manager.pdf)
- [Monteverde](https://writeups.osbornepro.com/Monteverde.pdf)
- [Pov](https://writeups.osbornepro.com/Pov.pdf)
- [Querier](https://writeups.osbornepro.com/Querier.pdf)
- [Resolute](https://writeups.osbornepro.com/Resolute.pdf)
- [Sniper](https://writeups.osbornepro.com/Sniper.pdf)
- [Visual](https://writeups.osbornepro.com/Visual.pdf)
- [Worker](https://writeups.osbornepro.com/Worker.pdf)

</details>

<details markdown="1">
<summary><strong>Hard Machines</strong> <span class="machine-count">8 writeups</span></summary>

- [Appsanity](https://writeups.osbornepro.com/Appsanity.pdf)
- [Blackfield](https://writeups.osbornepro.com/Blackfield.pdf)
- [Conceal](https://writeups.osbornepro.com/Conceal.pdf)
- [Control](https://writeups.osbornepro.com/Control.pdf)
- [Helpline](https://writeups.osbornepro.com/HelpLine.pdf)
- [Napper](https://writeups.osbornepro.com/Napper.pdf)
- [Office](https://writeups.osbornepro.com/Office.pdf)
- [RE](https://writeups.osbornepro.com/RE.pdf)

</details>

<details markdown="1">
<summary><strong>Insane Machines</strong> <span class="machine-count">3 writeups</span></summary>

- [BankRobber](https://writeups.osbornepro.com/BankRobber.pdf)
- [HackBack](https://writeups.osbornepro.com/HackBack.pdf)
- [Multimaster](https://writeups.osbornepro.com/Multimaster.pdf)

</details>

---

## Legacy HTB Material

Some older HTB material is preserved here for historical reference.

- [Get HTB Invite Code](https://writeups.osbornepro.com/Get_HTB_Invite_Code.pdf)

---

# Beyond the Labs

Security research is one part of a broader body of work covering cloud architecture, infrastructure engineering, automation, secure systems, identity, and custom tooling.

<div class="external-links" markdown="1">

### Technical Case Studies

Architecture and engineering work covering real-world infrastructure, security, automation, and operational problems.

[Explore OsbornePro →](https://osbornepro.com){: .btn .btn--primary}

### Projects & Tooling

Custom software, security tooling, automation, and open-source projects.

[Personal GitHub →](https://github.com/tobor88){: .btn .btn--inverse}
[OsbornePro GitHub →](https://github.com/osbornepro){: .btn .btn--inverse}
[NovaKey →](https://novakey.app/){: .btn .btn--inverse}
[RDAP-CLI →](https://rdap-cli.osbornepro.com/){: .btn .btn--inverse}
[EncrypIT Documentation →](https://encrypit.osbornepro.com/){: .btn .btn--inverse}
[BTPS Security Pacakge →](https://btpssecpack.osbornepro.com/){: .btn .btn--inverse}
[PowerShell Gallery →](https://www.powershellgallery.com/profiles/tobor){: .btn .btn--inverse}

### Technical Content & Credentials

[OsbornePro TV →](https://www.youtube.com/c/OsborneProLLC){: .btn .btn--inverse}
[Hack The Box Profile →](https://app.hackthebox.com/public/users/52286){: .btn .btn--inverse}
[Credentials →](https://www.credly.com/users/roberthosborne/badges){: .btn .btn--inverse}

</div>

---

## Contact

For professional inquiries:

[**info@osbornepro.com**](mailto:info@osbornepro.com)
