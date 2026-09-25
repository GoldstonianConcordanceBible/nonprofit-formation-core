THE TABERNACLE, INC.

GITHUB OPERATING SYSTEM

Document ID: CTRL-GIT-001
Version: 0.1
Status: DRAFT
Owner: Secretary / Technology Administrator
Approving Authority: Board of Directors
Classification: Governance / Document Control / Technology

⸻

ARTICLE I — PURPOSE

GitHub shall serve as The Tabernacle’s controlled repository for:

* Governance documents
* Policies
* Program charters
* Standard operating procedures
* Templates
* Property-control documents
* Education curriculum
* Non-confidential compliance records
* Change history
* Version history
* Board-approved document versions

GitHub provides provenance.

It does not itself create legal authority.

⸻

ARTICLE II — CORE CONTROL RULE

GITHUB = CONTROLLED DOCUMENTS

DISCORD = DAILY OPERATIONS

ACCOUNTING SYSTEM = FINANCIAL RECORD

SECURE SYSTEM = CONFIDENTIAL INFORMATION

BOARD RECORD = CORPORATE AUTHORITY

⸻

ARTICLE III — REPOSITORY NAME

Recommended private repository:

the-tabernacle-governance

Repository description:

Governance, formation, program controls, compliance, property, and operating documentation for The Tabernacle, Inc.

Initial visibility:

PRIVATE

Do not make the repository public during formation merely for transparency.

Public disclosure shall be deliberate.

⸻

ARTICLE IV — EXISTING CHURCH SOFTWARE

The existing:

Church-enterprise-erp

repository may be treated as technology infrastructure.

It shall remain separate from The Tabernacle’s corporate governance repository.

CONTROL RULE

SOFTWARE PROJECT ≠ LEGAL ENTITY

ERP ≠ CORPORATE RECORD BOOK

The Tabernacle may later adopt, license, configure, or use that software without merging the two repositories.

⸻

ARTICLE V — MASTER REPOSITORY STRUCTURE

Use:

the-tabernacle-governance/
│
├── README.md
│
├── CHANGELOG.md
│
├── .gitignore
│
├── .github/
│
├── 00_CONTROL/
├── 01_FORMATION/
├── 02_GOVERNANCE/
├── 03_501C3/
├── 04_PROGRAMS/
├── 05_OPERATIONS/
├── 06_RISK_COMPLIANCE/
├── 07_DISCORD/
├── 08_BOARD/
├── 09_PROPERTY/
├── 10_EDUCATION/
├── 11_PRISON_REENTRY/
├── 12_FINANCE/
├── 13_FUNDRAISING/
├── 14_HUMAN_RESOURCES/
├── 15_TECHNOLOGY/
├── 16_TEMPLATES/
└── 99_ARCHIVE/

⸻

ARTICLE VI — 00_CONTROL

Contains:

DOCUMENT_CONTROL.md
MASTER_DOCUMENT_REGISTER.md
GITHUB_OPERATING_SYSTEM.md
AUTHORITY_MATRIX.md
CHANGE_CONTROL.md
CONTROLLED_TERMS.md

This directory defines how all other documents are controlled.

⸻

ARTICLE VII — 01_FORMATION

Contains:

ARTICLES_OF_INCORPORATION.md
INITIAL_ACTION_OF_INCORPORATOR.md
FORMATION_CHECKLIST.md
REGISTERED_AGENT.md
EIN_CHECKLIST.md
STATE_FILINGS/

Do not place confidential EIN confirmation letters in a public repository.

⸻

ARTICLE VIII — 02_GOVERNANCE

Contains:

BYLAWS.md
CONFLICT_OF_INTEREST_POLICY.md
ANNUAL_CONFLICT_DISCLOSURE_TEMPLATE.md
COMPENSATION_POLICY.md
FINANCIAL_CONTROLS_POLICY.md
WHISTLEBLOWER_POLICY.md
DOCUMENT_RETENTION_POLICY.md
CODE_OF_CONDUCT.md

Signed individual conflict disclosures should be kept in restricted storage rather than the ordinary public document tree.

⸻

ARTICLE IX — 03_501C3

Contains:

FORM_1023_NARRATIVE.md
FORM_1023_FILING_CHECKLIST.md
THREE_YEAR_PROJECTED_BUDGET_TEMPLATE.md
FORM_1023_DISCLOSURE_WORKSHEET.md
PUBLIC_CHARITY_ANALYSIS.md
IRS_CORRESPONDENCE_INDEX.md

