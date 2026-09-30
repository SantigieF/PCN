# Poison Centre Notification (PCN)
## Initial Submission – IUCLID 6 Master Checklist

**Applicable reference:** Current ECHA PCN Format, currently Version 8, and applicable IUCLID 6 release.

> **Controlled-document principle:** Where this checklist refers to a controlled PCN picklist, the preparer must use the value available in the current IUCLID PCN implementation/ECHA PCN picklist. Do not create or manually type an alternative wording unless the PCN format explicitly provides a free-text field.

---

# PHASE 0 — Regulatory Scope & Product Assessment

## 0.1 Product scope

- [ ] Confirm the product is a **mixture** within the scope of Article 45 and Annex VIII of the CLP Regulation.
- [ ] Confirm the mixture is classified for **health and/or physical hazards**, where applicable.
- [ ] Confirm that a PCN is required for the intended market(s).
- [ ] Confirm applicable compliance date/transition provisions.
- [ ] Confirm the product is not excluded from the PCN obligation.
- [ ] Confirm whether the product is already subject to an existing PCN.
- [ ] Determine whether this is:
  - [ ] Initial notification
  - [ ] Update
  - [ ] New notification following significant change of composition
- [ ] Confirm the legal entity responsible for placing the mixture on the market.
- [ ] Confirm the markets/Member States in which the mixture will be placed on the market.

## 0.2 Annex VIII assessment

- [ ] Determine whether a **standard/full notification** is required.
- [ ] Determine whether a **Limited Submission** is legally applicable.
- [ ] Determine whether a **Group Submission** is appropriate.
- [ ] Determine whether a **Standard Formula (SF)** applies.
- [ ] Determine whether an **Interchangeable Component Group (ICG)** applies.
- [ ] Determine whether any components qualify for a **Generic Component Identifier (GCI)**.
- [ ] Identify all **Mixture-in-Mixture (MiM)** components.
- [ ] Determine whether MiM composition is fully known, partially known or unknown.
- [ ] Identify any other Annex VIII special provisions applicable to the product.

---

# PHASE 1 — IUCLID SOFTWARE & WORKING CONTEXT

## 1.1 IUCLID version

- [ ] Confirm the current approved IUCLID 6 release is being used.
- [ ] Record IUCLID version/release.
- [ ] Confirm the PCN format supported by the IUCLID installation.
- [ ] Confirm that the current ECHA PCN format/version is being used.

**Current reference:** ECHA currently identifies PCN Format **Version 8**, last updated 27 April 2026. The PCN format is updated annually with the IUCLID release cycle.

## 1.2 Working context

- [ ] Open IUCLID 6.
- [ ] Create the appropriate mixture/product dataset.
- [ ] Select the appropriate **CLP Poison Centre Notification / PCN working context**.
- [ ] Confirm the PCN-specific fields and validation rules are available.
- [ ] Confirm the dataset is not accidentally being prepared under an inappropriate regulatory context.

---

# PHASE 2 — LEGAL ENTITY

## 2.1 Legal Entity

- [ ] Confirm the correct Legal Entity document exists in IUCLID.
- [ ] Confirm Legal Entity name.
- [ ] Confirm Legal Entity UUID.
- [ ] Confirm Legal Entity country.
- [ ] Confirm the Legal Entity is the entity that will submit the PCN.
- [ ] Confirm the Legal Entity corresponds to the ECHA Submission Portal account/entity.
- [ ] Confirm the correct Legal Entity is linked to the mixture/dossier.

## 2.2 BR570 / Legal Entity consistency check

- [ ] Compare IUCLID Legal Entity UUID with ECHA Submission Portal submitting entity UUID.
- [ ] Confirm the UUIDs are identical.
- [ ] Confirm legal entity country is correct.
- [ ] Confirm legal entity name is correct.
- [ ] Perform a pre-submission BR570/related Legal Entity consistency check.

> **Do not rely on the company name alone. The UUID is the critical identifier.**

---

# PHASE 3 — DOSSIER HEADER & NOTIFICATION IDENTITY

## 3.1 PCN number

