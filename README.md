```text
$ ssh mark@github.com
                __
               / _)
      _.----._/ /
     /         /
  __/ (  | (  | It's a UNIX System!
 /__.-'|_|--|_|    I know this!

>
```

# 👋 Oh, hi. I'm Mark.

I work at [Red Hat](https://github.com/RedHatOfficial) out of Canberra, Australia, and my GitHub bio says *"I build Kubernetes clusters that nobody ever uses."*

That is not a joke. Give me bare metal, a switch, and a quiet afternoon and I will stand up a hardened, enterprise-grade **OpenShift** cluster with FreeIPA authentication, automated certificates, and five-nines uptime for a grand total of zero users. If an idle control plane hums in a rack in Canberra and nobody deploys an app to it, does it still pass a CIS audit? Yes. Yes it does.

When I am not over-engineering OpenShift clusters, I spend my time on **virtualization** and **automation**:

- **Virtualize everything**: VMs inside containers with **KubeVirt**, or **FreeBSD** hosts carved up into **Bhyve** VMs, **Jails**, and **ZFS** pools.
- **Automate the rest**: If I have to run a command twice, it goes into **Ansible** or **Salt** while I go make a coffee.

### 🛠️ Things I've Built (Instead of Going Outside)

- **[`sylve-cli`](https://github.com/mhahl/sylve-cli)**: A Python command-line client (`sylve(1)`) for managing [Sylve](https://github.com/AlchemillaHQ) FreeBSD clusters, Bhyve VMs, Jails, ZFS, networking, and backups from the terminal. I also sponsor [@AlchemillaHQ](https://github.com/AlchemillaHQ) because good FreeBSD virtualization tooling deserves our money.
- **[`sylve-ansible`](https://github.com/mhahl/sylve-ansible)**: Ansible modules and roles to automate Sylve so I don't even have to type the CLI commands. *(Note: this repo doesn't exist yet, which makes it the only project on my profile with zero bugs and 100% test coverage.)*
- **[`overstate`](https://github.com/mhahl/overstate) & [`overstate-cis`](https://github.com/mhahl/overstate-cis)**: A web UI in front of Salt for accepting keys, firing jobs, and applying CIS hardening baselines when you want a shiny button to click without hiding what Salt is doing underneath.
- **[`sigaint-au/corvus`](https://github.com/sigaint-au/corvus) & [`corvus-cli`](https://github.com/sigaint-au/corvus-cli)**: Self-hosted secrets management for engineering teams and Kubernetes clusters, complete with database-level RBAC and audit logging.
- **[`unix-baseline`](https://github.com/mhahl/unix-baseline) & [`suse-baseline-salt`](https://github.com/mhahl/suse-baseline-salt)**: The Ansible and Salt baselines that configure and harden my FreeBSD, OpenBSD, and Linux hosts.
- **[`freebsd-ipa-join`](https://github.com/mhahl/freebsd-ipa-join) & [`carbide`](https://github.com/mhahl/carbide)**: A wizard that enrolls FreeBSD machines into FreeIPA (SSSD, HBAC, sudo, keytabs) without ruining your weekend, plus an SSH honeypot fleet to watch bots try to log into the rest.

---

*This README is AI-generated, because I will write 2,000 lines of YAML to automate a server before I write a page about myself by hand. All hail the great AI.*
