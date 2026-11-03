# SBC Parallel

Compare an existing business workflow with a proposed change under the same incoming workload. Parallel shows where queues form, how much work finishes, and what remains unfinished when task times or staffing change.

**1.0.1 · Windows x64 · Starkey Bridge Consulting LLC**

## Working with a process

Start with quotations, customer inquiries, order fulfillment, client onboarding, or a custom process. Set up two to six steps, then adjust task time, staff, allocated hours, variation, or bypass rules for each version.

The comparison includes throughput, waiting time, mean and P90 turnaround, utilization, and unfinished-work age. Demand surges and staff absence help test a proposal under pressure. Twenty paired seeds show how the comparison varies across sampled workloads.

Projects stay on the computer. A local library holds up to one hundred projects, with undo/redo, scenario files, workspace backups, and PDF or CSV reports.

## Implementation

JavaScript and Electron, with a background calculation worker and atomic local saves. Simulations use reproducible seeds; exported reports include the inputs and model reference.

The model uses sequential FIFO queues and dedicated staff pools. Results depend on the assumptions entered and should be read alongside unfinished work, rather than treated as measured savings.

## Build status

The source has 110 unit tests covering the simulation, independent reference cases, file validation, reports, and persistence. Desktop, offline, and packaging checks are recorded with the source.

Installer and portable Windows builds are packaged. Native Windows launch, installation, dialogs, and display-scaling checks remain pending. The application runs offline without an account, subscription, or hosted API.

Commercial source is private.

[Portfolio](../README.md) · [Publisher](https://starkeybridgeconsulting.com)