- [ ] Generate/create a **new PCN number** for the initial notification.
- [ ] Confirm the PCN number is unique.
- [ ] Confirm it has not been copied from an existing PCN unnecessarily.
- [ ] Record the PCN number in the regulatory tracking system.

## 3.2 Keep identifiers separate

Record separately:

- [ ] **PCN number**
- [ ] **IUCLID dossier UUID**
- [ ] **ECHA Submission ID/number**
- [ ] **UFI(s)**

> These identifiers must not be treated as interchangeable.

## 3.3 Notification characteristics

Select the appropriate characteristics:

- [ ] Standard/full information
- [ ] Limited Submission, if applicable
- [ ] Group Submission, if applicable

## 3.4 Notification type

Select:

- [ ] Initial notification

Do **not** select Update or significant-composition-change notification simply because the product has previously been prepared internally.

## 3.5 Markets and languages

- [ ] Select every applicable Member State/market.
- [ ] Confirm no intended market is missing.
- [ ] Remove countries that are not intended markets.
- [ ] Determine required language(s) for each selected market.
- [ ] Select all applicable target languages.
- [ ] Confirm multilingual free-text fields will be completed where required.

## 3.6 Dossier administration

- [ ] Enter internal dossier/product name.
- [ ] Enter submission remarks where useful.
- [ ] Record internal project/reference number if used.
- [ ] Record preparer.
- [ ] Record reviewer.

---

# PHASE 4 — REFERENCE SUBSTANCES & SUBSTANCE IDENTITY

For **every substance component**:

- [ ] Confirm a corresponding Reference Substance exists.
- [ ] Import an appropriate ECHA/IUCLID Reference Substance where available.
- [ ] If necessary, create a new Reference Substance.
- [ ] Verify chemical name.
- [ ] Verify IUPAC name where applicable.
- [ ] Verify CAS number.
- [ ] Verify EC/List number.
- [ ] Verify molecular formula.
- [ ] Verify molecular structure where appropriate.
- [ ] Verify synonyms/alternative identifiers.
- [ ] Confirm the Reference Substance represents the **correct substance identity**.
- [ ] Link the composition component to the correct Reference Substance.

## Substance identity quality check

- [ ] Compare against SDS Section 3.
- [ ] Compare against raw-material specification.
- [ ] Compare against formulation/BOM.
- [ ] Investigate discrepancies.
- [ ] Confirm that a similar substance has not been selected accidentally.

---

# PHASE 5 — Mixture-in-Mixture (MiM)

For every MiM:

- [ ] Identify the MiM.
- [ ] Identify the MiM supplier.
- [ ] Identify supplier Legal Entity where required.
- [ ] Determine whether complete MiM composition is known.
- [ ] Determine whether composition is partially known.
- [ ] Determine whether composition is unknown.
- [ ] Obtain current supplier SDS/composition information.
- [ ] Obtain supplier UFI where applicable.
- [ ] Verify supplier UFI.
- [ ] Verify MiM classification/labelling information.
- [ ] Enter the MiM according to the applicable PCN structure.
- [ ] Identify substances within the MiM that must be reported.
- [ ] Confirm the MiM information is consistent with supplier information.

### MiM UFI check

- [ ] Do not assume a MiM UFI automatically replaces all composition information.
- [ ] Confirm the UFI actually corresponds to the supplier's relevant MiM.
- [ ] Confirm the MiM is being used in accordance with the PCN rules for MiMs.

---

# PHASE 6 — COMPOSITION & ANNEX VIII CONCENTRATION

## 6.1 Component-by-component assessment

For every component:

- [ ] Identify substance/MiM.
- [ ] Determine hazardous/non-hazardous status.
- [ ] Determine whether it is a **component of major concern**.
- [ ] Determine the appropriate Annex VIII concentration-reporting requirement.
- [ ] Enter exact concentration or permitted concentration range.
- [ ] Confirm concentration units.
- [ ] Confirm concentration basis.
- [ ] Confirm concentration range is permitted under Annex VIII.
- [ ] Confirm lower and upper limits are scientifically/formulation-wise defensible.
- [ ] Confirm required hazardous components are present.
- [ ] Confirm no relevant component has been omitted.

## 6.2 Formulation reconciliation

Reconcile the PCN against:

