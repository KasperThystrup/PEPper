# PEPper
When setting up metadata for projects, there may be several tedious setup steps. One approach to minimizing unnescesary setup time, is to collect metadata alongside sample file data into simple relational sheet. Portable Encapsulated Projects is a framework which supports this alongside extra inferrable metadata wrangling, that is, changes can be applied to metadata without physically chaning the metadata sheet.

This software aims at building a PEP from a directory as well as supporting optional implementation of a metadata sheet.

PEP setups can be used downstream as input for workflows, mitigating the need for setting up workflows indidivudally.

In addition, PEPper will include an option to build a project structure folder containing the relevant schemas, alongside a folder contaning symbolic links to relevant sample files.

# Concepts to be implemented
[] Will support .fasta and .fastq.gz
[] Automatic build of Project configuration, sample- and subsample-sheets
[] Build project folder support
