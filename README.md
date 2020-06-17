# Eclipse Arrowhead Core RFC Repository

__This repository is a proposal for how the RFC process could function in Eclipse Arrowhead. It has not yet been ratified by the project.__

Non-trivial changes to existing Eclipse Arrowhead core services and systems, or even the creation of new core services and systems, have to be approved by the Arrowhead community before implementation to ensure that those changes do not interfere with the existing goals and aims of the community. This repository provides a way for such changes to be (1) discussed, (2) formalized and then (3) approved or rejected by the community.

## Change Discussions (PRE-RFCs)

When the need for a change has been identified, start by creating an issue in this respository about the change you want to make. These issues can be referred to as PRE-RFCs, meaning that they are intended to lead to the creation of formalized proposals to be presented to the wider Arrowhead community. Make as many as possible from within the project that could have interest in the issue aware about it. The point of the dicussion that will take place in the issie is to (1) determine the interest of the Arrowhead community in committing to the change and to (2) make sure that it superficially contributes to the quality and usefulness of Eclipse Arrowhead. If the discussion starts to settle on that a change is indeed needed, one person is to be appointed by the participants in the discussion to make a formal RFC. The apointee will typically be the one that created the PRE-RFC in the first place. The only purpose of the appointment is to avoid the situation of having two RFCs with describing the same change. 

## Change Proposals (RFCs)

When a formalized proposal, or _Request For Comments_ (RFC), can be made, it is to be created by (1) forking this reposotory, (2) creating a new file in the [`/proposals`](/proposals) folder with a name adhering to the specification below and then making a pull request. The pull request containing the RFC will eventually be advertised to the Arrowhead community at large, which will be asked to comment it.

### RFC File Naming Convention

RFC file names must start with four zeroes, a dash, and then consist of only lower-case ASCII characters, numbers and dashes. The name must end with `.md`. The four digits are changed by the person responsible for merging the pull request if the RFC is approved. Examples of valid names are `0000-make-version-field-in-service-registration-message-mandatory.md` or `0000-new-safety-integration-service.md`.

## Community Ratification

This details of this step have not been decided yet.
