# Automating Domain-Driven Design

[![CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-informational?logo=creativecommons&logoColor=white)
](https://creativecommons.org/licenses/by-nc/4.0/)

This repository contains the supplementary data for our paper "Automating Domain-Driven Design: Experience with a Prompting Framework".

## Adopting the Prompting Framework

The framework can be adopted with any LLM, but we recommend using a large one with sufficient reasoning capabilities (100b+ Parameters).
To use this framework, you need a LLM-readable file - for example, markdown or pdf - contatining comprehensive requirements for the system you want to build.

1. Insert the system prompt into the LLM-tool of your choice.
2. Insert the prompt for Step 1 and attach the requirements file.
3. Answer the LLM’s questions and refine the output until it is accurate.
4. Proceed with the consecutive steps in the same manner.

## Requirements files

The [requirements](/requirements/) in this repository have been used to evaluate the prompting framework in a case study. For the full details of the case study, please read the original paper.
The requirements describe the two software systems [SecuRooms](/requirements/SecuRooms.md) and [SecuMails](/requirements/SecuMails.md), developed at [FTAPI Software GmbH](ftapi.com). The actual requirements at FTAPI are suspect to change and might not match these requirements exactly in the future.

## Evaluation

The prompting framework was evaluated in structured interviews with experts from FTAPI. For privacy reasons, the full interview transcripts are not included, but the [structure of the interview](/interview-structure.md) is available.