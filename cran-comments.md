## Resubmission
This is a resubmission. In this version:

Thank you very much for the earlier feedback!

* The package is now < 5 MB.
* On the depends search path: The package is a plug-in for R Commander that wraps multiple biclustering packages. The reasons that we added these all to the Depends field are (1) we use all functionalities from every included package and (2) we want the R Commander GUI to pick up the example data sets in these packages. The latter only works when these packages reside in the Depends field.
* The rqubic note: I am unsure what is going wrong here since 'rqubic' is an available package on Bioconductor that installs without issue through BiocManager.  Nevertheless the specific repository was added in the Additional_repositories field and a note on this was added as well in the description field.
