# SISMI
Simulated sequences mimicking integration designed to test virus integration tools

Integration of DNA oncoviruses is reported more and more often as a risk factor in cancerogenesis (1). 
Several bioinformatics tools have been designed to identify virus integration from massively parallel sequencing (MPS) data (2-3). Although these tools are always presented as infallible, validation of their output is required. These tools are offered with small datasets for testing purposes derived from MPS experiments whose viral integration is at best poorly defined. Another option is to use available MPS datasets but, again,  virus integration is not well characterized, if present. 
To overcome this gap, we designed simulated sequences mimicking integration (SISMI) in order to provide well characterized MPS data that can be used to benchmark the virus integration tools. Progressive levels of complexity (SISMI0, SISMI1, SISMI2) have been established with viral sequences mimicking typical insertions found in the literature.
In this directory is stored the quality check of these sequences obtained through FASTQC and SAMTOOLS.
