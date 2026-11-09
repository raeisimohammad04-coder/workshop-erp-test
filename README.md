# Workshop ERP — Test Repository

This repository is being prepared for a free, temporary iPhone-only test environment.

## Source package

Upload the supplied `workshop-erp-v14.zip` archive to the repository root. The archive contains the version 0.14 source tree under `workshop-erp-v14/src/`.

## Important

Version 0.14 has passed archive integrity and static checks only. It has not yet passed a full PostgreSQL runtime, integration, or end-to-end test. Do not use it for real financial records.

## Temporary test setup

After the archive is uploaded, open a GitHub Codespace for this repository, extract the archive, and follow `src/README.md`. A PostgreSQL service and environment secrets will be required; never commit `.env` or real credentials.
