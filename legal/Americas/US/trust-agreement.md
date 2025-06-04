# Nominee Trust Agreement
This Trust Agreement (this "Agreement") is entered into by the Grantor through the creation of a Digital Deed. The identifying information of this trust (the "Trust") may be found in the Digital Deed to which this Agreement is attached.

## Recitals
**Whereas** automated digital protocols provide a secure and interoperable way of representing ownership of assets through the use of an electronic ledger to accurately track, document, and verify all transactions. As a consequence, new systems and methods are emerging to store, interact with, and transact on real and digital assets.

**Whereas** the Grantor wants to link ownership of real property to a Digital Deed to benefit from digital operations and services.

**Whereas** upon issuance of the Digital Deed, the Grantor will attach this Agreement to the Digital Deed and intends for this Agreement to act as the operating agreement of the entity holding the Property. For the purposes of interoperability and standardization, the Grantor and any subsequent party to this Agreement intend to keep all the identifying information of this Agreement stored in the Digital Deed to which this contract has been attached. All the operations, definitions, and procedures related to the Digital Deed and the Trust will be stored in this Agreement.

**Whereas** the purpose and design of this Trust allow the Beneficiary to use digital technology to facilitate transfer and utilization of property ownership. To the extent provided in this Agreement, the Trustee's power and authority to deal with the Property are subject to the direction of the Beneficiary, who holds all economic and beneficial rights to the Property. The Beneficiary (who may change from time to time and is at all times defined as the party presently holding ultimate control over the Digital Deed) is entitled to income, maintains the sole right of termination, and is treated as the owner of the Property for all federal, state, and local tax purposes.

**Whereas** the parties intend to treat all valid operations done via the electronic ledger on the Digital Deed as final, with the same force and effect as a fully executed agreement. Further, the parties intend to treat digital signatures with the same legal consequence as wet signatures.

**Now, therefore**, in consideration of the agreements and obligations set forth herein and for other good and valuable consideration, the receipt and sufficiency of which are hereby acknowledged, the parties agree as follows:

## 1. Trust Purpose
The purpose of the Trust is to create a legally enforceable link such that ownership of the Digital Deed determines ownership of the Property, to allow for time-efficient, cost-effective, accurate, and secure ownership, transfer, use, and enjoyment of real property title in the digital environment (the "Trust Purpose").

Upon creation, the Trust will take and hold title to the Property, and ownership of the Trust will be represented by ownership of the Digital Deed. Regardless of the sale, hypothecation, or other transfer of the Digital Deed, title to the Property will remain in the Trust until such time as the then-present Beneficiary (or another authorized party) distributes the Property out of the Trust. To facilitate the Trust Purpose, the Trustee and Beneficiary agree that no deed or other agreement transferring the Property out of the Trust will be valid unless the Beneficiary has first ensured that the Digital Deed has been successfully locked or destroyed ("Retired").

Subject to Sections 6 and 7, the owner(s) of the Account holding the Digital Deed shall be the Beneficiary of the Trust and have the right to appoint the Trustee. All rights and obligations in this Agreement shall at all times be linked to the owner of the Digital Deed, such that rightful possession of the Digital Deed gives the holder full and total beneficial ownership.

## 2. Definitions
**Account:** An Address owned by a person(s) or entity(ies) and controlled through secure authentication methods, such as private keys, passwords, or biometric data.

**Address:** A unique identifier on an electronic ledger, representing a destination for digital assets.

**Beneficiary:** The individual or entity that is in control of the most recent Account owning the Digital Deed. If the Digital Deed has not yet been issued or has not yet been owned by any Account, the Beneficiary shall be the original Grantor. If ownership of the Digital Deed is subdivided (as discussed further in Sections 6 and 7), then the term Beneficiary applies to the various owners of the Digital Deed as a group.

**Electronic Ledger:** The digital system used to maintain records of ownership and management of the Digital Deed to which this Agreement is attached. This may include blockchain technology or any other secure, decentralized ledger system. The relevant electronic ledger may change due to actions of the Beneficiary, including the migration of the Digital Deed to a different system or the issuance of the Digital Deed on a different platform.

