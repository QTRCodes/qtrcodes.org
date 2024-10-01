# qtrcode.org

## Welcome to QTRCode.org
*Initial content and code specification still being drafted.*

## Overview
Quick Trusted Response (QTR) codes aim to enhance the security and trustworthiness of QR codes by introducing a standardized verification mechanism. By leveraging existing technologies like BIMI (Brand Indicators for Message Identification) and public key cryptography, QTR codes provide a method for users and applications to verify the authenticity of QR code content before any action is taken.

## Why QTR Codes?
- Mitigate QR Code Phishing Attacks: QTR codes help prevent malicious redirection and data theft by verifying the source and integrity of the QR code content.
- Enhance User Trust: By displaying verified brand logos and validation statuses, users can confidently interact with QR codes.
- Backward Compatibility: QTR codes are designed to be compatible with existing QR code readers, ensuring a seamless transition.

## Key Features
- Signature Verification: Uses cryptographic signatures appended as query parameters to verify content authenticity.
- Public Key Retrieval: Supports fetching public keys via DNS records or well-known endpoints.
- BIMI Integration: Incorporates BIMI records to display verified brand logos.
- Offline Validation: Supports caching of BIMI records and public keys for offline verification.

## Get Involved
- Implement QTR Support: Integrate QTR code verification into your applications.
- Contribute to the Specification: Join the discussion and help refine the QTR standard.
- Provide Feedback: Share your insights and help improve the security of QR codes globally.
