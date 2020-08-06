---
name: “MMA Feature request”
about: Suggest an idea for this project
title: ' '
labels:  "MMA feature request"
assignees: ' '

---

Requirement: any new feature request must have a data review done prior to filing. Consult w. engineering for that review.

## Request Type:
Add new - (include the build - Nightly, Beta, Release)
-or-
Update existing

## Provide the information requested below depending on the type of request new vs. update. 

### For new requests, include all information. 

### For existing items, include only the events, attributes or deeplink names and (important) the original github issue filed for the item

#### Event name detail and technical definition:

Event name: (e.g. E_FxA_New_Signup)
Event detail: (e.g. A new Firefox accounts sign up is completed    )
Technical definition: (e.g. Fired when the user completes the signup process to new account, but has not yet logged in.)

#### Attribute name and definition:

Attribute name: (e.g. Add Ons Installed)
Attribute definition:  (e.g. List of add-ons the user has installed when the user successfully adds an add-on to their browser)

#### Deeplink description and rationale

Deeplink description: (e.g. Link to Set Default Browser settings)
Rational:  (e.g. Increasing retention)
Deeplink (proposed): (e.g. fenix://make_default_browser)

#### Github issue: (for existing feature requests)

### Tasks
- [ ] Add mapping for request in code
- [ ] Undergo data review
- [ ] Add test to show it's being fired (e.g. specified by #11210)
- [ ] Document in Fenix code
- [ ] Test end-to-end and validate attribute in Leanplum