Do not publish:

* EIN
* Donor identities
* Personal compensation worksheets
* Sensitive related-party documentation
* Unredacted IRS correspondence containing protected data

⸻

ARTICLE X — 04_PROGRAMS

Contains master program governance.

Example:

MASTER_PROGRAM_CONSTITUTION.md
MASTER_PROGRAM_REGISTER.md
MIN-001/
HHS-001/
EDU-001/
REENTRY-001/

Each program should contain:

CHARTER.md
SOP.md
BUDGET_TEMPLATE.md
METRICS.md
RISK_REGISTER.md
TRAINING.md
PARTNERS.md
CHANGELOG.md

Sensitive participant information shall never be stored here.

⸻

ARTICLE XI — 05_OPERATIONS

Contains organization-wide operating procedures.

Examples:

24_7_OPERATIONS.md
SHIFT_HANDOFF.md
FACILITY_OPENING.md
FACILITY_CLOSING.md
EMERGENCY_ESCALATION.md
VOLUNTEER_OPERATIONS.md
VENDOR_OPERATIONS.md

Site-specific operational material may live under the applicable property folder.

⸻

ARTICLE XII — 06_RISK_COMPLIANCE

Contains:

SAFEGUARDING_POLICY.md
BACKGROUND_SCREENING_POLICY.md
INCIDENT_MANAGEMENT_POLICY.md
PRIVACY_POLICY.md
DATA_CLASSIFICATION_POLICY.md
SECURITY_POLICY.md
INSURANCE_REGISTER_TEMPLATE.md
RISK_REGISTER.md

Do not store individual incident reports or full background reports here.

⸻

ARTICLE XIII — 07_DISCORD

Contains:

DISCORD_OPERATING_SYSTEM.md
ROLE_MATRIX.md
CHANNEL_REGISTER.md
SHIFT_HANDOFF_TEMPLATE.md
OFFBOARDING_CHECKLIST.md

⸻

ARTICLE XIV — 08_BOARD

Contains non-confidential corporate governance templates and approved records.

Example:

INITIAL_BOARD_MEETING_AGENDA.md
INITIAL_BOARD_RESOLUTIONS.md
BOARD_MEETING_TEMPLATE.md
BOARD_RESOLUTION_TEMPLATE.md
BOARD_CALENDAR.md
BOARD_REGISTER.md

Signed minutes may be stored in a restricted governance repository or corporate-record system if the main repository is ever made public.

⸻

ARTICLE XV — 09_PROPERTY

Master controls:

PROPERTY_ACQUISITION_GATE.md
PROPERTY_REGISTER.md
SITE_ACTIVATION_GATE.md
PROPERTY_SCORECARD.md

Then:

TAB-PROP-001/
TAB-PROP-002/

After acquisition:

TAB-001/
TAB-002/

⸻

ARTICLE XVI — PROPERTY SUBFOLDER STRUCTURE

Use:

TAB-PROP-001/
├── PROPERTY_PROFILE.md
├── 01_OFFER_CONTRACT/
├── 02_TITLE/
├── 03_SURVEY/
├── 04_ZONING_USE/
├── 05_ENVIRONMENTAL/
├── 06_INSPECTIONS/
├── 07_FIRE_LIFE_SAFETY/
├── 08_ACCESSIBILITY/
├── 09_INSURANCE/
├── 10_FINANCING/
├── 11_RENOVATION/
├── 12_BUDGET/
├── 13_BOARD/
├── 14_CLOSING/
├── 15_SITE_ACTIVATION/
└── CHANGELOG.md

Large or sensitive attachments may be referenced rather than committed directly.

⸻

ARTICLE XVII — 10_EDUCATION

Contains:

EDU-001/
COURSE_REGISTER.md
CONTENT_RIGHTS_REGISTER_TEMPLATE.md
INSTRUCTOR_AGREEMENT_TEMPLATE.md
CERTIFICATE_POLICY.md

Course structure:

EDU-AI-101/
├── COURSE_CHARTER.md
├── CURRICULUM.md
├── LESSONS/
├── ASSESSMENTS/
├── RESOURCES/
├── RIGHTS.md
└── CHANGELOG.md

Do not store learner grades or personal student records in the repository.

⸻

ARTICLE XVIII — 11_PRISON_REENTRY

