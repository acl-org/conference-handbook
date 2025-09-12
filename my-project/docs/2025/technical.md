
# Technical Open Review Chair Handbook

## [Current Chairs](https://2025.aclweb.org/organization/)

| Name         | Affiliation       | Contact              |
|--------------|-------------------|----------------------|
| Niket Tandon | Allen AI          | nikett@gmail.com     |
| Lizhen Qu    | Monash University | lizhen.qu@monash.edu |

---

## Overview of Responsibilities  
Technical Open Review Chairs (TORCs) are the interface between *CL organisers and the OpenReview/ARR technical ecosystem. TORCs are responsible for creating and managing new groups within a conference venue on OpenReview, ensuring individuals have the correct access and permissions. TORCs are most needed during the Rolling Review cycle. During the commitment site phase, regular meetings with the OpenReview team may not be necessary.

**The following are the main responsibilities of the Technical Open Review Chairs:**


**1. Commitment‑Site Setup & Maintenance** 
**2. Technical Support & Ticket Triage**  
**3. Proceedings Generation & Metadata Support**   
**4. Stakeholder Communication**  
**5. Documentation & Handover** 

General information from ACL Automatic Rolling Review is available [here](https://stats.aclrollingreview.org/).

---

## Breakdown of Responsibilities

### 1. Commitment‑Site Setup  
  TORCs begin by establishing working channels with the ARR technical co‑chairs and OpenReview developers, then submit the official request that spawns the ACL commitment venue.  Once the site is provisioned, they rigorously test group permissions with sandbox papers to ensure authors, reviewers, and program chairs have the correct access.  Recommended practice is to file the request at least three weeks before commitments open. 

| Task                                                             | Start      | Deadline   | Dependency | Notes                                                                                                                                                                                                                                                    |
|------------------------------------------------------------------|------------|------------|------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Contact ARR Co‑Chief Technical Officers & Previous Year's Chairs | ASAP       | Nov 2024   | –          | **(1)** Establish Slack/Email channel; **(2)** OpenReview can be contacted at *info@openreview.net*                                                                                                                                                      |
| Submit OpenReview Commitment‑site Request                        | March 2025 | March 2025 | Form ready | **(1)** Submit request ≥3 weeks before commitment date; **(2)** See advice on setting up Commitment Sites [here](https://docs.openreview.net/getting-started/hosting-a-venue-on-openreview/creating-your-venue-instance-submitting-a-venue-request-form) |
| Verify Venue Configuration & Group Permissions                   | March 2025 | April 2025 | Site live  | **(1)** The option "our venue does not have Ethics Chairs and Reviewers" should be selected as Ethics reviews take place during ARR, not at the commitment level; **(2)** Test with PC sandbox papers.                                                   |

---

### 2. Technical Support & Ticket Triage  
  Once ARR cycles start, TORCs own the Freshdesk help desk and mailing list, fielding technical queries from program chairs, area chairs, and authors.  Straightforward issues are resolved directly; complex bugs are escalated to OpenReview devs.  A concise fortnightly digest keeps PCs informed of outstanding tickets and fixes. 

| Task                                       | Start    | Deadline  | Dependency | Notes                                                                                                                            |
|--------------------------------------------|----------|-----------|------------|----------------------------------------------------------------------------------------------------------------------------------|
| Monitor Freshdesk Queue & Mailing List     | Ongoing  | July 2025 | –          | **(1)** Answer editors'/PCs' queries; **(2)** Escalate complex issues to OpenReview developers (e.g., Jonathan Kummerfeld/Vitor) |
| Produce Fortnightly Status Summary for PCs | Jan 2025 | July 2025 | –          | Include bug list & resolutions.                                                                                                  |
| Handle Program Chair Requests              | Ongoing  | July 2025 | -          | Python API to access information that helps PCs is available [here](https://acl-org.github.io/conference-handbook/tech/).        |
| Maintain FAQ                               | Ongoing  | July 2025 | -          | To avoid answering similar questions repeatedly, an FAQ platform should be set up and kept up to date.                           |
---

### 3. Proceedings Generation & Metadata Support  
  TORCs guide program chairs through ACLPUB and OpenReview APIs to generate camera‑ready proceedings.  Tasks include reconciling paper IDs, running format scripts, and preparing order files so the Anthology ingest proceeds smoothly. 

| Task                            | Start    | Deadline | Dependency  | Notes                                                                       |
|---------------------------------|----------|----------|-------------|-----------------------------------------------------------------------------|
| Assist PCs with ACLPUB Workflow | Feb 2025 | May 2025 | PC timeline | ACLPUB documentation is available [here](https://github.com/acl-org/ACLPUB) |
| Run Format Checks               | Feb 2025 | May 2025 | –           | Provide sample Python snippets                                              |

---

### 4. Stakeholder Communication  
Regular sync‑ups prevent surprises. TORCs schedule monthly calls with PCs and ARR editors, maintain a help‑desk for workshop organisers, and circulate change logs when OpenReview rolls out new features. During commitment stage, meetings can be skipped if there are no blocking issues. 

| Task                                         | Start    | Deadline  | Dependency         | Notes                        |
|----------------------------------------------|----------|-----------|--------------------|------------------------------|
| Schedule monthly sync with PCs & ARR editors | Dec 2024 | June 2025 | –                  | Cancel if no blocking items. |
| Provide Workshop‑Organiser Helpdesk          | Jan 2025 | Jun 2025  | Workshop approvals | Reduces load on core devs.   |

---

### 5. Documentation & Handover  
The final responsibility is knowledge capture. TORCs update the FAQ and tutorial hosted in the handbook repository, tidy scripts, and compile a lessons‑learned memo so that the next team can start from a clean, documented baseline.  This hand‑off package should be finished shortly after proceedings go to press. 

| Task                                | Start      | Deadline  | Dependency                 | Notes                                                                                                                |
|-------------------------------------|------------|-----------|----------------------------|----------------------------------------------------------------------------------------------------------------------|
| Update TORC FAQ & Tutorial (v2)     | April 2025 | June 2025 | -                          | There is an ongoing effort to develop tutorials to help TORCs - this should be kept up to date by the current chair. |
| Revise and share hand‑over document | June 2025  | July 2025 | Everything Else Completed. | Include lessons learned, scripts, contact lists                                                                      |

---


