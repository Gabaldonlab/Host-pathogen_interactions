# Host-pathogen interactions between human and major Candida pathogens

The repository contains the data and R codes to fully reproduce the results and datasets of the study of host-pathogen interaction between human epitheliail cell line A431 and 4 major Candida pathogens C. albicans, C. glabrata, C. parapsilosis and C. tropicalis.

The "host_pathogen_interaction_codes.tar.gz" contains all necessary datasets, their description, directory structure, codes and software versions, which allows to exactly reproduce the aforementioned results.

Users should first untar the file, e.g. using

```
tar -xzvf host_pathogen_interaction_codes.tar.gz
```

The above command will create `codes` directory where all the data will be located. We encourage the users to first read through the `file_description.txt` file, which describes all files in the created directory. Subsequently, users can open the `R` scripts in `Rstudio` and run them (on a modern desktop each script will required ~5-6 min to complete). The version for all used software and packages can be found in `sesssionInfo.txt` file. All codes and required packages are open source. For full reproducibility, please make sure the software versions run on your machines coincide with versions in `sesssionInfo.txt`.


For any questions, please email to `grant.hovhannisyan@gmail.com`.