- [ ] Approved formulation/BOM.
- [ ] Manufacturing formulation.
- [ ] SDS Section 3.
- [ ] Raw-material specifications.
- [ ] Supplier information.
- [ ] Existing regulatory composition record.

## 6.3 Internal range checks

- [ ] Check minimum possible formulation composition.
- [ ] Check maximum possible formulation composition.
- [ ] Check concentration ranges for overlap/gaps.
- [ ] Perform midpoint plausibility check.
- [ ] Investigate unusual totals.
- [ ] Do **not** artificially manipulate concentration ranges solely to force midpoint totals to 100%.

---

# PHASE 7 — SPECIAL ANNEX VIII STRUCTURES

## 7.1 Generic Component Identifier (GCI)

- [ ] Determine whether the component qualifies for GCI treatment.
- [ ] Confirm the component is eligible.
- [ ] Confirm applicable concentration thresholds.
- [ ] Select the correct approved GCI.
- [ ] Confirm GCI is being used only where permitted.
- [ ] Confirm the GCI does not obscure a substance that must be individually identified.

## 7.2 Standard Formula (SF)

- [ ] Determine whether an applicable Standard Formula exists.
- [ ] Confirm product qualifies for the relevant SF.
- [ ] Confirm formulation meets SF conditions.
- [ ] Select correct Standard Formula dataset/template.
- [ ] Enter the required SF information.
- [ ] Verify SF against the actual formulation.
- [ ] Do not use SF simply because the product is broadly similar to an SF category.

## 7.3 Interchangeable Component Groups (ICG)

- [ ] Determine whether ICG criteria are met.
- [ ] Confirm components are genuinely interchangeable.
- [ ] Confirm relevant hazard/emergency-response consequences.
- [ ] Define the ICG correctly.
- [ ] Enter total group concentration.
- [ ] Enter individual component ranges.
- [ ] Check ICG-specific validation requirements.
- [ ] Confirm ICG is not being used merely to conceal a known fixed formulation.

---

# PHASE 8 — MIXTURE IDENTITY & PRODUCT INFORMATION

## 8.1 Mixture identity

- [ ] Enter correct mixture/product name.
- [ ] Confirm commercial product name.
- [ ] Confirm alternative names where applicable.
- [ ] Confirm mixture identity is consistent with SDS.
- [ ] Link correct Legal Entity.
- [ ] Confirm contact information.

## 8.2 Product/trade-name records

For each product/trade-name presentation:

- [ ] Enter trade name.
- [ ] Enter applicable product identifier.
- [ ] Link applicable UFI.
- [ ] Confirm country/market applicability.
- [ ] Confirm product variant relationship.
- [ ] Confirm product composition relationship.

---

# PHASE 9 — UFI MANAGEMENT

## 9.1 UFI generation

- [ ] Generate/obtain UFI using the appropriate ECHA UFI process.
- [ ] Confirm correct company VAT/tax identifier or company information used in generation, as applicable.
- [ ] Confirm correct formulation number/reference used.
- [ ] Record UFI internally.

## 9.2 UFI validation

- [ ] Check UFI character-by-character.
- [ ] Confirm UFI corresponds to the correct formulation.
- [ ] Confirm UFI is not associated with a different composition.
- [ ] Confirm UFI appears in the appropriate PCN record.
- [ ] Confirm UFI is linked to the correct product/trade name.
- [ ] Confirm every UFI appearing on the label is appropriately represented in the PCN.
- [ ] Confirm products sharing the same composition have been assessed for UFI reuse.
- [ ] Confirm different compositions have not inadvertently been assigned the same UFI.

---

# PHASE 10 — EuPCS & USE INFORMATION

## 10.1 EuPCS

- [ ] Select the correct **European Product Categorisation System (EuPCS)** code.
- [ ] Confirm the selected category accurately describes the product's intended use.
- [ ] Do not select a category simply because it resembles the product name.
- [ ] Check secondary/additional use information where applicable.

## 10.2 Use type

- [ ] Consumer.
- [ ] Professional.
- [ ] Industrial.
- [ ] Multiple applicable use types where appropriate.

## 10.3 Use consistency

- [ ] Compare PCN use with SDS Section 1.
- [ ] Compare with label/product instructions.
- [ ] Compare with actual distribution/supply chain.
- [ ] Confirm no inappropriate use type has been selected.

