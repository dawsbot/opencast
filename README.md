# Opencast

Opencast is a free and open-source indexer designed to empower developers by providing a flexible and powerful way to query data from Farcaster hubs and nodes.

## Overview

Opencast offers an alternative to closed platforms like Naynar, enabling developers to create sophisticated queries that unlock valuable insights from their Farcaster data. 

## Problem

- **Limited Capabilities:** Existing platforms restrict the types of queries you can execute. Opencast breaks these barriers, allowing you to build more dynamic Frames.
    - Example Queries:
        - Identify optimal times for casting content
        - Analyze the performance of your casts sv

- **Data Dependence:** Reliance on third-party platforms creates vulnerabilities like uptime issues and potential paywalls. Opencast empowers you to own and control your data, eliminating such dependencies.

## Solution

Opencast delivers a unique combination of features:

- **Client-Side Agnosticism:** Seamlessly integrate Opencast with your existing client-side applications, regardless of their architecture.
- **Node and Protocol Querying:** Execute powerful queries directly against Farcaster nodes and the underlying protocol, unlocking a wider range of data.
- **Expansive Querying (Future):** A future release will introduce even richer querying capabilities, empowering you to delve deeper into your data.

## Target Audience

- **Short-Term:**
    - Developers who operate their own Farcaster hubs (nodes)
    - Client-side developers seeking to integrate Farcaster data querying
- **Long-Term:**
    - Builders envisioning applications that don't require self-hosted hubs

## Minimum Viable Product (MVP)

The MVP will allow users to interact with the Opencast backend, crafting custom queries to extract valuable data from Farcaster. A demo showcasing both backend functionality and client-side usage examples will be provided.

## Architecture

Opencast is built on a robust technology stack:

- **Backend:**
    - GraphQL: Enables efficient and flexible data querying.
    - Shuttle: Provides real-time communication between the backend and client-side components.
    - Elysia: (Optional) Streamlines data fetching and manipulation.
    - Bun: (Optional) A high-performance JavaScript runtime for a fast and efficient backend.

- **Client-Side:**
    - Opencast is agnostic to the chosen client-side application. It can be used locally as a developer tool, seamlessly integrating with various frameworks and libraries.

## User Interface (UI)

Since Opencast is primarily a developer tool, it doesn't have a traditional user interface. Instead, it exposes a series of well-defined, programmatic endpoints that developers can leverage to build client-side applications with querying capabilities.

## Tooling

- **Error Monitoring:** Sentry (https://sentry.io/resources/error-monitoring/) provides real-time insights into errors and facilitates their timely resolution.
- **Real-time Communication:** Shuttle (https://docs.farcaster.xyz/developers/resources) enables communication between the Opencast backend and client-side application.
- **Farcaster Client/SDK Alternatives:**
    - Litecast (https://github.com/dylsteck/litecast)
    - Search for relevant Farcaster client libraries on GitHub by visiting https://github.com/farcasterxyz

## Getting Started

(Instructions on installation, usage, and contributing will be added in a separate document)

## Contributing

We welcome contributions from the community! (Information on contribution guidelines will be added in a separate document)

## License

Opencast is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

## Disclaimer

This Readme.md is a work in progress. We'll continue to update it with more detailed information as development progresses. Ping [@DawsonBotsford
](https://twitter.com/DawsonBotsford) or [@sydneylai](https://twitter.com/sydneylai) for collaboration.
