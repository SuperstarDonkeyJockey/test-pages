# M&S Software Testing

1. [Testing Policy](#policy)
2. [Good Practices](#good-practices)
3. [Delivery Enablers](#enablers)

## 1. Testing Policy {#policy}

1.1. [Shift Left: Test Early and Often](#shift-left)

1.2. [Share Responsibility for Quality](#share-responsibility)

1.3. [Continuously Integrate (CI)](#ci)

1.4. [Automate Repeatable Processes](#automate)

### 1.1. Shift Left: Test Early and Often {#shift-left}

##### Testing is an activity, not a phase

- Test frequently and iteratively throughout the development process
- Testing is an integral part of software development

##### Test as soon as possible, do not defer

- Testing early provides valuable, fast feedback loops
- Indentify issues at the time they are introduced, not some time later

##### Start by testing requirements (user stories)

- Review and refine stories iteratively to ensure they comply with INVEST

  [^1]: Independent, Negotiable, Valuable, Estimatable, Small, Testable

- Well-written stories provide a common understanding for everyone

- Readable for technical and non-technical people - Scrum Masters, Product Owners, Stakeholders

- Declarative ("what") statements, not imperative ("how")

##### Support stories with acceptance criteria (AC)

- Agree criteria from Product, Development and Testing points of view
- Criteria should be objective and assertable (without subjectivity)
- Define before coding - facilitates a test-driven approach

### 1.2. Share Responsibility for Quality {#share-responsibility}

.

### 1.3. Continuously Integrate (CI) {#ci}

.

### 1.4. Automate Repeatable Processes {#automate}

.

## 2. Good Practices {#good-practices}

2.1. [Resolve Issues Early](#resolve-issues)

2.2. [Adopt a Test-Driven Approach](#tdd)

2.3. [Prioritise Defects by Triage](#triage-defects)

### 2.1. Resolve Issues Early {#resolve-issues}

##### Issues left unresolved reduce quality

- Leaving issues unresolved can prevent the discovery of other issues
- Unresolved issues can block testing of specfic areas, functions or scenarios
- Coded workarounds can break when issues are eventually resolved
- Issues can end up being released into production

##### Issues discovered during development are not defects

- Issues discovered during development simply means development is not yet finished (not "done")
- Logging these issues in a defect reporting system is usually an unnecessary overhead
- An issue only becomes a defect when it is discovered after "done"

### 2.2. Adopt a Test-Driven Approach {#tdd}

.

### 2.3. Prioritise Defects by Triage {#triage-defects}

.

## 3. Delivery Enablers {#enablers}

[Feature Toggles](#feature-toggles)

[Continuous Delivery (CD)](#cd)

[Monitoring](#monitoring)

[Canary Releases & Testing](#canarying)

### Feature Toggles {#feature-toggles}

### Continuous Delivery (CD) {#cd}

### Canary Releases & Testing {#canarying}

### Monitoring {#monitoring}

.