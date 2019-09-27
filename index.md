## A tool collection for metagenomics
This is a collection of KNIME nodes to detect and characterize foodborne pathogens (EssBAR project).

## How to
### Prerequisites
 - Linux OS (x86_64)
 - KNIME Analytics Platform for Linux (>= version 3.1, but below version 4.0)
 - KNIME Community Extensions - Bioinformatics & NGS -> SeqAn NGS Toolbox (GenericKnimeNodes, NgsToolbox, SeqAn)  
 - KNIME Interactive R Statistics Integration (>= 4.0)
 
### Installation of nodes using the update site  
First add the EssBAR and the Generic KNIME nodes nightly build update site as as repositories within KNIME:
```Help -> Install New Software -> Add```   
  - EssBAR Update site: ```https://www.mi.fu-berlin.de/ess-bar/update_site.p2```
  - GKN nightly build: ```https://abibuilder.informatik.uni-tuebingen.de/archive/openms/knime-plugin/updateSite/nightly/```

![image](images/loaded_update_sites.png)   
First, work with the EssBAR Update site and select all the displayed packages  "EssBAR applications, NGS QC features" for installation and click on Next. Accept the license agreements by checking the corresponding box and click on Finish.
If a security warning pops up click install anyway:  
   
![image](images/unsigned_content-warning.png)    

You will be asked to restart KNIME for changes to take effect. Click on no and continue with the installation of the Generic KNIME nodes with ```Help -> Install New Software```. Now work with the GKN nighly build site, click on the triangle next to 'Uncategorized' and select ```Generic Workflow Nodes for KNIME```. After finishing the installation you need to restart KNIME.   
Afterwards the EssBAR KNIME nodes and GenericKnimeNodes should be visible as Community Nodes in the KNIME Node repository.   
   
### Example workflows
For testing we provide several workflows with test data:
 - Metagenomics workflow: [Slimm_taxonomic classification.knwf](Slimm_taxonomic_classification.knwf)
 - De novo assembly workflow: [SPAdes_assembly.knwf](SPAdes_assembly.knwf)
 - MLST workflow: [MLST_NGS-data.knwf](MLST_NGS-data.knwf)  
 Example data: [workflow_data.tar.gz](https://www.mi.fu-berlin.de/ess-bar/workflow_data.tar.gz)

### Source code
The source code for all nodes at [EssBAR-KNIME-nodes](https://github.com/kneubert/EssBAR-KNIME-nodes)