Contains:

REENTRY-001/
FACILITY_REGISTER_TEMPLATE.md
VOLUNTEER_TRAINING.md
MENTORING_POLICY.md
REENTRY_RESOURCE_DIRECTORY.md

Facility-specific public-safe files may use:

FACILITY-001/
├── PROGRAM_SUMMARY.md
├── CURRICULUM/
├── APPROVAL_STATUS.md
└── CHANGELOG.md

Do not commit:

* Inmate numbers
* Participant names
* Criminal histories
* Confidential facility-security details
* Private correspondence
* Detailed release plans

⸻

ARTICLE XIX — 12_FINANCE

GitHub shall contain policies and templates only.

Examples:

CHART_OF_ACCOUNTS.md
BUDGET_TEMPLATE.md
PURCHASE_APPROVAL_POLICY.md
EXPENSE_REIMBURSEMENT_POLICY.md
RESTRICTED_FUNDS_POLICY.md
MONTH_END_CHECKLIST.md

The actual ledger belongs in the accounting system.

CONTROL RULE

GITHUB ≠ GENERAL LEDGER

⸻

ARTICLE XX — 13_FUNDRAISING

Contains:

FUNDRAISING_POLICY.md
GIFT_ACCEPTANCE_POLICY.md
DONOR_RESTRICTION_POLICY.md
GRANT_REGISTER_TEMPLATE.md
CAMPAIGN_TEMPLATE.md

Do not commit donor lists containing confidential personal or financial information.

⸻

ARTICLE XXI — 14_HUMAN_RESOURCES

GitHub may contain:

EMPLOYEE_HANDBOOK.md
JOB_DESCRIPTION_TEMPLATES/
VOLUNTEER_HANDBOOK.md
ONBOARDING_CHECKLIST.md
OFFBOARDING_CHECKLIST.md

Do not commit:

* SSNs
* I-9s
* W-4s
* Direct deposit data
* Medical records
* Individual disciplinary files
* Background reports

⸻

ARTICLE XXII — 15_TECHNOLOGY

Contains:

SYSTEM_REGISTER.md
ACCESS_CONTROL_POLICY.md
BACKUP_POLICY.md
CYBERSECURITY_POLICY.md
DATA_CLASSIFICATION.md
VENDOR_TECHNOLOGY_REGISTER.md

Never commit:

* Passwords
* API keys
* Tokens
* Recovery codes
* Private certificates
* Banking credentials

⸻

ARTICLE XXIII — 16_TEMPLATES

Create reusable templates:

POLICY_TEMPLATE.md
PROGRAM_CHARTER_TEMPLATE.md
SOP_TEMPLATE.md
BOARD_RESOLUTION_TEMPLATE.md
MEETING_MINUTES_TEMPLATE.md
PROPERTY_PROFILE_TEMPLATE.md
RISK_REGISTER_TEMPLATE.md
INCIDENT_REFERENCE_TEMPLATE.md
MOU_TEMPLATE.md
VENDOR_REVIEW_TEMPLATE.md

⸻

ARTICLE XXIV — 99_ARCHIVE

Superseded material moves here when retention is necessary.

Never silently overwrite organizational history.

Each archived document should identify:

* Previous version
* Replacement
* Retirement date
* Reason

⸻

ARTICLE XXV — BRANCH MODEL

Use a simple model.

main

Controlled current documents.

Only reviewed material should enter main.

draft

Working documents that have not yet been formally approved.

Optional feature branches may be used for major changes.

Examples:

policy/safeguarding-v1
program/hhs-001
property/tab-prop-001
formation/articles

⸻

ARTICLE XXVI — MAIN BRANCH PROTECTION

Configure main so that, where practical:

* Direct pushes are restricted
* Pull requests are required
* Review is required before merge
* Force pushes are disabled
* Deletion is restricted

Technical administrators shall not bypass governance simply because they possess platform privileges.

⸻

ARTICLE XXVII — DOCUMENT WORKFLOW

Every controlled document moves:

IDEA

↓

DRAFT

↓

REVIEW

↓

APPROVAL

↓

MERGE

↓

VERSION

↓

EFFECTIVE

↓

REVIEW

↓

SUPERSEDE / RETIRE

⸻

ARTICLE XXVIII — DRAFT DOCUMENT HEADER

Every controlled document shall begin with:

