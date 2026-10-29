# Oh, hi. I'm Mark.

I work at [Red Hat](https://github.com/RedHatOfficial) out of Canberra, Australia. My GitHub bio says I build Kubernetes clusters that nobody ever uses. Give me bare metal and an afternoon and I will stand up a hardened, automated OpenShift cluster for a workload that never shows up.

My day-to-day is **OpenShift**, **virtualization**, and **automation**. If a machine needs to boot, join a FreeIPA domain, mount storage, or pass a CIS audit, I write Ansible or Salt to do it while I go make a coffee. When I am not putting VMs inside containers with KubeVirt, I run Bhyve VMs, Jails, and ZFS on FreeBSD.

### What I'm Working On

- **[`sylve-cli`](https://github.com/mhahl/sylve-cli)**: A Python command-line client (`sylve(1)`) for managing [Sylve](https://github.com/AlchemillaHQ) FreeBSD clusters, Bhyve VMs, Jails, ZFS pools, networking, and backups. I also sponsor [@AlchemillaHQ](https://github.com/AlchemillaHQ) because good FreeBSD virtualization tooling deserves to exist.
- **[`sylve-ansible`](https://github.com/mhahl/sylve-ansible)**: Ansible modules and roles to automate Sylve so I don't even have to type the CLI commands. *(This repo doesn't exist yet, which makes it my most stable project to date.)*
- **[`overstate`](https://github.com/mhahl/overstate) & [`overstate-cis`](https://github.com/mhahl/overstate-cis)**: A web UI in front of Salt for accepting keys, firing jobs, and applying CIS baselines when you want a button to click without hiding what Salt is doing.
- **[`sigaint-au/corvus`](https://github.com/sigaint-au/corvus) & [`corvus-cli`](https://github.com/sigaint-au/corvus-cli)**: Self-hosted secrets management for engineering teams and Kubernetes clusters, with database-level RBAC and audit logging.
- **Infrastructure glue**: Ansible and Salt baselines for FreeBSD and Linux ([`unix-baseline`](https://github.com/mhahl/unix-baseline), [`suse-baseline-salt`](https://github.com/mhahl/suse-baseline-salt)), [`freebsd-ipa-join`](https://github.com/mhahl/freebsd-ipa-join) for enrolling FreeBSD hosts into FreeIPA without losing your weekend, and [`carbide`](https://github.com/mhahl/carbide) for running an SSH honeypot fleet.
