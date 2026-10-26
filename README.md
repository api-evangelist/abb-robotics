# ABB Robotics (abb-robotics)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
