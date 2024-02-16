# Architecture Decision Record: Backend Language

## Status

Proposed

## Context

The food ordering app requires menus to be accurate and up-to-date while integrating with the restaurant's inventory management system. The development team requires a decision on which backend language to use that will most efficiently and reliably meet the needs of synchronizing menu data through APIs or web scraping techniques.

## Decision

The team proposes the use of Python for this context.

## Rationale

- **Expertise**
  The development team has extensively covered the Python language in both their studies and personal lives. As Python is a well developed language there is a plethora of online and community support to utilize, if/when complex problems arise.
- **Libraries and Frameworks**
  Python has many API frameworks, most notably the REST variants such as Django, Flask, and Pyramid. These frameworks can be used for various levels of scale, while also providing tasks such as form validation, form generation, and database connectivity.
- **Asynchronous**
  As Python supports asynchronous programming, it can handle large volumes of user API requests simultaneously, which will be necessary during peak food ordering times.

## Consequences

The development team will need to increase their knowledge of the Python frameworks mentioned here, and ensure their level of understanding is proficient enough to meet the requirements noted. An understanding of how the inventory management system's API and Python will communicate must be undertaken immediately following the approval of this ADR.
