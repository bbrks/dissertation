# Todo list

## Report
- [ ] **Feedback on one chapter**
- [x] LaTeX Template
- [x] Sectioned
- [x] Title Page
- [x] Contents
- [x] Abstract
- [x] Acknowledgements
- [x] **Background & Objectives**
  - [x] Introduction
  - [x] Background
    - [x] Module Evaluation Method Analysis
  - [x] Objectives
- [x] **Requirements**
  - [x] Features
  - [x] Development Practices
  - [x] User Roes
    - [x] Use Cases
- [x] **Design**
  - [x] Programming Language
  - [x] MVC Framework
    - [x] Routing
    - [x] Directory Structure
  - [x] Internationalisation Framework
  - [x] Database Schema
  - [x] User Interface
- [x] **Implementation**
  - [x] Prerequisites
    - [x] Third-party services
    - [x] Open Source License
    - [x] Development Environment
  - [x] Security Audit and Code Review
  - [x] MVC Framework
  - [x] i18n Framework
  - [x] Deploying on AU Server
- [x] **Testing**
  - [x] Automated Testing (TravisCI)
  - [x] User Testing
  - [x] Acceptance Testing
- [x] **Self-Evaluation**
  - [x] Objectives and Requirements
    - [x] Objectives
    - [x] Requirements
  - [x] Development Environment
  - [x] Choice of language and framework
  - [x] Blog
  - [x] Relevance to degree
  - [x] Links to clients
  - [x] Time Management
  - [x] Future Improvements
- [x] **Bibliography**
- [x] **Appendices**
  - [x] Outline Project Spec
  - [x] Test Tables

## Programming
- [ ] **Re-implement OOP/MVC or tidy up code a lot!**
- [ ] Display no. of respondents in unfinished survey

## Hand-in
- [ ] Print two copies
- [ ] Burn disc/Pendrive?
- [ ] Upload to blackboard
- [ ] Bind two copies
  - [ ] Buy comb-binding materials
  - [ ] Self-bind in HO
  - [x] Label on spine
    - [x] Name
    - [x] Project Title
    - [x] Degree Scheme
    - [x] Date
- [ ] Hand in
- [ ] **Beer** 🍻🍺

---

## Codebase Improvements

#### Short term
- [x] **Change procedural design to OO MVC** *(this is a huuuge one!)*
- [x] Change MySQL and tidy_sql to use PDO
- [x] Login functionality - .htaccess
- [x] Set up TravisCI for unit tests

#### Long term
- [ ] Polished analytics/reports
- [x] extensible i18n system
- [ ] accessibility audit
- [x] Make database relational *(foreign keys etc)*

#### Future Considerations
- [ ] Traffic light module/dept dashboard

## Spike Work
- [x] Travis CI - Automated and continuous integration
  - [x] PHP Unit - Automated unit testing
  - [ ] PHP CodeSniffer - Automated vulnerability scanning and coding standards

---

# Archived

## Programming
- [x] Add hidden field id question to be able to run update query
    set null id if new q- [ ] Show student response rate in list
- [x] Division by zero
    viewall.php line 47
- [x] Error on answering question
    database.php line 58
- [x] Deploy on server
- [x] Lighttpd rewrites/Linux case sensitivity fix
- [x] Change bit to int(1) in schema
- [x] i18n complete
- [x] Fix tabs not saving state in URL
- [x] Include lecturer name hint on question creation page
- [x] Display an SQL connection error if unsuccessful
- [x] Delete questions
- [x] Fix UI on survey view page (status page?)
# [x] email
  - [x] title of survey
  - [x] survey description
  - [x] msg for tailored survey
  - [x] email in welsh
# [x] Remove rewrite dependency
# [x] repeated module questions
  - [x] Fix answer IDs
- [x] replace lecturer variable with lecturer names
- [x] Results tab
- [x] Limit survey reminders to only incomplete surveys
- [x] Sending emails REALLY slow - sendmail hangs on hostname lookup (use SMTP)

## Outline Project Specification
- [ ] Tweak LaTeX style file
- [x] Write report
  - [x] Project Description
  - [x] Proposed Tasks
  - [x] Project Deliverables
  - [x] Annotated Bibliography

## Security Audit
- [x] Read through code and do sanity check
- [x] Look into automated scanning for vulnerabilities

## Immediate concerns
- [x] Create Git tag at starting point to diff between
- [x] Create list of changes to send to Hannah
