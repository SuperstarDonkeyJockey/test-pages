# Quality Engineering Principles

### [Shift Left Testing](#shift-left-testing-1)

### [Share Responsibility For Quality](#share-responsibility-for-quality1)

### [Continuously Integrate (CI)](#continuously-integrate-ci-1)

### [Automate Repeatable Activities](#automate-repeatable-activities-1)

### [Resolve Issues Early](#resolve-issues-early-1)

### [Adopt a Test-Driven Approach](#adopt-a-test-driven-approach-1)

### [Triage Defects](#triage-defects-1)

### [Feature Toggles](#feature-toggles-1)

### [Continuous Delivery (CD)](#continuous-delivery-cd-1)

### [Canary Releases & Testing](#canary-releases--testing-1)

### [Monitoring](#monitoring-1)

## Shift Left Testing

#### Testing is an activity, not a phase

- Test early and often
- Test frequently and iteratively throughout the development process
- Testing is an integral part of software development

#### Test as soon as possible, do not defer

- Testing early provides valuable, fast feedback loops
- Indentify issues at the time they are introduced, not some time later

#### Test early by reviewing user stories

- Review and refine stories iteratively to ensure they comply with INVEST
  - Independent, Negotiable, Valuable, Estimatable, Small, Testable
- Well-written stories provide a common understanding for everyone
- Readable for technical and non-technical people - Scrum Masters, Product Owners, Stakeholders
- Declarative ("what") statements, not imperative ("how")

#### Support stories with acceptance criteria (AC)

- Agree criteria from Product, Development and Testing points of view
- Criteria should be objective and assertable (without subjectivity)
- Define AC before coding - facilitates a test-driven approach

## Share Responsibility For Quality
#### Quality is a team responsibility

- Everybody in the team is accountable for quality
- Every engineer is focused on testing as a valuable feedback mechanism 
- There are no individuals on the team who are solely responsible for testing

#### Appoint a Quality Champion

- The role of the *Quality Champion* is to keep the team focused on quality
- There are two aspects to quality:
  - Quaity Assurance (QA) - prevention (standards, process)
  - Quality Control (QC) - detection (testing)

- Consider rotating the Quality Champion (e.g. every sprint) 

## Continuously Integrate (CI)

#### Every engineer commits often to the shared repository

- Avoid long-lived feature branches which may diverge and conflict as other team members push code
- Aim to push at least once per day, preferrably more frequently

#### Every build failure is fixed as soon as possible

- Do not leave broken builds unattended - treat them as an "emergency"
- Keeping builds green supports:
  - "Working software over comprehensive documentation" from the [Agile Manifesto](http://agilemanifesto.org/)
  - "Working software is the primary measure of progress" from the [Agile Principles](http://agilemanifesto.org/principles.html)

#### Every change to the shared repository triggers an automated build & test

- Automatically execute all unit tests as a minimum with every pushed commit
  - Must pass to be able to create a Pull Request (PR)
- Automatically execute all unit and integration tests as a minimum with every Pull Request (PR)
  - Must pass to be able to merge a PR
- Automatically execute all unit, integration and acceptance tests with every merge attempt
  - Failed builds block any future merges until the failure is resolved

## Automate Repeatable Activities

#### Automated Functional Testing

- There are three levels of automated functional testing:

  **Unit** – an individual atomic behaviour (usually method or function level)

  **Integration** - interaction between components (e.g. API requests and responses)

  **Acceptance** - key user scenarios and journeys (not always through a GUI)

#### The Test Pyramid

- Apply the test pyramid to implement a balanced approach for coverage and speed of execution

  ![test pyramid](Images/TestAutomationPyramid.gif)

- Implement automated tests as far down the pyramid as it is practical to do

- Test narrower and deeper functionality the lower down the pyramid (unit and integration)

- Test wider and shallower user scenarios and journeys toward the top (acceptance)

- Do not test granular functionality at the acceptance level

#### Other Automated Testing

- **Code Analysis** – code styling checks, *linting* (analysing for potential errors)
- **Performance** - simulating many users
- **Security** - at least at a fundamental level

#### Other Automated Activities

- **Builds** – including test execution and package management for dependencies
- **Deployment** - pipelines (DevOps)

## Resolve Issues Early

#### Issues left unresolved reduce quality

- Leaving issues unresolved can prevent the discovery of other issues
- Unresolved issues can block testing of specfic areas, functions or scenarios
- Coded workarounds can break when issues are eventually resolved
- Issues can end up being released into production

#### Issues discovered during development are not defects

- Issues discovered during development simply means development is not yet finished (not "done")
- Logging these issues in a defect reporting system is usually an unnecessary overhead
- An issue only becomes a defect when it is discovered after "done"

## Adopt a Test-Driven Approach

.

## Triage Defects

.

## Feature Toggles

.

## Continuous Delivery (CD)

.

## Canary Releases & Testing

.

## Monitoring

.