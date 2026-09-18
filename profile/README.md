# Vicenza Development Investment Joint Stock Company

Technology-driven solutions for modern industrial operations.

---

## About Us

Vicenza Development Investment Joint Stock Company specializes in industrial automation, software development, and hardware engineering. We design and deliver integrated solutions for production lines, real-time monitoring systems, and enterprise management platforms.

## Core Expertise

| Domain                | Capabilities                                                                                                         |
| --------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Industrial Automation | Firmware and hardware development for manufacturing machinery, including brick making machines and production lines. |
| Software Solutions    | Custom enterprise software: CRM systems, attendance tracking (`checkchamcong`), and internal evaluation tools.       |
| IoT and Monitoring    | Power and internet monitoring, server health tracking, and ESP-NOW communication protocols.                          |
| Infrastructure        | Scalable web applications and weighing bridge management systems.                                                    |

## Repository Naming Convention

Every repository is named after the project it belongs to, the part of the system it holds, and
who it is built for:

```
<project>-<component>-<client>
```

| Part        | Meaning                                                                                  | Examples                                                    |
| ----------- | ---------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| `project`   | The project the repository belongs to. Always first.                                     | `crm`, `erp`                                                |
| `component` | The system or component within the project.                                              | `website`, `api`, `client`, `firmware`, `hardware`, `data`  |
| `client`    | The customer or site the work is for. Always present; internal projects use `vicenza`.   | `vicenza`                                                   |

Putting the project first keeps every repository of a project together in any alphabetical list,
and one prefix finds them all:

```
crm-api-vicenza
crm-firmware-vicenza
crm-website-vicenza
```

Names use lowercase letters, digits and hyphens only, and never include a technology or version —
a project keeps its name when its stack changes. Some older repositories predate this convention
and are being renamed as they are reworked.

## Contact and Support

For professional inquiries or technical collaboration, please contact the Administrative Department through official corporate channels.

---

Copyright © 2026 Vicenza Development Investment Joint Stock Company. All rights reserved.
