# ABB Robotics (abb-robotics)

ABB Robotics is the robotics and discrete-automation business of ABB Ltd, the Swiss-Swedish multinational headquartered in Zurich, Switzerland. Formed in 1988 from the merger of ASEA (Sweden) and Brown, Boveri & Cie (Switzerland) — and the heir to ASEA's IRB 6, considered the first microprocessor-controlled industrial robot (1974) — ABB Robotics manufactures industrial robots, collaborative robots (GoFa, SWIFTI, YuMi), delta robots (IRB 360 FlexPicker), painting and welding robots, and autonomous mobile robots, paired with the OmniCore controller family running RobotWare 7 and the RAPID programming language. The developer surface is anchored by Robot Web Services (RWS), the PC SDK (.NET), and the RobotStudio SDK (.NET 10 / RobotStudio 2026).

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/abb-robotics/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Robotics, Industrial Robotics, Industrial Automation, Manufacturing, Robot Controllers, OmniCore, RobotStudio, RAPID, Collaborative Robots, Cobots, Welding, Painting, Material Handling, Picking and Packing, Discrete Automation, Robot Web Services, REST, WebSockets

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### ABB Robot Web Services (RWS)
The canonical REST/HTTP(S) API exposed by ABB OmniCore (RobotWare 7) and IRC5 controllers. Provides programmatic access to RAPID program data and execution, IO signals, motion system, file service, e-log, configuration (CFG), controller (clock, restart, identification), user authorization, and subscriptions over WebSockets. Supports XML (default) and JSON (HAL) representations via `json=1`. Digest authentication.

- [Documentation — RWS Introduction](https://developercenter.robotstudio.com/api/rwsApi/)
- [Documentation — RWS Reference](https://developercenter.robotstudio.com/api/RWS)
- [Community SDK — abb_librws (C++)](https://github.com/ros-industrial/abb_librws)
- [Community SDK — abb_robot_client (Python)](https://abb-robot-client.readthedocs.io/en/stable/abb_robot_client/api/rws.html)

### ABB Robot Web Services Subscriptions
WebSocket subscription service that pushes change events for subscribed RWS resources (IO signals, RAPID symbols, controller state, execution state, e-log, motion system).

- [Documentation](https://developercenter.robotstudio.com/api/rwsApi/)

### ABB PC SDK
.NET SDK for building custom PC applications and RobotStudio Add-Ins that communicate with the controller over a network. Domains include Controller, RapidDomain, IOSystemDomain, MotionDomain, EventLogDomain, FileSystemDomain, ConfigurationDomain, and UserAuthorizationManagement.

- [Documentation](https://developercenter.robotstudio.com/api/pcsdk/)
- [API Reference](https://developercenter.robotstudio.com/api/pcsdk/api/index.html)
- [Application Manual (PDF)](https://library.e.abb.com/public/124d6b59313ed85fc125793400410c5b/3HAC036957-en.pdf)

### ABB RobotStudio SDK
.NET 10 SDK targeting RobotStudio 2026 for building custom Add-Ins and SmartComponents that extend the RobotStudio simulation and offline programming environment.

- [Documentation](https://developercenter.robotstudio.com/api/robotstudio/index.html)

## Common Properties

- [Website — ABB Group](https://global.abb/group/en/)
- [Portal — ABB Robotics](https://new.abb.com/products/robotics)
- [Portal — ABB Developer Center](https://developercenter.robotstudio.com/)
- [Forum — RobotStudio User Forums](https://forums.robotstudio.com/)
- [Forum — ABB Robotics Community](https://tech-community.robotics.abb.com/)
- [Product — OmniCore Controllers](https://new.abb.com/products/robotics/controllers/omnicore)
- [Product — RobotStudio Suite](https://new.abb.com/products/robotics/software-and-digital/robotstudio)
- [Product — RobotStudio Cloud](https://new.abb.com/products/robotics/software-and-digital/robotstudio/robotstudio-cloud)
- [Product — Industrial Robots](https://new.abb.com/products/robotics/industrial-robots)
- [Product — Collaborative Robots](https://new.abb.com/products/robotics/collaborative-robots)
- [Product — Autonomous Mobile Robots](https://new.abb.com/products/robotics/autonomous-mobile-robots)
- [Downloads](https://www.abb.com/global/en/areas/robotics/downloads)
- [GitHub Organization](https://github.com/ABB-Robotics)
- [SDK — PC SDK](https://developercenter.robotstudio.com/api/pcsdk/)
- [SDK — RobotStudio SDK](https://developercenter.robotstudio.com/api/robotstudio/index.html)
- [SDK — abb_librws (ROS-Industrial)](https://github.com/ros-industrial/abb_librws)
- [SDK — abb_libegm (ROS-Industrial)](https://github.com/ros-industrial/abb_libegm)
- [SDK — abb_robot_client (Python)](https://abb-robot-client.readthedocs.io/)
- [SDK — A3br (PLC RWS library)](https://github.com/loupeteam/A3br)
- [Documentation — OmniCore Application Manual](https://search.abb.com/library/Download.aspx?DocumentID=3HAC066554-001&LanguageCode=en&DocumentPartId=&Action=Launch)
- [Documentation — OmniCore Robot User Documentation](https://search.abb.com/library/Download.aspx?DocumentID=3HAC065042-001&LanguageCode=en&DocumentPartId=&Action=Launch)
- [Newsroom](https://global.abb/group/en/media)
- [PressReleases](https://global.abb/group/en/media/press-releases)
- [Careers](https://global.abb/group/en/careers)
- [Investors](https://global.abb/group/en/investors)
- [AnnualReport](https://global.abb/group/en/investors/financial-information/annual-reports)
- [Sustainability](https://global.abb/group/en/sustainability)
- [TermsOfService](https://global.abb/group/en/legal/general-terms-of-use)
- [PrivacyPolicy](https://global.abb/group/en/legal/privacy-notice)
- [LinkedIn](https://www.linkedin.com/showcase/abb-robotics/)
- [Twitter](https://twitter.com/ABBRobotics)
- [YouTube](https://www.youtube.com/@ABBRobotics)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