**Retired:** The result of an operation that effectively locks the Digital Deed so that it becomes untransferable forever into the future.

**Confirmed Transaction:** A transaction that has been recorded on the Electronic Ledger and is considered finalized according to the consensus rules of that ledger.

**Contract Account:** An Address controlled by an automated digital protocol, often referred to as a smart contract, which can execute predefined actions when conditions are met.

**Creation Date:** The date and time at which the Trust was created by the Grantor.

**Grantor:** The individual or entity who creates the Trust and grants the Property to the Trust.

**Issue:** An operation that results in the association of a Unique ID to an Address, creating the Digital Deed.

**Property:** The bundle of rights identified in the legal description stored in the Digital Deed Metadata under the fields definition.claim and definition.offchainRegistrar. The Property so described is the bundle of rights which is to be deeded into the Trust and held throughout the life of the Trust.

**Digital Deed:** A digital asset issued using the Protocol Contract. The Digital Deed references the asset and standard on the Electronic Ledger on which it is tracked. If a Digital Deed is migrated to an alternative Electronic Ledger, it will reference the ultimate controlling interest asset at any present moment.

**Automated Digital Protocol:** The code deployed on a specific Electronic Ledger Address that acts as a program to execute and run a series of processes or interactions.

**Protocol Contract:** The Automated Digital Protocol used to maintain records of ownership and management of the Digital Deed to which this Agreement is attached.

**Unique ID:** The unique and immutable identifier determined on Trust creation and assigned to the corresponding Digital Deed. The Unique ID is generated based on the digital signature of multiple fields from the Digital Deed Metadata, including the precise language of this Agreement.

**Digital Deed Metadata:** The data directly stored within the Digital Deed as well as external data stored on a decentralized storage system and linked within the Digital Deed itself (using the fields definition and configuration). These will always include Unique ID, Trust Name (stored as definition.holdingEntity), and Property legal description (definition.claim). Alternative Electronic Ledgers may utilize different data configurations or definitions.

**Transfer:** Any operation performed through the Protocol Contract that assigns the Digital Deed to a new non-null Address.

**Trustee:** The individual or entity appointed as the Trustee of the Trust. At the creation of the Trust, the Trustee is a Qualified Validator assigned during the establishment of the Trust via an automated system. The Trustee will remain the one assigned at the establishment of the Trust unless changed or approved by the Trust Protector.

**Trust Name:** The name of the Trust, more particularly defined in the Digital Deed Metadata (in definition.holdingEntity). It is recommended to encode the Unique ID in the Trust Name using a standard encoding method.

**Trust Protector:** The individual or entity appointed to oversee the Trustee and having the authority to change or remove the Trustee as provided in Section 11.

**Qualified Validator:** An individual or entity that meets all necessary qualifications and complies with applicable laws and regulations to act as the Trustee.

## 3. Establishing the Trust
The process for entering into this Agreement is as follows:

**Creation of Unique ID:** The Grantor, or a third party instructed by the Grantor, creates the Trust by generating a Unique ID using the function generateId on the Protocol Contract.

**Transfer of Property into Trust:** The Grantor transfers the Property into the Trust by deed, or instructs a third-party owner to do so, and records the deed with the relevant authority or recorder. The deed language shall specify both the Protocol Contract address and the Unique ID.

**Issuance of Digital Deed:** The Grantor, or a third party instructed by the Grantor, issues the Digital Deed through the Protocol Contract, attaching this Agreement and a copy of the conveyance deed to the Digital Deed Metadata.

**Confirmation of Transaction:** Upon a Confirmed Transaction, the Beneficiary will be entitled to the Owner Rights (described below). Ownership records for the Digital Deed will be kept by the Protocol Contract.

The Trust is not intended to be, shall not be deemed to be, and shall not be treated as a general partnership, limited partnership, joint venture, corporation, or joint stock company. Prior to a Transfer, the Trust should be considered revocable by the Grantor, up to and until the specification of a Beneficiary. At the point a Beneficiary is specified, the Trust is no longer revocable by the Grantor, and the Beneficiary then retains the sole right to distribute the Property and dissolve the Trust.

