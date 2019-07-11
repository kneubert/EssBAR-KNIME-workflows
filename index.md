## A tool collection for metagenomics
KNIME4Metagenomics is a collection of KNIME nodes to detect and characterize foodborne pathogens. They are wrappers for several tools.

## How to
### Prerequisites
 - Linux OS (x86_64)
 - KNIME Analytics Platform for Linux (>= version 3.1, but below version 4.0)
 - KNIME Community Extensions - Bioinformatics & NGS -> SeqAn NGS Toolbox (GenericKnimeNodes, NgsToolbox, SeqAn)

### Installation of nodes using the update site
You need to load the EssBAR update site as a repository within KNIME using  
```Help -> Install New Software -> Add```  
Now add the update site https://www.mi.fu-berlin.de/ess-bar/updateSite to the available software sites. Select the displayed package "EssBAR NGS toolbox" and click on Next>. Accept the license agreements by checking the corresponding box.
If a security warning pops up click install anyway:  
![image](images/unsigned_content-warning.png)  
You will be asked to restart KNIME for changes to take effect. Afterwards the EssBAR KNIME nodes should be visible in the KNIME Node repository.

### Example workflows
For testing we provide several workflows with test data:
 - Metagenomics workflow 
 - De novo assembly workflow
 - Phylogenetics workflow
 - MLST workflow

### Source code
The source code for all nodes is available at https://github.com/kneubert/EssBAR-KNIME-nodes