Document ID:
Version:
Status:
Owner:
Approving Authority:
Approval Date:
Effective Date:
Next Review Date:
Supersedes:
Classification:

⸻

ARTICLE XXIX — DOCUMENT STATUS

Use only:

DRAFT

REVIEW

BOARD APPROVED

FILED

EFFECTIVE

SUPERSEDED

SUSPENDED

RETIRED

Do not label a draft policy “effective.”

⸻

ARTICLE XXX — DOCUMENT IDENTIFIERS

Maintain stable IDs.

Examples:

CTRL-001
GOV-001
GOV-002
FIN-001
SG-001
PROP-001
MIN-001
HHS-001
EDU-001
REENTRY-001
BRD-001
TAX-001

The ID should remain stable even if the file name later changes.

⸻

ARTICLE XXXI — VERSIONING

Use:

Drafts

0.1

0.2

0.3

First Adopted Version

1.0

Minor Revision

1.1

1.2

Major Revision

2.0

Major revisions include substantial changes to:

* Authority
* Rights
* Responsibilities
* Risk controls
* Program scope
* Legal structure

⸻

ARTICLE XXXII — COMMIT MESSAGES

Use clear messages.

Examples:

draft: add safeguarding policy
review: revise compensation controls
approve: adopt GOV-002 v1.0
property: add TAB-PROP-001 screening
education: add EDU-AI-101 curriculum
fix: correct cross-reference in PROP-001
archive: supersede GOV-003 v1.0

Avoid messages such as:

stuff
update
final final
changes

⸻

ARTICLE XXXIII — PULL REQUEST STANDARD

Each material pull request should state:

DOCUMENT / PROGRAM:
CHANGE:
WHY:
RISK IMPACT:
FINANCIAL IMPACT:
LEGAL REVIEW REQUIRED:
YES / NO
BOARD APPROVAL REQUIRED:
YES / NO
SUPERSEDES:
RELATED ISSUE:
APPROVAL EVIDENCE:

⸻

ARTICLE XXXIV — BOARD APPROVAL

A GitHub pull-request approval is a technical/document review.

It does not automatically constitute formal Board action.

Where Board approval is required:

1. Draft in GitHub.
2. Review.
3. Board formally acts.
4. Minutes/resolution record approval.
5. Update document status.
6. Merge approved version.
7. Tag version.

CONTROL RULE

PR APPROVAL ≠ BOARD APPROVAL

⸻

ARTICLE XXXV — BOARD APPROVAL EVIDENCE

An adopted document should identify:

Board Approval Date:
Resolution Number:
Meeting/Consent Reference:
Effective Date:

Example:

Board Approval Date: 2026-10-15
Resolution Number: BR-2026-014
Effective Date: 2026-10-15

⸻

ARTICLE XXXVI — TAGGING

Use Git tags for significant governance milestones.

Examples:

FORMATION-V1.0
BYLAWS-V1.0
GOVERNANCE-V1.0
SAFEGUARDING-V1.0
501C3-FILED
501C3-DETERMINATION
TAB-001-ACQUIRED
TAB-001-ACTIVATED
HHS-001-PILOT
HHS-001-V1.0
EDU-001-V1.0
REENTRY-001-V1.0

⸻

ARTICLE XXXVII — RELEASES

A GitHub release may package major milestones.

Examples:

Governance Release 1.0

Contains:

* Articles
* Bylaws
* Conflict Policy
* Compensation Policy
* Financial Controls
* Whistleblower Policy
* Document Retention
* Safeguarding

Site Launch Release — TAB-001

Contains public-safe:

* Site charter
* Approved program list
* Operating-status record
* Public policies

⸻

ARTICLE XXXVIII — ISSUES

Use GitHub Issues for trackable work.

Recommended labels:

formation
governance
501c3
board
property
ministry
food
education
reentry
safeguarding
finance
legal-review
board-approval
blocked
high-risk
urgent
documentation

⸻

ARTICLE XXXIX — ISSUE TEMPLATE — POLICY

Create:

.github/ISSUE_TEMPLATE/policy.md

Template:

# Policy Request
Policy:
Document ID:
Problem Being Solved:
Owner:
Legal Review Needed:
YES / NO
Board Approval Needed:
YES / NO
Target Date:
Dependencies:
Notes:

⸻

ARTICLE XL — ISSUE TEMPLATE — PROPERTY

Create:

.github/ISSUE_TEMPLATE/property.md

Template:

