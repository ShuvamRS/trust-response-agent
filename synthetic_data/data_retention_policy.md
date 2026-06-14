# Data Retention Policy

**Company:** AcmeCloud Analytics  
**Product:** AcmeCloud Analytics cloud analytics platform for business reporting  
**Document Type:** Synthetic internal policy for demo use  
**Version:** 1.0  
**Effective Date:** 2026-01-15  
**Owner:** Data Governance Team  

## 1. Purpose

This Data Retention Policy describes how AcmeCloud Analytics retains and deletes customer data for its cloud analytics platform. The policy is fictional and designed for use in a GitHub portfolio RAG project. It provides realistic internal evidence while avoiding any real legal, contractual, or certification claims.

The goal of data retention at AcmeCloud Analytics is to retain customer data only for approved business, product, support, and contractual purposes.

## 2. Scope

This policy applies to customer data stored in the AcmeCloud Analytics production platform, including uploaded datasets, generated business reports, dashboard configuration data, workspace metadata, and scheduled export files.

This policy also applies to encrypted backups containing customer data. It does not apply to customer data that has been exported from the platform and stored in customer-managed systems. Customers are responsible for retention and deletion of data after download or export.

## 3. Customer Data Retention During Active Service

During an active subscription, customer data is retained as needed to provide the AcmeCloud Analytics platform. This includes maintaining analytics workspaces, dashboards, report definitions, scheduled jobs, and user-selected report history.

Customers may delete certain datasets or reports through product features. Deleted items may not be immediately removed from encrypted backups because backups follow a separate lifecycle. This document does not specify exact deletion timing for every product object after a user performs an in-application deletion.

## 4. Retention After Contract Termination

Customer data is retained for 30 days after contract termination unless a different retention period is specified in the customer agreement. During the 30-day post-termination period, data may be retained to support export assistance, billing closeout, and account recovery requests.

After the retention period ends, AcmeCloud Analytics begins deletion of customer data from active production systems according to the standard deprovisioning workflow. If a customer agreement specifies a different retention period, the customer agreement controls the retention period for that customer.

This synthetic evidence set does not include actual customer agreements. Therefore, questions about whether a particular customer has a special retention term are not answerable from the provided evidence.

## 5. Backups

Backups are encrypted and tested quarterly. Backups may contain customer data that existed at the time the backup was created. Backup deletion follows the backup lifecycle rather than immediate deletion from active systems.

A quarterly backup restoration test must confirm that backup data can be restored into a controlled non-production recovery environment. Restoration tests are not used for analytics development or employee training. Restored backup data must remain protected as restricted data.

This policy does not state the exact number of days that all backup copies are retained. A question asking for the precise backup retention duration should be answered as not specified in the provided evidence unless another document provides that detail.

## 6. Support Data and Troubleshooting Exports

AcmeCloud Analytics may create temporary troubleshooting exports when needed to investigate a support issue. Troubleshooting exports require a documented business reason and manager approval. Temporary exports must be deleted when the support task is complete.

Support personnel may view account metadata through approved support dashboards. Direct access to production databases is not part of the standard customer support role.

This policy does not specify a universal maximum retention time for all support tickets or customer communications. Those records may follow a separate support operations policy not included in this evidence set.

## 7. Logs and Metadata

Operational logs may include timestamps, system events, request identifiers, and account metadata. Logs are used for security monitoring, reliability analysis, troubleshooting, and incident response.

This policy does not define a single retention period for every category of log. Security investigation logs, application logs, and performance logs may have different retention requirements. Answers about exact log-retention duration require additional evidence.

## 8. Deletion Requests

Customer deletion requests are reviewed by the Data Governance Team or another approved owner. The review confirms whether the request applies to active data, backup data, account metadata, or records subject to contractual retention.

AcmeCloud Analytics does not use production customer data for public demonstrations. Demo data must be synthetic, anonymized, or approved for demonstration use.

## 9. Legal and Contractual Holds

Data subject to a documented contractual hold, legal hold, or security investigation may be retained beyond the standard deletion period until the hold is released. This policy does not define specific legal standards for applying a hold. Such decisions require human review.

## 10. Limitations

This policy does not claim compliance with any external privacy law, security certification, or independent audit. It is synthetic evidence for a fictional company and should not be interpreted as legal advice or a real retention commitment.
