# Invoice Issuer

An Invoice Issuer is an entity responsible for invoicing for the resources and/or services consumed. It is commonly used for cost analysis and reporting scenarios.

The InvoiceIssuerName column MUST be present in the billing data. This column MUST be of type String and MUST NOT contain null values.

See [Appendix: Origination of cost data](#originationofcostdata) section for examples of Provider, Publisher, and Invoice Issuer values that can be used for various purchasing scenarios.

## Column ID

InvoiceIssuerName

## Display Name

Invoice Issuer

## Description

Name of the entity responsible for invoicing for the resources and/or services consumed.

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