---

# PHASE 11 — PHYSICAL & CHEMICAL INFORMATION

## 11.1 Physical state

- [ ] Record physical state.
- [ ] Confirm appropriate state for the product at the relevant reference conditions.
- [ ] Record form where applicable.
- [ ] Confirm consistency with SDS.

## 11.2 Appearance

- [ ] Colour.
- [ ] Colour intensity where applicable.
- [ ] Physical appearance.
- [ ] Clarity where applicable.
- [ ] Confirm consistency with commercial product.

## 11.3 pH

- [ ] Enter pH value where available.
- [ ] Enter permitted pH range where applicable.
- [ ] Enter required solution concentration associated with pH.
- [ ] If pH is unavailable/not relevant, select the appropriate **predefined PCN justification**.
- [ ] Do not invent a free-text justification where a controlled justification is available.
- [ ] Confirm pH relates to the actual mixture.
- [ ] Confirm pH/range is consistent with supporting technical data.

---

# PHASE 12 — CLASSIFICATION & LABELLING

## 12.1 Final mixture classification

- [ ] Confirm current CLP classification.
- [ ] Confirm physical hazards.
- [ ] Confirm health hazards.
- [ ] Confirm applicable hazard classes/categories.
- [ ] Confirm H-statements.
- [ ] Confirm signal word.
- [ ] Confirm pictograms.
- [ ] Confirm precautionary statements.
- [ ] Confirm supplemental EUH information.
- [ ] Confirm applicable M-factors.
- [ ] Confirm applicable SCLs.
- [ ] Check harmonised classification where applicable.
- [ ] Check current CLP amendments/ATPs.
- [ ] Confirm classification is consistent with the approved regulatory assessment.

## 12.2 Component/MiM classification

- [ ] Verify classification of relevant substances.
- [ ] Verify classification of relevant MiMs.
- [ ] Confirm relevant harmonised classifications.
- [ ] Confirm classification is consistent with the composition used in the PCN.
- [ ] Confirm current regulatory classification data have been used.

---

# PHASE 13 — CONTROLLED PCN LABELLING DATA

> **Critical SOP rule:** Do not manually create standard H-, P-, EUH- or pictogram wording. Use the controlled values available in the current PCN/IUCLID picklists. ECHA's PCN Guide identifies Signal Word, Hazard Pictograms and Hazard Statements as picklist-controlled fields.

## 13.1 Signal word

- [ ] Select the applicable signal word from the PCN picklist.
- [ ] `Danger`
- [ ] `Warning`
- [ ] `No signal word`, where applicable/available in the PCN implementation.
- [ ] Confirm selected signal word corresponds to the final mixture classification.
- [ ] Do not manually type an alternative wording.

ECHA's PCN Guide identifies Signal Word as a **mandatory single-select picklist** and states that the applicable values include `Danger` and `Warning`, with a corresponding no-signal-word value where applicable.

## 13.2 Hazard pictograms

For each applicable pictogram:

- [ ] Select from the controlled PCN picklist.
- [ ] Confirm pictogram corresponds to the applicable classification.
- [ ] Confirm all applicable pictograms have been included.
- [ ] Confirm no inappropriate pictogram has been selected.
- [ ] Confirm pictogram priority/reduction rules have been considered under CLP.
- [ ] Confirm pictograms correspond to the final approved product label.
- [ ] Confirm the maximum permitted number is not exceeded.

ECHA's Guide identifies hazard pictograms as a controlled picklist and states that up to nine different GHS codes can be provided in the relevant PCN structure.

## 13.3 Hazard statements

For each applicable hazard statement:

- [ ] Select the statement from the current PCN controlled picklist.
- [ ] Confirm the H-code is correct.
- [ ] Confirm the selected statement corresponds to the classification.
- [ ] Confirm all applicable hazard statements are included.
- [ ] Confirm no obsolete/incorrect statement has been selected.
- [ ] Confirm the statement is consistent with the current CLP legal wording.

### Additional text

Where the selected hazard statement contains an editable component:

