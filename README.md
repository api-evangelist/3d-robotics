# 3DR

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

3DR, Inc. designs and manufactures electronic systems for unmanned vehicles, drones and UAVs from
Chula Vista, California — Control N1 / Control Zero / Pixracer Pro autopilots, Location One and
ZED-F9P RTK GNSS receivers, SiK and Dualband Wi-Fi telemetry radios, DroneCAN power modules and
sensors, ESCs, and an ArduRemoteID-based Remote ID module — built around open-source and
open-hardware flight control (PX4, ArduPilot, DroneCAN, MAVLink).

**3DR publishes no public web API.** Every OpenAPI / Swagger / GraphQL / llms.txt / `.well-known`
path was probed on `www.3dr.com`, `docs.3dr.com`, `3dr.wiki`, `store.3dr.com` and `dronekit.io` on
2026-09-05; all returned 404. What this profile records instead is the real published surface: a
61-page hardware knowledge base, self-declared NDAA / FCC / Prop 65 / RoHS compliance notices, and
the DroneCAN and FAA Remote ID protocol conformance the documentation states.

**Two companies have traded as 3DR.** The company at 3dr.com states on its own site that "3DR Inc
was a distinct entity before the year 2023" and does not support products sold under the earlier
label. The pre-2023 3D Robotics, Inc. built Solo, Site Scan and the DroneKit developer program; its
web API at `api.3drobotics.com` is decommissioned (NXDOMAIN), its DroneKit SDKs were last released
2019-03-18, and `3drobotics.com` now redirects to an unrelated company. See
`lifecycle/3d-robotics-lifecycle.yml` and `packages/3d-robotics-packages.yml`.

- https://www.3dr.com/
- https://docs.3dr.com/
- https://forgeglobal.com/3d-robotics_stock/ (secondary-market listing this profile was harvested from)
