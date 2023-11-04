# Provider

A Provider is an entity that made the resources and/or services available for purchase. It is commonly used for cost analysis and reporting scenarios.

The ProviderName column MUST be present in the billing data. This column MUST be of type String and MUST NOT contain null values.

See [Appendix: Origination of cost data](#originationofcostdata) section for examples of Provider, Publisher and Invoice Issuer values that can be used for various purchasing scenarios.

## Column ID

ProviderName

## Display Name

Provider

## Description

Name of the entity that made the resources and/or services available for purchase.

## Content Constraints

| Constraint      | Value         |
| :-------------- | :------------ |
| Column type     | Dimension     |
| Column required | True          |
| Data type       | String        |
| Allows nulls    | False         |
| Normalized      | False         |
| Value format    | Not specified |

## Introduced (version)

0.5