- [ ] Determine whether `Additional text` is required.
- [ ] Enter **only the editable part**.
- [ ] Do not duplicate the standard hazard statement in `Additional text`.
- [ ] Where multiple editable elements are required, use the required separator.
- [ ] Verify the order of editable elements.

ECHA's Guide specifically states that `Additional text` is to be used only where the hazard statement contains editable parts, and gives the format using `|` between editable elements.

Example structure:

`doctor|inhalation`

rather than rewriting the entire H-statement.

## 13.4 Precautionary statements

- [ ] Select applicable P-statements from the controlled PCN picklist.
- [ ] Confirm each P-statement is appropriate to the final classification/product.
- [ ] Confirm unnecessary/inapplicable P-statements have not been included.
- [ ] Confirm the selected wording is the current controlled wording.
- [ ] Do not manually retype standard P-statement text into a free-text field.

## 13.5 Supplemental hazard information / EUH statements

- [ ] Identify applicable supplemental hazard information.
- [ ] Select the applicable statement from the controlled PCN list.
- [ ] Confirm statement is legally applicable.
- [ ] Confirm statement corresponds to current CLP Annex III requirements.
- [ ] Do not manually create alternative wording.
- [ ] Where an editable element is required, enter only the permitted editable component.
- [ ] Confirm multilingual requirements.

ECHA's Guide states that the relevant supplementary statements must be selected from a **predefined list of existing values according to Annex III Part 2 of the CLP Regulation**.

## 13.6 Picklist source control

- [ ] Confirm the selected value exists in the current ECHA PCN picklist.
- [ ] Record the PCN format version used.
- [ ] Do not use a copied picklist from an obsolete PCN format.
- [ ] Where an internal labelling database is used, confirm it has been updated to the current PCN picklist.
- [ ] For controlled SOPs, maintain the current ECHA picklist file as a controlled reference.

ECHA's current PCN Version 8 package explicitly includes the **picklist values in both XML and Excel formats**.

---

# PHASE 14 — TOXICOLOGICAL INFORMATION

## 14.1 Mixture toxicology

- [ ] Prepare mixture toxicological information based on the available SDS/toxicological assessment.
- [ ] Enter the required toxicological free text.
- [ ] Ensure information is useful for emergency medical response.
- [ ] Do not simply enter "See SDS Section 11".
- [ ] Do not use irrelevant generic toxicology text.
- [ ] Confirm information is specific to the submitted mixture.

## 14.2 Languages

For each required market language:

- [ ] Enter required toxicological information.
- [ ] Translate/review free-text information.
- [ ] Confirm terminology is appropriate.
- [ ] Confirm no required language field is blank.
- [ ] Confirm information is consistent between languages.
- [ ] Confirm translations have undergone appropriate regulatory/linguistic review.

---

# PHASE 15 — EMERGENCY CONTACT

## Limited Submission

- [ ] Confirm 24/7 emergency contact is provided.
- [ ] Confirm contact can rapidly access complete formulation information.
- [ ] Confirm telephone number.
- [ ] Confirm email where applicable.
- [ ] Confirm organisation/person.
- [ ] Confirm country.
- [ ] Confirm contact is appropriate for every relevant market.
- [ ] Create separate country records where required.

## Other submissions

- [ ] Determine whether emergency contact information is appropriate/required.
- [ ] If provided, confirm contact details are current.
- [ ] Confirm contact has agreed to provide the necessary emergency support.

---

# PHASE 16 — PACKAGING

For consumer/professional products:

- [ ] Select correct packaging type.
- [ ] Confirm packaging material/type is correct.
- [ ] Enter nominal packaging size.
- [ ] Confirm units.
- [ ] Enter all relevant packaging presentations.
- [ ] Link packaging information to the correct product.
- [ ] Confirm packaging information against actual commercial packaging.

## Packaging reconciliation

- [ ] PCN packaging = actual marketed packaging.
- [ ] Label/packaging presentation is consistent.
- [ ] Packaging size is correct.
- [ ] Packaging type is correct.

---

# PHASE 17 — FOUR-WAY DATA RECONCILIATION

Before validation, perform a formal comparison between:

## PCN ↔ Approved formulation

- [ ] Composition matches.
- [ ] Concentrations/ranges match.
- [ ] Components match.
- [ ] MiMs match.
- [ ] UFIs match formulation.

