# Secondary Materials Market Room

## One-sentence benefit

Help European recyclers and manufacturers turn fragmented recovered-material offers into trusted cross-border supply.

## Live demo

[Watch the workflow](docs/demo.webm).

## Screenshots

![Secondary materials market dashboard](docs/screenshot.png)

## Main features

- Search and sort listings by material, supplier, market owner or status.
- Create validated listings with priorities and accountable teams.
- Advance listings through draft, review and approved states.
- Show loading, empty, error and success feedback.
- Present operational and market-guidance areas responsively.

## Technology used

Angular, TypeScript, signals, computed state, HttpClient, Vite, Spring Boot and Java 21.

## Installation instructions

Install Node.js 22 and Java 21. Run `npm install`, start `cd backend && mvn spring-boot:run`, then run `npm start`.

## Commercial licensing/contact

Commercial licensing and integration support are available through the repository contact options.

## Business problem and users

Recyclers, laboratories, industrial buyers and market authorities need consistent quality evidence and accountable cross-border listing decisions.

## Key workflows

Find a material lot, create a listing, assign a market owner, advance it after quality review and confirm the API result.

## Angular framework highlights

Signals and computed values drive efficient state, HttpClient handles real writes and built-in control flow renders status-aware actions.

## Java backend highlights

Spring Boot exposes validated list, search, create and update APIs, clear errors, health status and service tests.

## Architecture and state flow

Angular calls `/api/items`; Java validates requests and Angular signals update from returned records.

## Accessibility and responsive behaviour

Semantic regions, labelled search, keyboard actions, visible focus and adaptive grids support varied devices.

## Verification commands

Run `npm test`, `npm run build`, `cd backend && mvn test` and `cd backend && mvn package`.

## Structure

`src` contains Angular, `backend` contains Java and `docs` contains inspected media.

## Tradeoffs

In-memory records keep setup simple; production needs authentication, persistence and laboratory certificate exchange.

## Roadmap

Add material taxonomies, certificate uploads, buyer matching, logistics data and multilingual market notices.
