# Hi, I'm Jurre 👋

Cloud & DevOps consultant from Belgium, working mostly in **Azure**, **infrastructure as code** (Terraform, Bicep, Ansible) and **Kubernetes** with **GitOps** (Argo CD). Off the clock I run a homelab and fix the small things that annoy me: a Home Assistant add-on here, an e-reader patch there.

Most of what's public here is something I needed myself and finished properly enough to share.

## Things I've built

**Home & self-hosting**

- [fusionsolar-charger](https://github.com/jterpstra1/fusionsolar-charger) · Home Assistant add-on for Huawei SCharger wallboxes. Pulls live status and monthly kWh from the FusionSolar portal, handy for company-car charging reimbursement.
- [ebook-convert-sidecar](https://github.com/jterpstra1/ebook-convert-sidecar) · Container that converts the EPUBs in a library folder to AZW3 (or any format) with Calibre and keeps them in sync next to the original. Works with Grimmory and BookOrbit.
- [docker-s3sync](https://github.com/jterpstra1/docker-s3sync) · Small container that backs up folders to S3 on a cron schedule with `aws s3 sync`.
- [unraid-templates](https://github.com/jterpstra1/unraid-templates) · Unraid Community Applications templates for the containers above and a few more.

**E-readers**

- [koreader-pocketbook-wifi-fix](https://github.com/jterpstra1/koreader-pocketbook-wifi-fix) · KOReader user patch for PocketBook so that "Wi-Fi off" actually powers the radio down, instead of draining the battery overnight.
- [koreader-simpleui-bento](https://github.com/jterpstra1/koreader-simpleui-bento) · Per-module Bento Grid widths for the SimpleUI home screen, re-targeted at SimpleUI 2.5.

**Kubernetes**

- [k3s-ha-setup](https://github.com/jterpstra1/k3s-ha-setup) · Highly available k3s cluster on Proxmox: three control-plane nodes, workers and load balancers on one old PC.

**Cloud & automation**

- [awx-ee](https://github.com/jterpstra1/awx-ee) · Ansible AWX execution environment image with the AWS CLI and SSM tooling baked in, published from GitHub Actions.

## Elsewhere

- 📍 Heppen, Belgium
- 📫 info@terpstra.tech