## PCN ↔ SDS

- [ ] Product name matches.
- [ ] UFI matches.
- [ ] Composition information is consistent.
- [ ] Classification is consistent.
- [ ] Physical state is consistent.
- [ ] pH is consistent.
- [ ] Intended use is consistent.
- [ ] Toxicological information is consistent.

## PCN ↔ Label

- [ ] Product/trade name matches.
- [ ] UFI matches.
- [ ] Pictograms match.
- [ ] Signal word matches.
- [ ] H-statements match.
- [ ] P-statements are appropriately represented.
- [ ] Supplemental hazard information is consistent.
- [ ] Product presentation matches.

## PCN ↔ Commercial/Product Master Data

- [ ] Markets are correct.
- [ ] Trade names are correct.
- [ ] Product variants are correct.
- [ ] Packaging is correct.
- [ ] Packaging sizes are correct.
- [ ] Use type is correct.
- [ ] EuPCS is correct.

---

# PHASE 18 — VALIDATION ASSISTANT

## 18.1 IUCLID validation

- [ ] Run the IUCLID Validation Assistant.
- [ ] Review all validation errors.
- [ ] Review all quality warnings.
- [ ] Open flagged records directly from the validation report.
- [ ] Correct all blocking errors.
- [ ] Investigate all quality warnings.
- [ ] Document justification for any warning intentionally retained.
- [ ] Re-run validation after corrections.
- [ ] Confirm final validation result.

## 18.2 Current validation rules

- [ ] Confirm the validation rules correspond to the current PCN format.
- [ ] Confirm no old validation-rule document is being used as the sole reference.
- [ ] Review high-risk rules concerning:
  - [ ] Legal Entity
  - [ ] PCN number
  - [ ] UFI
  - [ ] composition
  - [ ] markets
  - [ ] languages
  - [ ] product identity
  - [ ] classification/labelling
  - [ ] packaging
  - [ ] pH
  - [ ] MiMs
  - [ ] Limited/Group submissions.

---

# PHASE 19 — FINAL DOSSIER CREATION

Before dossier creation:

- [ ] Confirm all datasets are final.
- [ ] Confirm all Reference Substances are correct.
- [ ] Confirm Legal Entity.
- [ ] Confirm PCN number.
- [ ] Confirm notification type.
- [ ] Confirm markets.
- [ ] Confirm languages.
- [ ] Confirm composition.
- [ ] Confirm MiMs.
- [ ] Confirm UFI(s).
- [ ] Confirm EuPCS.
- [ ] Confirm product identity.
- [ ] Confirm packaging.
- [ ] Confirm pH.
- [ ] Confirm classification.
- [ ] Confirm controlled labelling data.
- [ ] Confirm toxicological information.
- [ ] Confirm emergency contact where applicable.
- [ ] Confirm validation status.

Then:

- [ ] Create final dossier.
- [ ] Confirm dossier UUID.
- [ ] Confirm dossier is based on the intended final dataset.
- [ ] Save final `.i6z`.
- [ ] Generate PCN Dossier Report.
- [ ] Save report to controlled records.

---

# PHASE 20 — FOUR-EYES FINAL REVIEW

A second competent regulatory reviewer independently verifies:

### Administrative

- [ ] Legal Entity
- [ ] Legal Entity UUID
- [ ] PCN number
- [ ] Dossier UUID
- [ ] Notification type
- [ ] Submission characteristics
- [ ] Markets
- [ ] Languages

### Composition

- [ ] Full formulation
- [ ] Annex VIII concentration ranges
- [ ] Components of major concern
- [ ] MiMs
- [ ] GCI
- [ ] SF
- [ ] ICG

### Product

- [ ] Product name
- [ ] Trade name
- [ ] UFI
- [ ] EuPCS
- [ ] Use type
- [ ] Packaging

### Hazard information

- [ ] Classification
- [ ] Signal word
- [ ] Pictograms
- [ ] H-statements
- [ ] P-statements
- [ ] EUH/supplemental statements
- [ ] Additional text
- [ ] Physical state
- [ ] pH
- [ ] Toxicological information

### Submission

