# sergeapollonov

**Product-focused developer · React Native / Expo / TypeScript · AI-assisted development**

I build practical software for everyday problems: organising family life, keeping vehicle maintenance records, finding information in documents and working with utility invoices.

My focus is turning a useful idea into a clear interface and a working implementation. I use AI coding tools to accelerate development, with particular attention to local data, validation, testing and the limits of what has actually been verified.

**Interested in junior frontend/mobile roles and AI-assisted product prototyping opportunities.**

## Selected independent projects

### Doma — family planning with local data

A family planner built with **React Native, Expo and TypeScript**, covering events, household tasks and shopping lists.

- Persistent local state, versioned data migrations and recovery flows.
- Russian and Polish interface, shared design tokens and reusable components.
- Work on date handling, linked records, undo actions and navigation.
- Unit tests, CI checks and documented platform verification.

**Stage:** alpha. The local application is implemented; backend authentication, family sync and notifications remain future work. Full iOS acceptance is still pending. **Source:** private.

### Peugeot 308 Service Book — Android maintenance and live telemetry

A native Android app built with **Kotlin, Jetpack Compose and Room**, combining service records, maintenance planning and live OBD/UDS telemetry.

- Local persistence, service history and PDF reporting.
- Documented on-car testing: an initial session exposed unsuitable data identifiers; after correcting the PID selection, a repeat session recorded **8,442 CSV samples over approximately 25 minutes**.
- Request/response logs provide evidence of ECU communication, including successful reads and rejected requests.
- A transport abstraction and simulated responses support testing without a vehicle; the reviewed CI passed **64 JVM tests** and built a debug APK.

**Stage:** in development, with on-car telemetry sessions documented for one vehicle/adapter setup. Extended parameter decoding, DTC behaviour, automotive calculations and broader compatibility require further validation. **Source:** private.

### ModernPDFSearch — a focused desktop utility

A **Windows-oriented Python application** built with **CustomTkinter and PyMuPDF**.

- Recursive text search across PDF folders.
- Background scanning with cancellation and result navigation.
- File and folder actions, with a PyInstaller packaging configuration.

**Stage:** prototype. Automated tests and a verified release are further work. **Source:** private.

### Rozlicz.to — utility billing workflow prototypes

Related **React / TypeScript / Vite** and **React Native / Expo** projects exploring invoice management and monthly utility cost allocation.

Implemented work includes invoice editing, balance carry-over, multi-month reporting and a Gemini API integration for extracting invoice information.

**Stage:** prototypes. AI extraction, financial calculations and data handling need additional validation before wider use. **Source:** private.

## Additional prototypes

- **Majster Kraków:** a local-service landing page with an enquiry flow, structured SEO data and a promotional-video rendering workflow.
- **Smart TV gateway:** a home-lab integration combining Python parsing, a JavaScript playlist and TV remote navigation.

Both are private projects whose external integrations and deployment need further verification.

## How I approach development

- Start with the user problem and define a manageable scope.
- Make important states visible: empty lists, invalid input, errors and recovery.
- Review AI-generated changes and use tests and runtime checks to examine the result.
- Keep implemented functionality, documented plans and verified behaviour distinct.
- Document decisions and limitations so the next change is easier to understand.

## Technology used in my portfolio

| Area | Technologies |
| --- | --- |
| Cross-platform apps | TypeScript, React Native, Expo, Zustand |
| Web prototypes | React, Vite, HTML, CSS, JavaScript |
| Native Android | Kotlin, Jetpack Compose, Room, coroutines |
| Desktop utilities | Python, CustomTkinter, PyMuPDF, PyInstaller |
| Quality and workflow | Git, pull requests, GitHub Actions, Vitest, JUnit |

My main career focus is **frontend/mobile development and product prototyping**.

## Public work

Earlier HTML/CSS practice: [Uber landing page exercise](https://github.com/sergeapollonov/uber), also mirrored in my [GitHub Pages repository](https://github.com/sergeapollonov/sergeapollonov.github.io).

Most of my recent source repositories are private. The summaries above describe their current scope and development stage.

Languages: Polish · Russian · English.
