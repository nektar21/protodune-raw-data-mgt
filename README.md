# Data Management Documents for protoDUNE
## Overview
This repository contains documents for a proposed raw data managment system and a few online components for the protoDUNE single-phase detector (CERN experiment NP04), which is scheduled to take data with CERN SPS beams in late 2018. The dual-phase detector (NP02) employs a somewhat different approach to data management however there are overlaps in the infrastructure which is mentioned in documentation provided here.

## Documents in this repository
###Data Handling###
* *protoDUNE-DMS-design.tex is the MAIN document*. It describes a specific design of the data management system based on deployment and reuse of F-FTS, which is a data management system supported by FNAL.

* *pdrdm.tex* is an initial note evaluating basic design requirements.

* *spbf.tex* is a stub for the document to describe testing of the Single-Phase protoDUNE Disk Buffer Farm. This probably won't be updated due to the decision to use commercial storage appliance for the buffer, to be procured at CERN.

* *uoob.tex* is a document which explores a few different options for passing the data from the DAQ pipeline to storage and looks at issues such as event interlacing etc.

* *TB_online_June2016* is a report to the DUNE Technical Board

* *neut-buffer.tex* describes a concrete implementation of a xrootd storage cluster at CERN which is a candidate for the single-phase protoDUNE online buffer. Obsolete dut to design decisions as described above.

##Workflow##
Documents whose names starts with "prompt" are related to the prompt processing system for protoDUNE

* the folder *"figures"* contains graphics to all of these documents

## Built PDFs

Go here:

https://dune.bnl.gov/docs/




