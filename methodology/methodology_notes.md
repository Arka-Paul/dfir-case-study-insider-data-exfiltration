Investigation Methodology
Evidence Creation

A controlled Windows 10 virtual machine was used to simulate realistic insider activity within a corporate workstation environment. Activities were intentionally performed to generate artefacts consistent with data handling, concealment, and post-incident behaviour.

Forensic Acquisition

The virtual machine disk was acquired using FTK Imager and preserved in E01 format. Cryptographic hash values were generated and verified at acquisition to ensure evidence integrity.

Evidence Handling

All analysis was conducted on the forensic image in read-only mode. No modifications were made to the original evidence image during examination.

Analysis Workflow

The investigation followed a structured DFIR approach:

Initial survey and artefact identification

Timeline reconstruction and correlation

Artefact classification across Reconnaissance, Record, and Aftermath phases

Evidential reasoning and limitation assessment

Reporting aligned with professional DFIR standards

Reporting

Findings were documented with emphasis on:

What artefacts demonstrate

What they do not prove

Attribution constraints and evidential limitations

Sensitive details were sanitised prior to publication.