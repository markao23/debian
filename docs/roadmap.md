# AsterOS Roadmap

This roadmap presents the main milestones for the project, from the base system foundation to enterprise-ready delivery.

```mermaid
gantt
    title AsterOS Product Roadmap
    dateFormat  YYYY-MM-DD
    axisFormat  %b %d

    section Foundation
    Debian base integration             :done, base, 2026-08-01, 30d
    Boot and init stabilization        :done, boot, 2026-09-01, 25d
    Kernel hardening                   :active, kernel, 2026-09-20, 35d

    section Security
    Signed repositories and package trust :repo, 2026-10-15, 30d
    Firewall and audit layer            :sec, 2026-11-15, 25d
    Secure boot and policy baseline     :secure, 2026-12-05, 30d

    section Platform
    Installer refinement                :install, 2026-12-20, 20d
    Package management automation       :pkg, 2027-01-10, 30d
    Monitoring and diagnostics          :diag, 2027-02-10, 25d

    section Enterprise
    Remote management tools             :remote, 2027-03-05, 30d
    Production readiness validation     :prod, 2027-04-05, 35d
    LTS release and support package     :lts, 2027-05-15, 20d
```

## Roadmap phases

### Phase 1: Foundation
- Stable Debian-compatible boot and init system
- Hardened kernel configuration
- Core documentation and architecture baseline

### Phase 2: Security and reliability
- Signed packages and controlled repositories
- Firewall, audit and access policy controls
- Secure update and recovery workflows

### Phase 3: Platform maturity
- Improved installer experience
- Packaging automation and lifecycle management
- Monitoring and operational observability

### Phase 4: Enterprise release
- Remote management tooling
- Production validation and support readiness
- Long-term support release

## Notes

This roadmap is intended to evolve with the project. It supports planning, execution tracking, and communication with stakeholders, clients, and technical teams.