If the Digital Deed is issued to a Contract Account, then the Grantor shall be considered the Beneficiary of the Trust, unless otherwise specified.

If the Property has been transferred into the Trust, but the Digital Deed has not yet been issued and no Beneficiary has been specified, the Grantor shall be considered the Beneficiary of the Trust, unless otherwise specified.

## 4. Transactions and Interactions with Protocol Contract
Any signature or execution made through the use of secure authentication methods on an Electronic Ledger for any matters relating to the Digital Deed or the Trust shall be valid, sufficient, and final, as if signed in writing.

Any action that the Beneficiary or Trustee takes with respect to the Property or the Trust shall be invalid unless first instructed through a Confirmed Transaction interacting with the Protocol Contract and under the conditions of this Agreement.

## 5. Grantor Rights and Representations
The Grantor is responsible for funding the Property into the Trust upon creation. Following funding of the Trust, the Grantor (except in their capacity as Trustee and/or Beneficiary) will have no rights regarding the Property, the Digital Deed, or the management of the Trust, and will not retain any voting, director appointment, consent, approval, management, or revocation rights with respect to the Property or the Trust. Further, the Grantor will not have any right to require the Beneficiary or Trustee to consult with the Grantor with respect to the exercise of such rights, and neither the Beneficiary nor the Trustee is required to consult with the Grantor with respect to such rights. The Grantor will have no right to remove or to replace the Beneficiary or Trustee. For purposes of this Agreement, the Trust is not deemed to be an affiliate of the Grantor or any of the Grantor’s affiliates.

Immediately prior to the Grantor’s conveyance of the Property into the Trust, the Grantor represents and warrants:

(a) That the Grantor has the full right, power, and authority to enter into and deliver this Agreement and to perform all covenants and agreements of the Grantor hereunder.

(b) That to the best of the Grantor’s knowledge at the time of creation of the Trust, the Grantor owns fee simple record title to the Property as described in the Property legal description attached to the Digital Deed Metadata; or, if the Grantor does not own fee simple record title to the Property, then the Grantor has attached to the Digital Deed Metadata the full expression of the Grantor's title interest in the Property being granted into the Trust, and a description of any other outstanding interests in the Property at the time of Trust creation.

## 6. Beneficiary Rights
The Beneficiary, or an authorized third party, is authorized to:

- **Execute Functions via Protocol Contract:** Execute any function via the Protocol Contract regarding any decision made by the Beneficiary with respect to the Digital Deed, the Property, and the Trust, including but not limited to transfer, lease, encumbrance, subdivision, or partial or total sale of the Digital Deed; transfer, lock, or utilization of the Digital Deed within any Contract Account; or any other legal and available activity with respect to ownership of property represented by a digital asset.

- **Dissolve the Trust:** Dissolve the Trust and instruct the Trustee to distribute the Property as more fully described in Section 10.

The Beneficiary shall possess beneficial enjoyment of and from the Property, including the right of possession, control, exclusion, enjoyment, and disposition, as well as the right to transfer, lend, or dispose of such, and any other rights traditionally or typically associated with property ownership, subject to the provisions of the Trust. The Beneficiary shall have the right to borrow against the Digital Deed. The Beneficiary is entitled to all net income and receipts from the Property regardless of source and is responsible for any debts, taxes, or other liabilities arising out of the Property or ownership of the Digital Deed. All net income accrued or undistributed at the termination of any interest shall be treated as if it had accrued or been received immediately after that termination. All of the above Beneficiary rights and entitlements are referred to herein as the "Owner Rights."

The Owner Rights should be considered absolute, sole, and uncontrolled, except to the extent that such Owner Rights conflict with other provisions of this Agreement.

## 7. Digital Deed Transfer
The Beneficiary may transfer their Beneficial Interest by transferring the Digital Deed to another Account through the execution of any code or function that results in the assignment of the Unique ID to a different Account. Upon a Confirmed Transaction, the owner of that Account shall become the new Beneficiary of the Trust.

The Trustee will remain the one assigned at the establishment of the Trust unless changed or approved by the Trust Protector. The transfer of the Digital Deed does not automatically result in a change of the Trustee. The Trustee shall continue to serve regardless of changes in the Beneficiary, unless and until the Trustee is changed or removed by the Trust Protector as provided in Section 11.

