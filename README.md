# Data Management for protoDUNE
## Overview
### Single and Dual-Phase detectors

This is repository contains documents for a proposed raw data managment system for the protoDUNE detectors, which are scheduled to take data with CERN SPS beams in late 2018:
* NP02 - the dual-phase detector
* NP04 - the single-phase detector

One of the main drivers behind the design of the data management system for protoDUNE is to use synergies between the two experiments, increase robustness of the overall solution and minimize the effort required for the design, prototyping, deployment and operations.

### EOS and CASTOR
EOS is a high-performance distributed system at CERN. It is the centerpiece of the raw data management design for protoDUNE, which is in line with the practices of the LHC experiments. Among it's many features is a "native" XRootD interface which allows for simplified access to data over the network.

CASTOR is the tape storage system.

## Documents in this repository
* *protoDUNE-DMS-design.tex is the MAIN document*. It describes a specific design of the data management system based on deployment and reuse of F-FTS, which is a data management system supported by FNAL.
* The file pdrdm.tex and the two charts that go in it,
"flow" and "state", is an initial note evaluating basic design requirements.

* The file spbf.tex is work in progress and will describe the Single-Phase protoDUNE Disk Buffer Farm



