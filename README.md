# sdk-updates
Updates on SDK status and feature discussion

## Overall Casper Client SDKs Update
**Status date: 04-Jun-2024**

| SDK        | Latest Updates                                                                                                                                                   | Current Casper-Node<br>Protocol Alignment | Upcoming Casper-Node<br>Protocol Alignment | Condor Release Status | Planned Devnet Release Date | Planned Testnet Release Date |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------- | ------------------------------------------ | --------------------- | --------------------------- | ---------------------------- |
| JavaScript | JavaScript SDK Condor updates are in progress.<br>Internal testing will commence after the updates.<br>Documentation and list of changes by the end of the week. | 1.5.6                                     | Condor                                     | Testing               | 07-Jun-24                   |                              |
| Go         | Updates in progress, testing ongoing.<br>Aim for backward compatibility with Casper 1.5.6. Internal discussion on approach concluded.                            | 1.5.6                                     | Condor                                     | Testing               | TBC                         |                              |
| C#         | Updates in progress, testing ongoing.<br>Aim for backward compatibility with Casper 1.5.6. Internal discussion on approach concluded.                            | 1.5.6                                     | Condor                                     | Testing               | TBC                         |                              |
| Rust       | Updates pending technical discussions with CTO (Medha Parlikar).<br>Status to be updated once a consensus is reached.                                            | 1.5.6                                     | Condor                                     | TBC                   | TBC                         |                              |
| Python     | Updates will start soon                                                                                                                                          | 1.5.6                                     | Condor                                     | Development           | TBC                         |                              |
| PHP        | Not currently on the plan; needs to be added and discussed in future meetings.                                                                                   | 1.5.6                                     | Condor                                     | TBC                   | TBC                         |                              |
| C++        | Not currently on the plan; needs to be added and discussed in future meetings.                                                                                   | 1.5.6                                     | Condor                                     | TBC                   | TBC                         |


## Condor Release & Testing Updates
- Testing RC2 on DevNet; broader audience access expected next week.
- Internal SRE testing ongoing on the latest Condor feature branch.
- Indicative release date for RC2: Week commencing 10th June 2024.

## AOB
### Dockerized NCTL image for Condor 2.0
- MAKE Services (David) shared a script for building a local NCTL image for Casper 2.0.
- Dokerized NCTL with Condor changes is available for teams to test their changes locally.
- Useful for teams to test locally, reducing load on DevNet.

### Actions/Next Steps
- Schedule a session with JS SDK Maintainer(Jan Hoffman) for a detailed overview and Q&A once JavaScript SDK updates are completed. - Devendran M
- Gather information on teams using various SDKs. - Stormeye
- Prepare a detailed diff between current and RC versions for documentation.- Jan Hoffman