Transfer of the Digital Deed shall effectuate the full assignment of all interests, rights, duties, liabilities, and obligations under the Trust, except for the role of the Trustee, which remains as assigned unless altered by the Trust Protector. Therefore, use of the terms “Trustee” and “Beneficiary” within this Agreement shall reference the present-interest Trustee (as assigned and potentially modified by the Trust Protector) and the present-interest Beneficiary (as identified by the record of the Digital Deed as maintained by the Protocol Contract).

The Beneficiary may transfer the Digital Deed to a Contract Account, for purposes such as placing the Digital Deed in escrow to collateralize or subdivide it, or to migrate the Digital Deed to an alternative Electronic Ledger. The Digital Deed may transfer to multiple Contract Addresses before being returned to the Beneficiary’s Address or to an alternative Account. Such transfers may, but do not necessarily, cause an assignment of the Beneficial Interest in the Trust. However, the Trustee will remain as initially assigned unless changed or removed by the Trust Protector.

All identifying information about the chain of Accounts and Contract Addresses that have interacted with the Digital Deed, as well as the present owner Account, are immutably recorded on the Electronic Ledger(s) on which the Digital Deed is maintained.

## 8. Trustee Obligations, Fees, and Indemnification
The Trustee shall (the below Trustee rights and duties referred to herein as the "Trustee Rights"):

(a) **Act as Representative:** Act as the representative of the Trust at the behest of the Beneficiary and manage the Property of the Trust consistent with the terms of this Agreement.

(b) **Prepare and Execute Documents:** Prepare, execute, and deliver any documents related to the continued existence of the Trust as well as in connection with any transfer of the Digital Deed or any termination event as defined in Section 10.

(c) **Limited Liability:** Have no duty or liability to the Grantor or Beneficiary with respect to any change in value of any of the Property during the life of the Trust, nor shall the Trustee be liable to any prior or subsequent Beneficiary or Trustee, except to the extent such liability is created by any private agreement or by the willful actions of the Trustee.

(d) **No Bond Required:** Not be required to furnish a bond or other security in any jurisdiction for the faithful performance of its duties.

## 9. No Individual Ownership; Trust Proceeds
Title to all assets of the Trust shall be vested in the Trust until the Trust dissolves; provided, however, that if the applicable laws of any jurisdiction require that title to any part of the assets of the Trust be vested in a party to the Trust, then title to that part of the assets shall be vested in the Beneficiary to the extent so required, with such vested title remaining subject to the assignment and transfer provisions of Section 7. Ownership of the Property will remain in the Trust despite the transfer of the Digital Deed until such time as the Trust is dissolved.

## 10. Trust Termination
The process for dissolving the Trust is as follows ("Dissolution Event"):

**Retire the Digital Deed:** The Beneficiary will retire the Digital Deed by instructing the Protocol Contract.

**Execute Transfer Deed:** After a Confirmed Transaction, the Beneficiary will digitally sign a deed with their secure authentication method and instruct the Trustee to sign the deed transferring the Property and any other remaining Property from the Trust.

**Transfer of Property:** The Trustee will transfer the Property out of the Trust.

In the event of any disposition involving all or part of the Property, the proceeds of such distribution, whether in cash, property, digital assets, or other assets or securities, will be distributed to the Beneficiary or any other person or entity designated by the Beneficiary. If dividends or distributions are paid in respect of any portion of the Trust Property, all such dividends or distributions shall be distributed to the Beneficiary as soon as practicable following receipt.

Once the Trust has been fully established as per the steps in Section 3, and throughout the life of the Trust, the Grantor holds no right of termination, nor is any termination subject to the life of the Grantor or any decision or action taken by the Grantor.

## 11. Trust Protector
The Trust Protector shall be an individual or entity appointed to oversee the Trustee and ensure the Trust operates according to the terms of this Agreement. The Trust Protector has the authority to:

(a) **Remove or Replace Trustee:** Remove or replace the Trustee at any time, with or without cause. The Trustee will remain the one assigned at the establishment of the Trust unless changed or approved by the Trust Protector.

