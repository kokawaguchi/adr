# Architecture Decision Record: Payment Gateways

## Status

Proposed

## Context

User payments need to be handled through the app with a consideration for security, user experience, supported regions, and transaction fees. These transactions are handled via a payment gateway, which is a service that handles the payment processing between the app and the customer's bank.

As payments require a high level of security around sensitive user data, it is vital to use a payment gateway that is reputable and well established. This will give users confidence while making payments through the app, which can lead to higher sales.

## Decision

Braintree will be used as the payment gateway as it is noted by [Forbes](https://www.forbes.com/advisor/ca/business/software/best-payment-gateways/) as best overall payment gateway in 2024.

## Rationale

- **Security**
  Braintree was founded in 2007 and acquired by PayPal in 2013, establishing it as a recognized brand that has a reputation for securely handling online transactions.
- **Acceptance**
  Covered by the most popular online payment merchants, such as PayPal, Venmo, ApplePay, Visa, and Mastercard.
- **APIs**
  Being an established service, Braintree is well-documented for API and other developer tools, meaning integration costs and efforts will be reduced.

## Consequences

As payments require a high level of security, developers with expertise may need to be consulted to ensure integration between the app and the payment gateway are handled correctly.

The development team will be required to stay on top not only of changing API changes or updates, but also with various regulatory or security requirements around payment processing.
