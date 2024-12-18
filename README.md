## Small Ruminant Lentivirus Extension to Lentivirus-GLUE

<img src="md/sheep-droplet.jpg" align="right" alt="" width="220" />

Welcome to the GitHub repository for **Lentivirus-GLUE-SRLV**: an extension to **[Lentivirus-GLUE](https://github.com/giffordlabcvr/Lentivirus-GLUE)**.

**Small ruminant lentiviruses (SRLVs)** infect sheep and goats, causing chronic, lifelong diseases that impact various organ systems. 

The SRLV extension to SRLV-GLUE incorporates all published SRLV sequence data linked to associated metadata, including information that is sequence-associated (length, publication date); taxonomic (viral genotype, subtype); and isolate-associated (isolation host species, date and location of sampling, isolation source).

The SRLV extension of Lentivirus-GLUE provides functionality for genotyping SRLV sequences via **maximum likelihood**. Genotyping can be performed on any sequence of adequate length (typically >300 nucleotides are required for confident assignment). Any genomic region can be genotyped using the approach implemented in SRLV-GLUE.

Classification is based on maximum likelihood clade assignment (MLCA) as implemented in GLUE. Sequences are classified into genotypes and subtypes defined via phylogenetic analysis of full-length reference genome sequences.

For more details on the SRLV extension project please see the Lentivirus-GLUE **[User Guide](https://github.com/giffordlabcvr/Lentivirus-GLUE/wiki/SRLV-Project-Development-Background)**.

* * * * *

Installation
------------

To install **Lentivirus-GLUE-SRLV**, follow the instructions provided in the **[User Guide](https://github.com/giffordlabcvr/Lentivirus-GLUE/wiki)**.

You can choose between:

-   **[Docker-based installation](https://github.com/giffordlabcvr/Lentivirus-GLUE/wiki/Docker-Installation)** for ease of deployment.
-   **[Native installation](https://github.com/giffordlabcvr/Lentivirus-GLUE/wiki/Native-Installation)** for traditional setup.

Lentivirus-GLUE-SRLV can be installed as a prebuilt database for quick setup or constructed from scratch via (a project build process) for more customization.

* * * * *

## Data Sources

Lentivirus-GLUE-SRLV is constructed using sequence data obtained from [NCBI Nucleotide](https://www.ncbi.nlm.nih.gov/nuccore).

* * * * *

## Contributing

We welcome contributions from the community! If you're interested in contributing to Lentivirus-GLUE-SRLV, please review our [Contribution Guidelines](./md/CONTRIBUTING.md).

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](./md/code_of_conduct.md)

* * * * *

## License

The project is licensed under the [GNU Affero General Public License v. 3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)

* * * * *

## Contact

For questions, issues, or feedback, please open an issue on the [GitHub repository](https://github.com/giffordlabcvr/Lentivirus-GLUE-SRLV/issues).

* * * * *