# Property Candidate
Property ID:
Address:
Seller:
Asking Price:
Current Use:
Proposed Tabernacle Uses:
Zoning Status:
Inspection Status:
Environmental Status:
Insurance Status:
Estimated Renovation:
Major Risks:
Current Gate:
LEAD / SCREENING / DUE DILIGENCE / NEGOTIATION / BOARD REVIEW
Next Action:
Owner:

⸻

ARTICLE XLI — ISSUE TEMPLATE — PROGRAM

Create:

.github/ISSUE_TEMPLATE/program.md

Template:

# Program Proposal
Program ID:
Program Name:
Division:
Charitable / Religious / Educational Purpose:
Population Served:
Program Owner:
Projected Budget:
Funding Source:
Facility Needed:
Licenses / Approvals:
Safeguarding Requirements:
Proposed Pilot:
Board Approval Required:
YES / NO
Status:
CONCEPT

⸻

ARTICLE XLII — ISSUE TEMPLATE — RISK

Create:

.github/ISSUE_TEMPLATE/risk.md

Template:

# Risk Record
Risk ID:
Area:
Description:
Likelihood:
Impact:
Existing Controls:
Additional Action:
Owner:
Due Date:
Status:
Escalation Required:
YES / NO

Do not put sensitive incident facts into a public or broadly accessible risk issue.

⸻

ARTICLE XLIII — PULL REQUEST TEMPLATE

Create:

.github/PULL_REQUEST_TEMPLATE.md

# THE TABERNACLE — CHANGE REVIEW
## What changed?
## Why?
## Document IDs affected
## Legal/compliance impact
## Financial impact
## Safeguarding impact
## Property impact
## Program impact
## Board approval required?
- [ ] Yes
- [ ] No
## Board approval received?
- [ ] Yes
- [ ] No
- [ ] Not applicable
Resolution/reference:
## Checklist
- [ ] Document header updated
- [ ] Version updated
- [ ] Cross-references checked
- [ ] Master register updated
- [ ] No confidential information included
- [ ] Required reviewers completed

⸻

ARTICLE XLIV — CODEOWNERS

Where supported, establish review ownership.

Example concept:

/02_GOVERNANCE/      Secretary + Board reviewer
/03_501C3/           Treasurer + Secretary
/06_RISK_COMPLIANCE/ Safeguarding Officer + Board reviewer
/09_PROPERTY/        Property Director + Treasurer
/10_EDUCATION/       Education Director
/11_PRISON_REENTRY/  Reentry Director
/12_FINANCE/         Treasurer

A technical CODEOWNER review is not a substitute for corporate approval.

⸻

ARTICLE XLV — MASTER DOCUMENT REGISTER

00_CONTROL/MASTER_DOCUMENT_REGISTER.md

shall track:

ID	Document	Version	Status	Owner	Approval Date	Next Review
CTRL-001	Document Control	1.0	Effective	Secretary	TBD	TBD
GOV-001	Bylaws	1.0	Board Approved	Board	TBD	TBD
SG-001	Safeguarding	1.0	Board Approved	Safeguarding	TBD	TBD

This register is the index of controlled governance documents.

⸻

ARTICLE XLVI — MASTER PROGRAM REGISTER

Maintain:

04_PROGRAMS/MASTER_PROGRAM_REGISTER.md

Example:

ID	Program	Division	Status	Owner
MIN-001	24/7 Christian Ministry	Ministry	Design	TBD
HHS-001	Meal & Homelessness Relief	Relief	Design	TBD
EDU-001	Education	Education	Design	TBD
REENTRY-001	Prison & Reentry	Reentry	Design	TBD

⸻

ARTICLE XLVII — PROPERTY REGISTER

Maintain:

09_PROPERTY/PROPERTY_REGISTER.md

Example:

ID	Property	Status	Intended Use	Lead
TAB-PROP-001	TBD	Lead	TBD	TBD

Do not create a property ID merely for every internet listing viewed.

Create it when a site becomes a meaningful candidate.

⸻

ARTICLE XLVIII — CONFIDENTIAL INFORMATION CLASSIFICATION

Use four levels:

PUBLIC

Safe for unrestricted publication.

Examples:

* Mission
* Public policies
* Public program descriptions

INTERNAL

Ordinary operational information.

Examples:

* Draft procedures
* Internal project planning

CONFIDENTIAL

Limited access.

Examples:

* Compensation analysis
* Non-public contracts
* Sensitive Board discussions
* Donor information

RESTRICTED

Highest control.

Examples:

* SSNs
* Banking credentials
* Medical data
* Child abuse reports
* Background checks
* Inmate personal information
* Security vulnerabilities
* Passwords/API secrets

⸻

ARTICLE XLIX — WHAT MAY GO IN THE PRIVATE REPOSITORY

A private GitHub repository may contain appropriately controlled:

* Draft policies
* Program charters
* SOPs
* Board-resolution templates
* Property research
* Curriculum
* Risk registers without sensitive case data
* Contract templates
* Public-safe compliance documentation

Privacy classification still applies even when the repository is private.

⸻

ARTICLE L — WHAT SHALL NOT BE STORED IN ORDINARY GITHUB

Do not commit:

* Social Security numbers
* Passwords
* API keys
* Bank credentials
* Credit-card numbers
* Individual donor payment information
* Full background reports
* Medical records
* Individual case-management records
* Child protection reports
* Detailed abuse allegations
* Inmate identifiers
* Detailed facility-security vulnerabilities
* Personnel medical files

⸻

ARTICLE LI — SECRETS

No credential shall ever be committed intentionally.

Use secure credential-management systems for:

* Passwords
* API credentials
* Database credentials
* Tokens
* Encryption keys
* Recovery codes

If a secret is accidentally committed:

REVOKE / ROTATE FIRST

↓

REMOVE EXPOSURE

↓

INVESTIGATE

↓

DOCUMENT

Simply deleting the latest commit may not remove a secret from repository history.

⸻

ARTICLE LII — LARGE DOCUMENTS

Large signed PDFs, scans, surveys, architectural files, environmental reports, and inspection reports may be maintained in an approved document-storage system with a reference entry in GitHub.

Example:

Document:
Phase I Environmental Assessment
Property:
TAB-PROP-001
Date:
2026-10-20
Storage Location:
Restricted Property Records
Status:
Reviewed
Summary:
See PROP-001 decision package

⸻

ARTICLE LIII — LEGAL DOCUMENTS

GitHub may contain working and controlled copies.

The official executed document shall be preserved according to the corporate-record retention system.

MARKDOWN COPY ≠ ORIGINAL SIGNED INSTRUMENT

⸻

ARTICLE LIV — SCANNED SIGNATURES

Do not casually publish signatures.

Public versions may replace signatures with:

[Signed original retained in corporate records]

where appropriate.

⸻

ARTICLE LV — PUBLIC REPOSITORY STRATEGY

If The Tabernacle later wants transparency, create a separate public repository rather than automatically exposing the private governance repository.

Possible name:

the-tabernacle-public

Potential public materials:

* Mission
* Public bylaws where appropriate
* Public policies
* Program descriptions
* Annual reports
* Impact reports
* Public education material
* Public property histories

⸻

ARTICLE LVI — PUBLIC REPOSITORY EXCLUSIONS

Never publish merely for transparency:

* Confidential Board discussions
* Detailed security plans
* Participant records
* Personnel files
* Background checks
* Donor financial information
* Non-public legal advice
* Private contracts
* Credentials

TRANSPARENCY ≠ DISCLOSURE OF EVERYTHING

⸻

ARTICLE LVII — GITHUB PROJECT BOARD

Create a project board with:

BACKLOG

DESIGN

REVIEW

BOARD APPROVAL

READY

ACTIVE

BLOCKED

DONE

Major formation items should each have an issue.

⸻

ARTICLE LVIII — INITIAL GITHUB ISSUES

Create these first:

#1 Confirm state of incorporation
#2 Confirm The Tabernacle, Inc. name availability
#3 Finalize Articles of Incorporation
#4 Select initial Board
#5 Adopt Bylaws
#6 Adopt Conflict of Interest Policy
#7 Adopt Compensation Policy
#8 Adopt Financial Controls Policy
#9 Complete Whistleblower Policy
#10 Complete Document Retention Policy
#11 Adopt Safeguarding Policy
#12 Obtain EIN
#13 Open bank account
#14 Complete Form 1023 narrative
#15 Build three-year financial projections
#16 Prepare Form 1023
#17 Create Discord operations server
#18 Establish accounting platform
#19 Build HHS-001 pilot
#20 Build EDU-001 pilot
#21 Begin correctional partnership outreach
#22 Establish first property search criteria

⸻