- [ ] Validation completed
- [ ] Errors resolved
- [ ] Warnings reviewed
- [ ] Dossier report generated
- [ ] Final `.i6z` generated

**Prepared by:** __________________

**Reviewed by:** __________________

**Date:** __________________

**PCN number:** __________________

**Dossier UUID:** __________________

**IUCLID version:** __________________

**PCN format version:** __________________

---

# PHASE 21 — SUBMISSION

- [ ] Export final `.i6z`.
- [ ] Confirm correct final dossier selected.
- [ ] Log into ECHA Submission Portal.
- [ ] Confirm correct submitting Legal Entity/account.
- [ ] Upload dossier.
- [ ] Complete portal information.
- [ ] Submit.
- [ ] Record ECHA Submission ID/number.
- [ ] Record submission date/time.
- [ ] Confirm submission status.
- [ ] Review submission result.
- [ ] Review any portal validation messages.
- [ ] Resolve any submission-blocking issue.
- [ ] Confirm successful submission/processing.

> **Important:** Do not treat successful IUCLID validation as equivalent to successful ECHA submission. ECHA identifies PCN validation rules as being incorporated into both IUCLID and the ECHA Submission Portal.

---

# PHASE 22 — POST-SUBMISSION ARCHIVING

Archive the following:

- [ ] Final `.i6z` dossier.
- [ ] PCN Dossier Report.
- [ ] IUCLID Validation Report.
- [ ] ECHA Submission ID/receipt.
- [ ] PCN number.
- [ ] Dossier UUID.
- [ ] UFI(s).
- [ ] Approved formulation.
- [ ] SDS used for submission.
- [ ] Final label artwork.
- [ ] Packaging information.
- [ ] Toxicological information.
- [ ] Target-market/language list.
- [ ] Relevant translations.
- [ ] Supporting MiM information.
- [ ] Legal Entity information.
- [ ] Four-eyes review/sign-off.
- [ ] Any submission correspondence.
- [ ] Any justification for retained validation warnings.

---

# PHASE 23 — LABEL / SDS / PCN RELEASE CONTROL

Before product release:

- [ ] Label UFI = PCN UFI.
- [ ] UFI corresponds to the correct formulation.
- [ ] Product name = PCN product name.
- [ ] Classification = approved PCN classification.
- [ ] Signal word = approved classification.
- [ ] Pictograms = approved classification.
- [ ] H-statements = approved classification.
- [ ] Relevant P-statements = consistent.
- [ ] Supplemental hazard information = consistent.
- [ ] SDS UFI = PCN UFI.
- [ ] SDS product name = PCN product name.
- [ ] Packaging = PCN packaging.
- [ ] Product use = PCN use.
- [ ] Product is not placed on the relevant market before the applicable notification obligation has been satisfied.

---

# PHASE 24 — PCN CHANGE CONTROL

Create a PCN impact assessment whenever any of the following changes:

- [ ] Composition.
- [ ] Component concentration.
- [ ] Addition/removal of component.
- [ ] MiM.
- [ ] MiM supplier.
- [ ] MiM UFI.
- [ ] UFI.
- [ ] Product/trade name.
- [ ] Product variant.
- [ ] Classification.
- [ ] Hazard statement.
- [ ] Pictogram.
- [ ] Signal word.
- [ ] Supplemental hazard information.
- [ ] Toxicological information.
- [ ] pH.
- [ ] Physical state.
- [ ] EuPCS.
- [ ] Intended use.
- [ ] Consumer/professional/industrial use.
- [ ] Packaging.
- [ ] Packaging size.
- [ ] Market/country.
- [ ] Language.
- [ ] Emergency contact.
- [ ] Legal Entity.
- [ ] Other PCN information.

Determine whether the change requires:

- [ ] No PCN action.
- [ ] PCN update.
- [ ] New notification following significant change of composition.
- [ ] New UFI.
- [ ] Label update.
- [ ] SDS update.
- [ ] Additional market notification.

---

# APPENDIX A — CONTROLLED LABELLING REFERENCE

## Source hierarchy

For controlled labelling data, use the following hierarchy:

**1. Current ECHA PCN Picklist Values**

Use the current PCN Version 8 Excel/XML picklist package as the source for the **actual selectable PCN values**.

