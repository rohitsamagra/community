# Table of contents

## Learn

* [Introduction](README.md)
* [Verifiable Credentials](learn/verifiable-credentials/README.md)
  * [What issues will Verifiable Credentials address?](learn/verifiable-credentials/what-issues-will-verifiable-credentials-address.md)
  * [What are the key roles in Verifiable Credentials?](learn/verifiable-credentials/what-are-the-key-roles-in-verifiable-credentials.md)
  * [What are the components of Verifiable Credentials?](learn/verifiable-credentials/what-are-the-components-of-verifiable-credentials.md)
  * [What are the benefits of Verifiable Credentials?](learn/verifiable-credentials/what-are-the-benefits-of-verifiable-credentials.md)
  * [Digital Credentials vs Verifiable Credentials](learn/verifiable-credentials/digital-credentials-vs-verifiable-credentials.md)
  * [QR code vs Verifiable QR code](learn/verifiable-credentials/qr-code-vs-verifiable-qr-code.md)
  * [Use Cases](learn/verifiable-credentials/use-cases.md)
* [Electronic Registries](learn/electronic-registries/README.md)
  * [Evolution of Electronic Registries](learn/electronic-registries/evolution-of-electronic-registries.md)
  * [What issues will Electronic Registries address?](learn/electronic-registries/what-issues-will-electronic-registries-address.md)
  * [Benefits of Electronic Registries](learn/electronic-registries/benefits-of-electronic-registries.md)
  * [Registry vs Database](learn/electronic-registries/registry-vs-database.md)
  * [Design Principles](learn/electronic-registries/design-principles.md)
  * [Use Cases](learn/electronic-registries/use-cases.md)