ARTICLE LIX — DAY-ZERO COMMITS

The initial repository should begin with:

README.md
00_CONTROL/DOCUMENT_CONTROL.md
00_CONTROL/MASTER_DOCUMENT_REGISTER.md
00_CONTROL/GITHUB_OPERATING_SYSTEM.md
01_FORMATION/ARTICLES_OF_INCORPORATION.md
01_FORMATION/INITIAL_ACTION_OF_INCORPORATOR.md
01_FORMATION/FORMATION_CHECKLIST.md
02_GOVERNANCE/BYLAWS.md
02_GOVERNANCE/CONFLICT_OF_INTEREST_POLICY.md
02_GOVERNANCE/COMPENSATION_POLICY.md
02_GOVERNANCE/FINANCIAL_CONTROLS_POLICY.md
03_501C3/FORM_1023_NARRATIVE.md
03_501C3/FORM_1023_FILING_CHECKLIST.md
04_PROGRAMS/MASTER_PROGRAM_CONSTITUTION.md
04_PROGRAMS/MASTER_PROGRAM_REGISTER.md
06_RISK_COMPLIANCE/SAFEGUARDING_POLICY.md
07_DISCORD/DISCORD_OPERATING_SYSTEM.md
08_BOARD/INITIAL_BOARD_MEETING_AGENDA.md
08_BOARD/INITIAL_BOARD_RESOLUTIONS.md
09_PROPERTY/PROPERTY_ACQUISITION_GATE.md
10_EDUCATION/EDU-001_EDUCATION_PROGRAM_CHARTER.md
11_PRISON_REENTRY/REENTRY-001_PRISON_JAIL_REENTRY_PROGRAM_CHARTER.md

⸻

ARTICLE LX — FIRST RELEASE

After the Board formally adopts the foundational governance package, create:

GOVERNANCE-V1.0

Do not tag this until the actual Board action has occurred.

⸻

ARTICLE LXI — BACKUP

GitHub shall not be the sole copy of irreplaceable corporate records.

Maintain appropriate backups of:

* Governance documents
* Executed agreements
* Board records
* Formation records
* IRS records
* Property documents

⸻

ARTICLE LXII — ACCESS CONTROL

Recommended initial access:

Repository Administrators

Maximum practical minimum.

Board

Read access to controlled governance; editing as necessary according to responsibility.

Secretary

Governance administration.

Executive Director

Operational document access.

Program Directors

Access to relevant program directories.

Volunteers

No general repository access unless needed.

⸻

ARTICLE LXIII — OFFBOARDING

When repository access is no longer required:

1. Remove organization membership.
2. Remove team access.
3. Revoke credentials.
4. Transfer open issues.
5. Transfer document ownership.
6. Review outstanding branches.
7. Preserve institutional records.

⸻

ARTICLE LXIV — CHANGELOG

Maintain root:

CHANGELOG.md

Example:

# CHANGELOG
## 2026-10-15
- Adopted Bylaws v1.0
- Adopted GOV-002 v1.0
- Adopted SG-001 v1.0
## 2026-10-10
- Added PROP-001 draft
## 2026-10-01
- Repository initialized

⸻

ARTICLE LXV — PROVENANCE

GitHub history supports documentation of:

WHO CHANGED WHAT

WHEN

WHY

WHAT VERSION FOLLOWED

It does not establish that a person had legal authority to approve that change.

COMMIT ≠ AUTHORITY

⸻

ARTICLE LXVI — CONTROL PRINCIPLES

The Tabernacle adopts:

DRAFT ≠ ADOPTED

ADOPTED ≠ FILED

FILED ≠ APPROVED

COMMIT ≠ AUTHORITY

PR APPROVAL ≠ BOARD APPROVAL

ADMIN ≠ GOVERNANCE

PRIVATE REPO ≠ SECURE VAULT

VERSION HISTORY = PROVENANCE

GITHUB ≠ GENERAL LEDGER

GITHUB ≠ CASE MANAGEMENT

GITHUB ≠ HR FILE

GITHUB ≠ INCIDENT DATABASE

ONE SOURCE OF CONTROLLED DOCUMENT TRUTH

PRESERVE THE RECORD

⸻

ADOPTION

This GitHub Operating System was adopted by the Board of Directors of The Tabernacle, Inc. on:

<DATE>

President / Chair

⸻

Secretary

⸻

Technology Administrator

⸻