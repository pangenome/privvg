# privvg: differential privacy on variation graphs (vgteam)

Vgteam is pioneering privacy-preserving variation graphs, that allow to capture complex models and aggregate data resources with formal guarantees about the privacy of the individual data sources from which they were constructed. Variation graphs relate collections of sequences together as walks through a graph. They are traditionally applied to genomic data, where they support the compression and query of very large collections of genomes.

See also:

* [Project BLOGs](https://privvg.github.io/)
* [Early prototype in Racket](https://github.com/Gavlooth/DP_WIP)
* [What is differential privacy?](http://eti.mit.edu/what-is-differential-privacy/)

## Privacy enhanced search within e.g. genome data sets

The project applies formal models of differential privacy to build variation graphs which do not leak information about the individuals whose data was used to construct them. For genomes, the techniques allow us to extend the traditional models to include phenotype and health information, maximizing their utility for biological research and clinical practice without risking the privacy of participants who shared their data to build them. For geolocation trajectory data, people can share data in the knowledge that their social graph is not exposed. The tools themselves are not limited to the above use cases, and open the doors to many other types of applications both online (web browsing histories, social media usage) and offline. .

## Acknowledgements

This project was funded through the [NGI0 Discovery Fund](https://nlnet.nl/project/VariationGraph/), a fund established by NLnet with financial support from the European Commission's Next Generation Internet programme, under the aegis of DG Communications Networks, Content and Technology under grant agreement No 825322.

## LICENSE

This software is distributed under the free software [MIT LICENSE](./LICENSE).
