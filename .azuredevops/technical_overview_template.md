Detailed Technical Design: \<Component\>
---


Document ID: DHF\<Doc-ID\>

Document Revision: \<Revision\>

Table of Contents 
=================

[1 Document Introduction](#document-introduction)

[1.1 Purpose](#purpose)

[1.2 Scope](#scope)

[1.3 References](#references)

[1.4 Terms, Definitions and Abbreviations](#terms-definitions-and-abbreviations)

[2 Overview and Architecture Views](#overview-and-architecture-views)

[2.1 Design Overview](#design-overview)

[2.2 Architecture Views](#architecture-views)

[3 Design Details](#design-details)

[3.1 Sub-Components](#sub-components)

[3.2 Safety classification](#safety-classification)

[3.3 Detailed Description](#detailed-description)

[3.4 Internal Interfaces](#internal-interfaces)

[3.5 Material](#material)

[4 Allocation of Specifications](#allocation-of-specifications)

[5 Document History](#document-history)


Document Introduction
=====================

This is the how part of the component implementation.

Instructions for preparing this document:

-   Text in blue italics is for guidance or instructional purposes and
    is to be deleted and/or overwritten by the program-specific
    information.

    -   This blue text is written in the style 'Instructions for
        writer'. (Styles can be changed in the Home tab in Word.
        Standard text is normal; chapter headings are marked 'Heading x'

    -   If needed, for the recalling of this instruction, please refer
        to the empty template

-   Fill Document author, ID and level and revision on the header page;
    do not remove the boxes (author, status and keywords). The header
    and footer on the pages will be automatically updated.

-   The information on the front page (document number, revision level,
    etc.) of the template must be replaced with the information of the
    document

-   When updating, if a section is not applicable: Do not delete the
    section. Instead put N/A and a rationale why it is not applicable.

-   For MR Therapy, check for reviewers and approver in QFW1012.01:
    Document Authorization Matrix

Purpose
-------

This document describes the detailed technical design of the component
Detailed Technical Design: \<Component\>.

Scope
-----

The scope of this document is the detailed technical design of the
component Detailed Technical Design: \<Component\>.

References 
----------

-   Only add references that are really used as an input in this
    document.

-   Preferably use a small description between brackets as the
    reference, it is allowed to use only a number.

-   Include document ID's, including the revision of that document

-   Do not refer to lower level documents

 | reference | Title of document | id | revision |
 |-----------|-------------------|----|----------|
 |           |                   |    |          |
 

Terms, Definitions and Abbreviations
------------------------------------

Only those specific to this document. The Handbook contains an overview
of general terms, definitions and abbreviations.

| term | explanation |
|------|-------------|
| Abbr | Abbreviation |
             

Overview and Architecture Views
===============================

Design Overview
---------------

Provide a brief description of the subject.

If needed, position the subject in the product architecture or include a
reference of the high level technical Design.

Architecture Views
------------------

Describe, if applicable, the architectural views relevant to clarify the
design of the subject and to provide guidance for detailing.

Examples of architecture views

-   Functional View

-   Interface View

-   Physical View

-   Deployment View

-   Mechanical View

-   Electrical View

-   Hardware View

-   Software View

-   Usage View

-   Network View

-   Interaction View

-   Communication/process View

-   Code Distribution View

-   Events View

-   Data Storage View

Add for each architecture view in scope a subsection to detail the view.

Design Details
==============

Provide, as starting point for design teams, for each sub-component (if
applicable) / interface the required functionality, technical choices
(hardware / software /mechanical / electrical) and other design
constraints.

Sub-Components
--------------

This section is only necessary in case the component is decomposed in
sub-components.

Specify all sub-components of the component, containing a description of
its function, implementation in software or hardware, the interfaces,
dependencies and used resources.

Safety classification
---------------------

This section shall contain the safety classification for the component
as a whole and the safety classification for each specified
sub-component (if applicable).

For SW this an A, B or C according IEC 62304. For HW list the known
HAZARDS from the RMM and the basic safety clauses from IEC.

Detailed Description
--------------------

Describe the detailed design space for the subject. Breakdown and
provide for each component the detailed design space including a
description of its function, specification allocation, implementation in
software or hardware, the interfaces, dependencies and used resources.

The following design aspects can be considered:

-   Hardware

    -   Design entities, e.g. Printed Circuit Boards, Mechanics

    -   Performance Benchmarks and Impact

    -   Maintainability / Extensibility

    -   Thermal behavior

    -   Electrical behavior

    -   Mechanical behavior

    -   Power requirements

    -   Cooling requirements

    -   EMC/EMI requirements

    -   Housing / Casing / Covering

    -   Controls

    -   Input / Output modules

    -   Timers and timing diagrams

-   Software

    -   Technologies

    -   Non-Philips MR Software (SOUP, COTS)

    -   Installation

    -   Configuration

    -   Safety classification

    -   Computer Resource Usage and Impact

    -   Performance Benchmarks and Impact

    -   Process View & Boot Impact

    -   Maintainability / Extensibility

    -   Logging, retrieving, and storing data

    -   Exception handling

    -   Interrupt handling

    -   Self-test

    -   State machines

    -   Algorithms

    -   User authentication

    -   Privacy & Security

If the component is decomposed in sub-components, indicated per
sub-component functionality and applicable design constraints (might be
generic).

Internal Interfaces
-------------------

Describe the detailed design space for the internal interfaces within
the architecture.

For business model services, focus here on all interfaces above "the
line of visibility".

Per interface describe the used protocol and/or physical deployment

Material
--------

Optional chapter if needed describe material needed, e.g. cable between
A & B. In case of none, delete this section entirely.

Allocation of Specifications
============================

In case the component is decomposed in sub-components, embed the
allocation matrix of (functional and non-functional) Component
Specifications to sub-components. This may be generated by ALM.

Document History
================

| Revision | Description |
|----------|-------------|
|   00     | Initial version|