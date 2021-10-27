# EGT_SCL: A digital Standard Cell Timing Library for Printed Electrolyte-Gated Tranistor (EGT) Technology 

Motivation:
EGT is an inkjet printed electrolyte-gated transistor technology for developing pritable devices and circuits. The EGT technology is a low-voltage technology
with a typical supply voltage of 1V. The detailed information about the technology is given in R1. We developed the standard cell libraries for the EGT technology
by characterizing the combinational and sequential logic gates. The characteristics of the libraries are reported in our paper Printed Microprocessors [R2], published in ISCA 2020. 

Library Details:
The EGT standard libraries are developed using the compact models of the EGT. Only n-type transistor is available in EGT technology and all logic gates are realized with
tranistor-resisitor logic. The pull-up logic is realized using a resistor and pull-down logic is relaized using an EGFET. 
The ./lib folder contains the standard libraries for the supply voltage ranging from 0.6V to 1.0V. Detailed information about the libraries are prvided in [R3].

[R1] G.C. Marques, D.Weller, A. T. Erozan, X. Feng, M. Tahoori, and J. Aghassi-Hagmann, “Progress Report on ‘From printed electrolyte-gated metal-oxide devices to circuits'”, Advanced Materials, 2019.

[R2] Bleier, N., Mubarik, M. H., Rasheed, F., Aghassi-Hagmann, J., Tahoori, M. B., & Kumar, R. (2020, May). Printed microprocessors. In 2020 ACM/IEEE 47th Annual International Symposium on Computer Architecture (ISCA) (pp. 213-226). IEEE.

[R3] Rasheed, Farhan. Compact Modeling and Physical Design Automation of Inkjet-printed Electronics Technology. Diss. Karlsruher Institut für Technologie (KIT), 2020.