(b) **Amend or Modify Terms:** Amend or modify the terms of the Trust to correct administrative errors or to ensure the Trust's objectives are met, provided such amendments do not alter the fundamental purpose of the Trust or the rights of the Beneficiary.

(c) **Resolve Disputes:** Resolve disputes between the Trustee and Beneficiary.

(d) **Exercise Other Powers:** Exercise such other powers as are granted to the Trust Protector under this Agreement or under applicable law.

The Trust Protector's actions must be in good faith and in the best interests of the Beneficiary and the Trust.

## 12. Trustee Appointment and Qualified Validator
At the establishment of the Trust, the Trustee will be a Qualified Validator assigned via an automated system. The Trustee will remain as assigned at the establishment of the Trust unless changed or approved by the Trust Protector. The Trustee can be changed or removed by the Trust Protector without altering the end goal of the Trust. The Qualified Validator must meet all necessary qualifications and comply with applicable laws and regulations.

## 13. Amendments
This Agreement may be amended or modified only by a written instrument executed by the Beneficiary and the Trustee, with the approval of the Trust Protector. Any amendment must be attached to the Digital Deed Metadata and recorded on the Electronic Ledger through a Confirmed Transaction.

## 14. Conflict Resolution and Dispute Settlement
In the event of any dispute arising out of or relating to this Agreement, the parties agree to first attempt to resolve the dispute through good faith negotiations. If the dispute cannot be resolved through negotiation within thirty (30) days, the parties agree to submit the dispute to binding arbitration under the rules of the American Arbitration Association or another mutually agreed-upon arbitration organization. The arbitration shall take place in the County of Natrona or Laramie, State of Wyoming, and the arbitrator's decision shall be final and binding.

## 15. Governing Law and Jurisdiction
To the extent it is not contrary to a strong public policy of the jurisdiction, if any, having a more significant relationship to this Agreement, the rights and obligations of the parties hereto, and any claims and disputes relating thereto, shall be governed by and construed in accordance with the laws of the State of Wyoming.

The parties to this Agreement hereby consent to the exclusive jurisdiction of any State or Federal Court of competent jurisdiction located within the State of California, in the County of San Francisco, in connection with any actions or proceedings arising directly or indirectly from this Agreement.

## 16. Digital Signature
Given the digital nature of the transaction and the inherent connection to the Digital Deed, the parties hereby agree to use digital signatures to execute this Agreement. Digital signatures executed via secure authentication methods on the Electronic Ledger shall have the same legal effect as traditional handwritten signatures.

## 17. Severability
If any part of any provision of this Agreement or any other agreement, document, or writing given pursuant to or in connection with this Agreement is invalid or unenforceable under applicable law, that part shall be ineffective to the extent of such invalidity only, without affecting the remaining part of said provision or the remaining provisions of this Agreement.

## 18. Miscellaneous
**Headings:** The headings of the sections and subsections of this Agreement are inserted for convenience of reference only and do not form a part or affect the meaning hereof.

**Gender and Number:** Wherever used herein, a pronoun in any gender shall be considered as including any other gender pronoun. References to the singular include the plural, and vice versa.

**Entire Agreement:** This Agreement contains the entire agreement between the parties and supersedes all prior negotiations, understandings, and agreements between the parties concerning its subject matter.

**Binding Effect:** This Agreement is binding upon and inures to the benefit of the parties to this Agreement and their respective heirs, executors, administrators, legal representatives, successors, and assigns as permitted by law.

**Notices:** Any notice required or permitted to be given under this Agreement shall be in writing and shall be deemed to have been duly given when delivered electronically via the Electronic Ledger or by other electronic means as agreed upon by the parties.

## 19. Disclaimer
This Trust Agreement is intended to be a legally binding document. However, the use of digital assets and electronic ledgers is a developing area of law, and legal recognition may vary by jurisdiction. Parties should consult with qualified legal counsel to ensure that this Agreement meets all legal requirements and adequately protects their interests.

**IN WITNESS WHEREOF**, the parties have executed this Agreement as of the Creation Date through their digital signatures on the Electronic Ledger.