* [Sunbird RC Overview](learn/readme/README.md)
  * [Features](learn/readme-1/features.md)
  * [Core Registry Verbs](learn/readme-1/core-registry-verbs.md)
  * [Why do we need Sunbird RC?](learn/readme/why-do-we-need-sunbird-rc.md)
  * [What Sunbird RC is and what it's not? (WIP)](learn/readme/what-sunbird-rc-is-and-what-its-not-wip.md)
  * [Core Capabilities](learn/readme/core-capabilities.md)
  * [Technical Specification Draft](learn/readme-1/technical-specification-draft.md)
  * [Workflows](learn/readme/workflows.md)
  * [High level architecture](learn/readme-1/high-level-architecture.md)
  * [High level architecture](learn/readme-1/high-level-architecture-1.md)
* [Sunbird RC in action](learn/sunbird-rc-in-action/README.md)
  * [Implementations (Work in Progress)](learn/sunbird-rc-in-action/implementations-work-in-progress.md)
  * [Possibilities](learn/sunbird-rc-in-action/possibilities.md)

## Use

* [Technical Requirements](use/infrastructure-requirements.md)
* [Technical Requirements](use/technical-requirements.md)
* [Releases](use/releases.md)
* [Setup the Backend](use/setup-the-backend.md)
* [Setup the Frontend](use/setup-the-frontend.md)
* [Leveraging Existing data stores](use/leveraging-existing-data-stores-directories.md)
* [SSO with existing systems](use/sso-with-existing-systems/README.md)
  * [Digilocker Meripehchaan SSO](use/sso-with-existing-systems/digilocker-meripehchaan-sso.md)

## Developer Documentation

* [Generic OAuth Configuration](developer-documentation/generic-oauth-configuration.md)

## Developer Documentation

* [Installation Guide](developer-documentation-1/installation-guide/README.md)
  * [Registry CLI](developer-documentation-1/installation-guide/installation-guide/README.md)
    * [Setup A Registry Instance](developer-documentation-1/installation-guide/installation-guide/setup-a-registry-instance.md)
  * [Manual installation through docker-compose](developer-documentation-1/installation-guide/manual-installation-through-docker-compose.md)
  * [Production setup through Helm](developer-documentation-1/installation-guide/production-setup-through-helm.md)
* [Introduction To Schemas](developer-documentation-1/introduction-to-schemas.md)
* [Creating Your Own Schemas](developer-documentation-1/creating-your-own-schemas.md)
* [Schema Configuration](developer-documentation-1/schema-configuration.md)
* [Using The APIs](developer-documentation-1/using-the-apis.md)
* [Create Schemas With Custom Password](developer-documentation-1/create-schemas-with-custom-password.md)
* [Admin Portal](developer-documentation-1/admin-portal/README.md)
  * [Login](developer-documentation-1/admin-portal/login.md)
  * [Get Started](developer-documentation-1/admin-portal/get-started/README.md)
    * [Create Schema](developer-documentation-1/admin-portal/get-started/create-schema.md)
    * [Attestation Workflows (WIP)](developer-documentation-1/admin-portal/get-started/attestation-workflows-wip.md)
    * [VC Template](developer-documentation-1/admin-portal/get-started/vc-template/README.md)
      * [Custom VC Template (WIP)](developer-documentation-1/admin-portal/get-started/vc-template/verifiable-credential-template-wip.md)
    * [Ownership (WIP)](developer-documentation-1/admin-portal/get-started/ownership-wip.md)
    * [Publish (WIP)](developer-documentation-1/admin-portal/get-started/publish-wip.md)
  * [Dashboard](developer-documentation-1/admin-portal/dashboard.md)
* [Configuration](developer-documentation-1/configuration.md)
* [Developer Setup](developer-documentation-1/developer-setup.md)
* [VC Verification Module](developer-documentation-1/vc-verification-module.md)
* [Audit Configuration](developer-documentation-1/audit-configuration.md)
* [Custom Keycloak Build](developer-documentation-1/custom-keycloak-build.md)
* [Metrics](developer-documentation-1/metrics.md)
* [Digilocker Integration](developer-documentation-1/digilocker-integration.md)
* [Custom QR Code design](developer-documentation-1/custom-qr-code-design.md)
* [Notifications Configuration](developer-documentation-1/notifications-configuration.md)
* [View Templates Configuration](developer-documentation-1/view-templates-configuration.md)
* [Generic Identity And Access Management](developer-documentation-1/generic-identity-and-access-management.md)
* [Backup and Restore](developer-documentation-1/backup-and-restore/README.md)
  * [PostgreSQL](developer-documentation-1/backup-and-restore/postgresql/README.md)
    * [SQL Dump](developer-documentation-1/backup-and-restore/postgresql/sql-dump.md)
    * [File System Level Backup](developer-documentation-1/backup-and-restore/postgresql/file-system-level-backup.md)
    * [Continuous Archiving and Point-in-Time Recovery (PITR)](developer-documentation-1/backup-and-restore/postgresql/continuous-archiving-and-point-in-time-recovery-pitr.md)
  * [Cassandra](developer-documentation-1/backup-and-restore/cassandra/README.md)
    * [Snapshot-based backup method](developer-documentation-1/backup-and-restore/cassandra/snapshot-based-backup-method.md)
    * [Incremental backup method](developer-documentation-1/backup-and-restore/cassandra/incremental-backup-method.md)
    * [Data Restore](developer-documentation-1/backup-and-restore/cassandra/data-restore.md)
* [Frontend Configurations](developer-documentation-1/frontend-configurations.md)
* [Frontend - Proxy configuration](developer-documentation-1/frontend-proxy-configuration.md)

## API Reference

* [Registry](api-reference/registry/README.md)
  * [Create An Entity](api-reference/registry/create-an-entity.md)
  * [Invite An Entity](api-reference/registry/invite-an-entity.md)
  * [Generate token](api-reference/registry/authenticating-as-an-entity.md)
  * [Generate admin token](api-reference/registry/generate-admin-token.md)
  * [Get An Entity](api-reference/registry/get-an-entity.md)
  * [Get An Entity By Id](api-reference/registry/get-an-entity-by-id.md)
  * [Update An Entity](api-reference/registry/update-an-entity.md)
  * [Create A Property Of An Entity](api-reference/registry/create-a-property-of-an-entity.md)
  * [Update A Property Of An Entity](api-reference/registry/update-a-property-of-an-entity.md)
  * [Revoke a Credential](api-reference/registry/create-a-property-of-an-entity-1.md)
  * [Delete An Entity](api-reference/registry/delete-an-entity.md)
* [Schema](api-reference/schema/README.md)
  * [Create Schema](api-reference/schema/create-schema.md)
  * [Get Schema](api-reference/schema/get-schema.md)
  * [Update Schema](api-reference/schema/update-schema.md)
  * [Delete Schema](api-reference/schema/delete-schema.md)
  * [Publish A Schema](api-reference/schema/publish-a-schema.md)
* [Attestation API](api-reference/attestation-api/README.md)
  * [Raise An Attestation](api-reference/attestation-api/raise-an-attestation.md)
  * [Get Attestation Certificate](api-reference/attestation-api/get-attestation-certificate.md)
* [Claims API](api-reference/claims-api/README.md)
  * [Get All Claims](api-reference/claims-api/get-all-claims.md)
  * [Get Claim by ID](api-reference/claims-api/get-claim-by-id.md)
  * [Attest A Claim](api-reference/claims-api/attest-a-claim.md)
* [Discovery API](api-reference/discovery-api/README.md)
  * [Search An Entity](api-reference/discovery-api/search-an-entity.md)
* [File Storage API](api-reference/file-storage-api/README.md)
  * [Upload A File](api-reference/file-storage-api/upload-a-file.md)
  * [Get Uploaded File](api-reference/file-storage-api/get-uploaded-file.md)
  * [Delete A File/ Multiple Files](api-reference/file-storage-api/delete-a-file-multiple-files.md)
* [Bulk Issuance API](api-reference/bulk-issuance-api/README.md)
  * [Get Sample Template](api-reference/bulk-issuance-api/get-sample-template.md)
  * [Upload CSV](api-reference/bulk-issuance-api/upload-csv.md)
  * [Get all uploaded Files](api-reference/bulk-issuance-api/get-all-uploaded-files.md)
  * [Download a Report File](api-reference/bulk-issuance-api/download-a-report-file.md)
* [Metrics APIs](api-reference/metrics-apis/README.md)
  * [Get Count](api-reference/metrics-apis/get-count.md)
  * [Get Aggregates](api-reference/metrics-apis/get-aggregates.md)
* [ID Gen APIs](api-reference/id-gen-apis/README.md)
  * [Generate ID](api-reference/id-gen-apis/generate-id.md)
  * [Create ID Format](api-reference/id-gen-apis/create-id-format.md)
* [Encryption APIs](api-reference/encryption-apis/README.md)
  * [Encrypt](api-reference/encryption-apis/encrypt.md)
* [Other APIs](api-reference/other-apis/README.md)
  * [Sign API](api-reference/other-apis/sign-api.md)
  * [Verify API](api-reference/other-apis/verify-api.md)
  * [Swagger JSON API](api-reference/other-apis/swagger-json-api.md)
  * [Health API](api-reference/other-apis/health-api.md)

## Reference Solutions

* [Education](reference-solutions/education/README.md)
  * [Education Ecosystem](reference-solutions/education/education-ecosystem/README.md)
    * [Installation](reference-solutions/education/education-ecosystem/installation.md)
  * [Education Registries](sample-use-cases/edu-registries/README.md)
    * [Installation](sample-use-cases/edu-registries/installation.md)
* [Certificate Issuance](reference-solutions/certificate-issuance/README.md)
  * [Installation(WIP)](reference-solutions/certificate-issuance/installation-wip.md)
  * [User Guide](reference-solutions/certificate-issuance/portal-user-guide.md)
* [eLocker](reference-solutions/elocker/README.md)
  * [High Level Diagram](reference-solutions/elocker/digital-locker.md)
  * [Installation (WIP)](reference-solutions/elocker/installation-wip/README.md)
    * [Frontend Setup E-locker](reference-solutions/elocker/installation-wip/frontend-setup-e-locker.md)
  * [User Guide](reference-solutions/elocker/user-guide.md)
* [Health Registries](reference-solutions/health-registries/README.md)
  * [Organ Registries](reference-solutions/health-registries/organ-registries/README.md)
    * [Frontend Setup](reference-solutions/health-registries/organ-registries/frontend-setup.md)
    * [Backend Setup](reference-solutions/health-registries/organ-registries/backend-setup.md)
    * [User Guide](reference-solutions/health-registries/organ-registries/user-guide.md)
* [Vaccination Platform](sample-use-cases/vaccination.md)
* [Skills & Work Credentials](sample-use-cases/skill-and-work-credentials-platform.md)
* [Govt to Person (G2P)](reference-solutions/govt-to-person-g2p.md)
* [Unified Learners Passport (ULP)](reference-solutions/unified-learners-passport-ulp/README.md)
  * [ULP Capabilities](reference-solutions/unified-learners-passport-ulp/ulp-capabilities.md)
  * [Example Scenario](reference-solutions/unified-learners-passport-ulp/example-scenario.md)
  * [Technical Components (WIP)](reference-solutions/unified-learners-passport-ulp/technical-components-wip.md)
  * [Demo/Sandbox Links (WIP)](reference-solutions/unified-learners-passport-ulp/demo-sandbox-links-wip.md)
  * [Installation Guide (WIP)](reference-solutions/unified-learners-passport-ulp/installation-guide-wip/README.md)
    * [Frontend Setup](reference-solutions/unified-learners-passport-ulp/installation-guide-wip/frontend-setup.md)
    * [Installation through docker-compose](reference-solutions/unified-learners-passport-ulp/installation-guide-wip/installation-through-docker-compose.md)
    * [Dummy records setup for refrence](reference-solutions/unified-learners-passport-ulp/installation-guide-wip/dummy-records-setup-for-refrence.md)

## Links

* [Source Code](https://github.com/Sunbird-RC/)
* [Releases & Changelogs](https://github.com/Sunbird-RC/sunbird-rc-core/releases)
* [Website](https://sunbirdrc.dev)
* [Roadmap](https://github.com/orgs/Sunbird-RC/projects/16/views/1)
* [Reference links](links/reference-links.md)
* [Design](links/design.md)

## Community

* [Discussion Forum](community/discussions.md)
* [Contributing](engage/contributing.md)
* [Contributors](community/contributors.md)
* [Contribution Guidebook](community/contribution-guidebook.md)
* [Code of Conduct](engage/code-of-conduct.md)
* [Community Events](engage/community-events.md)
* [Status By Track](engage/status-by-track.md)

## HELP

* [Roadmap](help/roadmap.md)
* [FAQs](help/faqs.md)
* [Glossary](help/terminology.md)
