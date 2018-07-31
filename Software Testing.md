# Software Testing

1. [Testing Policy](#1-testing-policy)
2. [Good Practices](#2-good-practices)
3. [Delivery Enablers](#3-delivery-enablers)

## 1. Testing Policy

1.1. [Shift Left: Test Early and Often](#11-shift-left)

1.2. [Share Responsibility](#12-share-responsibility)

1.3. [Continuously Integrate (CI)](#13-continuously-integrate-ci)

1.4. [Automate Repeatable Processes](#14-automate-repeatable-processes)

### 1.1. Shift Left

##### Testing is an activity, not a phase

- Test early and often
- Test frequently and iteratively throughout the development process
- Testing is an integral part of software development

##### Test as soon as possible, do not defer

- Testing early provides valuable, fast feedback loops
- Indentify issues at the time they are introduced, not some time later

##### Start by testing requirements (user stories)

- Review and refine stories iteratively to ensure they comply with INVEST
  - Independent, Negotiable, Valuable, Estimatable, Small, Testable
- Well-written stories provide a common understanding for everyone
- Readable for technical and non-technical people - Scrum Masters, Product Owners, Stakeholders
- Declarative ("what") statements, not imperative ("how")

##### Support stories with acceptance criteria (AC)

- Agree criteria from Product, Development and Testing points of view
- Criteria should be objective and assertable (without subjectivity)
- Define AC before coding - facilitates a test-driven approach

### 1.2. Share Responsibility
.

### 1.3. Continuously Integrate (CI)

.

### 1.4. Automate Repeatable Processes

.

## 2. Good Practices

2.1. [Resolve Issues Early](#resolve-issues)

2.2. [Adopt a Test-Driven Approach](#tdd)

2.3. [Prioritise Defects by Triage](#triage-defects)

### 2.1. Resolve Issues Early

##### Issues left unresolved reduce quality

- Leaving issues unresolved can prevent the discovery of other issues
- Unresolved issues can block testing of specfic areas, functions or scenarios
- Coded workarounds can break when issues are eventually resolved
- Issues can end up being released into production

##### Issues discovered during development are not defects

- Issues discovered during development simply means development is not yet finished (not "done")
- Logging these issues in a defect reporting system is usually an unnecessary overhead
- An issue only becomes a defect when it is discovered after "done"

### 2.2. Adopt a Test-Driven Approach

.

### 2.3. Prioritise Defects by Triage

.

## 3. Delivery Enablers

[Feature Toggles](#feature-toggles)

[Continuous Delivery (CD)](#cd)

[Monitoring](#monitoring)

[Canary Releases & Testing](#canarying)

### Feature Toggles

### Continuous Delivery (CD)

### Canary Releases & Testing

### Monitoring

.
