# DIOT-Template

This repository is the reference design baseline for Sinara-DIOT hardware projects.

## Purpose

The template was created to improve consistency between Sinara-DIOT modules
and to provide a single place where common system design decisions can be maintained
and tracked.

It contains system-level solutions and standardized design elements shared
between modules, including common interfaces, connectors, power-related
circuitry and other reusable parts of the DIOT architecture.

Using the template helps to:

- keep common parts of different Sinara-DIOT modules consistent,
- avoid independently reimplementing the same system-level solutions,
- propagate common improvements and design changes between projects,
- simplify development of new DIOT modules,
- simplify redesign of existing EEM modules for the DIOT platform,
- provide a common reference for schematic and PCB organization.

Common changes that may affect multiple Sinara-DIOT modules should preferably
be introduced in this repository first and then propagated to individual
projects.

## Template version

Projects based on this template should specify the template version they are
compatible with using the `P_template_version` project parameter.

This makes it possible to track which version of the common DIOT design
baseline was used when a particular project was created or updated.