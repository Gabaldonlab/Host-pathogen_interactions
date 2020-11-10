# Host-pathogen interactions between human and major Candida pathogens

The repository contains the data and R codes to fully reproduce the results and datasets of the study of host-pathogen interaction between human epitheliail cell line A431 and 4 major Candida pathogens C. albicans, C. glabrata, C. parapsilosis and C. tropicalis.

The "host_pathogen_interaction_codes.tar.gz" contains all necessary datasets, their description, directory structure, codes and software versions, which allow to exactly reproduce the aforementioned results.

Users should first untar the file, e.g. using

```
tar -xzvf host_pathogen_interaction_codes.tar.gz
```

The above command will create a directory where all the data will be located. We encourage the users to first read through the `file_description.txt` file, which describes all files in the created directory. Subsequently, users can open the `R` scripts in `Rstudio` and run them. On a modern desktop each script will require ~10-15 min to complete. Of note, the most computationally intensive and the longest step (the whole analysis, including GO enrichment of modules, might take ~2-3 hours) is the network analysis, which requires ~15Gb of RAM, and its speed will depend on the number of available cores. The version for all used software and packages can be found in `sesssionInfo.txt` file. All codes and required packages are open source. For full reproducibility, please make sure the software versions run on your machine coincide with versions in `sesssionInfo.txt`.


For any questions, please email `grant.hovhannisyan@gmail.com`.
