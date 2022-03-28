
2022-03-10 (v0.1.4)
-------------------

- Changes to support documentation generation
- Feature: Ensure schema is a valid credential schema that expects `didJwtVc` attribute
- Feature: Ensure credential hasn't expired when verifying (relies on local clock being correct)
- Fix: Base64 encode sharing credential public URI's without using an external library
- Feature: Add additional unit tests for new features and ensuring auto-created `issuanceDate` is correctly set

2022-02-27 (v0.1.3)
-------------------

- Feature: Add more complete unit tests
- Feature: Support error logging
- Feature: Support issuing an encrypted public presentation for sharing
- Feature: Support custom expiryDate and issuanceDate
- Feature: Base64 encode Verida URIs for more compact length