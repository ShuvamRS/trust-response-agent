# Vendor Management Policy

**Company:** AcmeCloud Analytics  
**Product:** AcmeCloud Analytics cloud analytics platform for business reporting  
**Document Type:** Synthetic internal policy for demo use  
**Version:** 1.0  
**Effective Date:** 2026-01-15  
**Owner:** Vendor Risk Team  

## 1. Purpose

This Vendor Management Policy defines how AcmeCloud Analytics evaluates, approves, reviews, and monitors vendors that support the AcmeCloud Analytics cloud analytics platform. The policy is fictional and created for a public-safe RAG demo. It does not name real vendors, subprocessors, auditors, or customers.

The goal of vendor management is to reduce risk from external services that may process, store, transmit, or support access to company or customer data.

## 2. Scope

This policy applies to vendors that provide services used by AcmeCloud Analytics, including infrastructure hosting, monitoring, support workflow tools, internal productivity systems, security tools, and data-processing services.

Vendors are categorized based on risk. Higher-risk vendors include those that may process customer data, support production operations, store restricted internal information, or have administrative access to systems used by AcmeCloud Analytics.

This policy does not include a public subprocessor list. Because this evidence set is fictional synthetic data, AcmeCloud Analytics does not list real subprocessors, real vendor names, real data centers, or real contractual commitments.

## 3. Vendor Onboarding Review

Vendors are reviewed before onboarding. The review must be completed before a new vendor is approved for production use or given access to restricted data.

The onboarding review may include:

- Business purpose and system owner.
- Type of data the vendor may access.
- Whether customer data is involved.
- Security questionnaire or equivalent assessment.
- Review of available security documentation.
- Access method and authentication requirements.
- Data retention and deletion expectations.
- Incident notification expectations.
- Contractual review by the appropriate business owner.

A vendor cannot be approved solely because it is popular or already used by another team. The requesting team must identify why the vendor is needed and what data or systems the vendor will access.

## 4. Annual Vendor Reviews

Vendors are reviewed annually after onboarding. Annual reviews are coordinated by the Vendor Risk Team and system owners. The review checks whether the vendor is still needed, whether the data-use purpose has changed, whether risk level should be updated, and whether any open issues require follow-up.

For vendors supporting production systems or restricted data, the annual review should confirm that the vendor’s security posture remains acceptable for the intended use. If information is missing, the Vendor Risk Team may request updated documentation or require a risk acceptance decision.

This policy does not specify a guaranteed number of days for completing each annual review. It also does not specify that all vendors must provide the same type of security report.

## 5. Vendor Risk Categories

AcmeCloud Analytics uses three internal vendor risk categories:

1. **Low Risk:** Vendor has no access to customer data and no production access.
2. **Moderate Risk:** Vendor may access internal business information or limited operational metadata.
3. **High Risk:** Vendor may process customer data, support production operations, or access restricted systems.

High-risk vendors require approval from the Vendor Risk Team and the system owner. If the vendor may access customer data, the review must document the business purpose and expected data categories.

## 6. Access Requirements

Vendor access must be limited to the minimum level needed. Vendor access to internal systems must use named accounts where supported. MFA is required for AcmeCloud Analytics employees and administrators. For vendor-managed accounts, the required authentication controls depend on the vendor review and contract terms.

The policy does not state that every vendor employee must use the same MFA method as AcmeCloud Analytics employees. That detail requires review of the specific vendor arrangement, which is not included in this evidence set.

## 7. Vendor Incidents

If AcmeCloud Analytics receives notice of a vendor security incident that may affect AcmeCloud Analytics systems or customer data, the issue must be reported to Security Operations. Security Operations determines whether the issue should be handled under the Incident Response Policy.

Critical incidents involving customer data or privileged production access are escalated to the incident response lead. Vendor-related incidents may require additional review by legal, executive, or customer support stakeholders.

## 8. Data Handling and Retention

Vendors that access customer data must have a documented business purpose. Data access should be minimized. Vendor data retention expectations should be reviewed during onboarding and reassessed during annual review.

This policy does not define a universal deletion timeline for all vendors. Vendor-specific deletion requirements depend on the service purpose and applicable agreement.

## 9. Prohibited Practices

Teams must not send customer data to unapproved vendors. Teams must not create unofficial vendor accounts for production support. Teams must not bypass vendor review by using personal accounts, trial accounts, or unmanaged file-sharing tools.

## 10. Limitations

This policy is synthetic and does not represent a real vendor risk program, public subprocessor page, legal commitment, external audit, or certification.
