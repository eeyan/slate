# Commonly Used Terms

<aside class="notice">
This error section is stored in a separate file in <code>includes/_errors.md</code>. Slate allows you to optionally separate out your docs into many files...just save them to the <code>includes</code> folder and add them to the top of your <code>index.md</code>'s frontmatter. Files are included in the order listed.
</aside>


Term | Description
---------- | -------
Account Holders | Value that serves as a holder for detailed information about the user whose name the account is in.
Account Identifier | A unique identifier (GUID) generated for an account.
Account Refererence Number | A friendly unique identifier of an account that is safe for sharing between Green Dot and partner employees.
ACH In | Transfer type that describes a transfer of funds from an external account to a user’s account. Note: The “achIn” transactionType is used for all transactions where Green Dot is the RDFI.
ACH Out | Transfer type that describes a transfer of funds from a user’s account to an external account.
ACH Pull | Transfer type that describes a transfer of funds from an external account to a user’s account. Note: In the transactions object, achPull is called partnerTransferIn because it is initiated by the partner.
API Call | A request for information that is sent to a server. The API serves as a messenger that delivers the request (call) for information to the provider (server) that you are requesting it from and then delivers the response (requested information) back to you.
Authorization | A merchant request to hold funds on a customer’s account.
Available Balance | The amount of funds, including pending transactions, that is available for use by the user.
CVV | A mandatory 3-4 digit number located on the back of a card that is used for verification during a purchase. It is normally referred to as a security code.
Encrypted | Sensitive data or information that is sent within any API call will be concealed within a code to prevent unauthorized access.
Endpoint | A reference to a URL of a server that accepts requests or API calls.
Enrollment | Synonym for registration. Can be used interchangeably.
Ephemeral Public Key | A string of numbers that is randomly generated for each transaction. This random generation ensures that no key is re-used, which in turn prevents the sensitive information that is being transferred from unauthorized access.
Event - Webhook | An activity that happens outside of the partner’s system (i.e. card transaction at a point of sale (POS) terminal or an account status update).
IDV | Identity Verification (i.e. driver’s license or state identification card)
KYC | Also referred to as know your customer. This is an identity verification process required by the government to prevent activities such as money laundering and fraud.
KYC Gates | Endpoint used to verify users through KYC.
KYC Pending Gate | A KYC Gate that the user must pass to successfully complete KYC.
PAN | Personal account number located on the front side of the card.
Partner | Utilizes our BaaS platform of APIs to expand their financial services
Payment Instrument | A card associated with a user’s account. It can be considered the card in hand and can be plastic, virtual, or metal.
Payment Instrument Identifier | A unique identifier (GUID) generated for a payment instrument.
Payment Instrument Type | The type of payment instrument (card) being used by the user. The card can be either physical or virtual. There are two types of physical cards, emv and magStripe.
PIE | Testing environment
Post | A settlement of funds from the customer account to the merchant.
Product Material Type | Optional. Returns the physical material type of the product. Partner must designate the type(s) they would like to offer to their users.
Public Key Hash | Converts sensitive information into a unique string of text to prevent unauthorized access.
Purse | Balance holding object that is usually the user’s primary account.
Purse Identifier | A unique identifier (GUID) generated for a purse.
Source Transfer Endpoint | Contains information about the source of the transfer.
SSN | Also known as social security number. This is a nine-digit number assigned to U.S. citizens, permanent residents, and temporary residents.
Statement Period | Normally between 28 and 33 days. Its purpose is to summarize the economic activity of the account from the start to the end date. Must be entered in the form YYYYMM.
Target Transfer Endpoint | Contains information about the endpoint (bank account) that the transfer of funds is going to.
Terms and Acceptance Flag | Indicates whether or not the terms were accepted by the user. Required for opt in/out agreements.
Terms and Conditions | A shortcut code used to indicate that all required terms are being accepted as a unit.
Terms Identifier | A unique identifier (GUID) generated for the terms of acceptance.
Transaction Identifier | A unique identifier (GUID) generated for a transaction.
Transfer Endpoint Type | Type of endpoint the transfer of funds is coming from (i.e. account).
Transfer Route | Contains information about the source and target of each new transfer.
UTC | Means time is offset from US time zones by approx. +4 to +11 hours.
Webhooks | A messaging mechanism that enables the partner to receive notification of events (activities) as they occur.