ECHA explicitly states that the Version 8 package contains the picklist values in both Excel and XML format.

**2. ECHA Guide to PCN Format**

Use the Guide to understand:

- which fields are picklists;
- which fields are mandatory;
- which fields are repeatable;
- when `Additional text` is permitted;
- how editable portions are entered.



**3. CLP Regulation / applicable amendments**

Use the CLP legislation as the legal source for the underlying classification and labelling requirements.

**4. IUCLID implementation**

Use the actual current IUCLID PCN working context to select the controlled value.

### Rule

**Never build a controlled PCN labelling list solely from a previous PCN, SDS, label, internet source or old SOP.**

The current ECHA PCN picklist should be treated as the authoritative technical source for what can be selected in the PCN format.

---

# APPENDIX B — COMMON PCN MISTAKES & PREVENTION

| Mistake | Prevention |
|---|---|
| Wrong Legal Entity UUID | Perform UUID comparison against ECHA Submission Portal before submission. |
| Correct UUID but wrong country/name | Perform Legal Entity UUID + country + name check. |
| Reusing PCN number incorrectly | New initial notification gets the appropriate new PCN number; maintain notification history. |
| Confusing PCN number, dossier UUID and submission ID | Record all three separately. |
| Treating all components identically | Assess each component under Annex VIII concentration rules. |
| Forcing concentration ranges to midpoint 100% | Use formulation and Annex VIII logic; midpoint is an internal check, not a reason to manipulate ranges. |
| Missing component of major concern | Perform formal component-by-component assessment. |
| Incorrect MiM treatment | Establish whether composition is known/partially known/unknown and apply the appropriate MiM structure. |
| Assuming MiM UFI replaces composition information | Verify applicable MiM reporting requirements. |
| Wrong UFI | Check UFI against formulation and product. |
| Same UFI used for different compositions | Perform formulation/UFI reconciliation. |
| Wrong EuPCS | Assess actual intended use, not merely product name. |
| Incorrect pH justification | Use the controlled PCN justification where applicable. |
| pH entered without required solution concentration | Check the pH record completely. |
| Copying SDS Section 11 verbatim without review | Ensure toxicological information is appropriate for PCN/emergency response. |
| Leaving one target-language free-text field blank | Perform language-by-language review. |
| Manually typing H/P/EUH wording | Use current controlled PCN picklists. |
| Using old picklist wording | Check against current ECHA PCN Version 8 picklist. |
| Putting the complete H-statement into Additional text | Enter only the editable component. |
| Incorrect separator in Additional text | Apply the PCN-required `|` structure where multiple editable elements are required. |
| Selecting a valid H-statement that does not correspond to classification | Perform classification-to-labelling reconciliation. |
| Missing supplementary hazard statement | Check CLP Annex III Part 2 and the PCN picklist. |
| Assuming IUCLID validation means submission is complete | Perform portal-level review as well. |
| Ignoring quality warnings | Investigate/document every warning. |
| Not performing second-person review | Mandatory four-eyes check before dossier creation/submission. |
| No post-submission change control | Link PCN to formulation/product change-control process. |

---

# APPENDIX C — CONTROLLED DOCUMENTS TO MAINTAIN

Maintain the following controlled references with the SOP:

- [ ] Current ECHA **PCN Format** package.
- [ ] Current **PCN Picklist Values – Excel**.
- [ ] Current **PCN Picklist Values – XML** where required for IT/database purposes.
- [ ] Current **Guide to PCN Format**.
- [ ] Current **PCN Data Model**.
- [ ] Current **PCN Validation Rules**.
- [ ] Current IUCLID 6 release/version.
- [ ] Current applicable CLP Regulation.
- [ ] Current CLP ATP amendments.
- [ ] Current Annex VIII guidance/implementation information.
- [ ] Current EuPCS version.
- [ ] Current ECHA UFI guidance.
- [ ] Internal formulation/BOM procedure.
- [ ] Internal SDS/classification procedure.
- [ ] Internal PCN change-control procedure.

**Document owner:** __________________

**Effective date:** __________________

**Next review date:** __________________

**PCN format version:** __________________

**IUCLID version:** __________________
