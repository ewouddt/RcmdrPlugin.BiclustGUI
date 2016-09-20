
<!-- README.md is generated from README.Rmd. Please edit that file -->
The BiclustGUI for R Commander
==============================

`RcmdrPlugin.BiclustGUI` is a R Commander Plug-In containing multiple methods to apply biclustering and visualise these results.

Installing the GUI
------------------

To install the **CRAN Release Version**, please use the following commands:

``` r
setRepositories(ind=c(1:5))
install.packages("RcmdrPlugin.BiclustGUI")
```

To install the **Development Version** from either the *R-Forge* or *GitHub* repository use

``` r
setRepositories(ind=c(1:5))
install.packages("RcmdrPlugin.BiclustGUI",repos="http://R-Forge.R-project.org")
```

or

``` r
setRepositories(ind=c(1:5))
install.packages("devtools") # If not yet installed on your R Version
devtools::install_github("hadley/devtools") # Only run this if your currently installed 
                                            # devtools version is <= 1.12 (recursive dependencies bug)

devtools::install_github("ewouddt/RcmdrPlugin.BiclustGUI")
```

One of the options above will install the GUI and its dependencies from both CRAN and Bioconductor. Should some issue arise with a package installation, please try to manual install them. The code for this can be found [here](https://ibiostat.be/online-resources/online-resources/biclustgui/biclustgui).

On the initial start-up of R Commander, you will probably be prompted to install some additional dependencies. This should not take too long!

To launch the GUI, use:

``` r
library(RcmdrPlugin.BiclustGUI)
```

More Info & Links
-----------------

-   *Introductory Blog on GitHub/R-Bloggers* (Coming Soon).
-   *Detailed Guide* (See /vignettes/GuideBiclustGUI.pdf).
-   *Shiny Application for Biclustering* ([Shiny Cloud](https://uhasselt.shinyapps.io/shiny-biclust/) + [Stand-Alone](https://ibiostat.be/online-resources/online-resources/biclustgui/shinyapp) + GitHub (Coming Soon))
-   *R-Forge Project Page* ([R-Forge](https://r-forge.r-project.org/R/?group_id=2104)).
-   *I-Biostat Page* ([I-Biostat](https://ibiostat.be/online-resources/online-resources/biclustgui/biclustgui)).

Currently Available Methods/Diagnostics
---------------------------------------

<table style="width:79%;">
<caption>All included biclustering and diagnostics packages in the BiclustGUI:</caption>
<colgroup>
<col width="15%" />
<col width="40%" />
<col width="23%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">R Package</th>
<th align="left">Biclustering Method</th>
<th align="left">Publication</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><code>biclust</code></td>
<td align="left">Plaid</td>
<td align="left">Turnet <em>et al.</em>, 2005</td>
</tr>
<tr class="even">
<td align="left"><code>biclust</code></td>
<td align="left"><span class="math inline"><em>δ</em></span>-biclustering</td>
<td align="left">Cheng and Church, 2000</td>
</tr>
<tr class="odd">
<td align="left"><code>biclust</code></td>
<td align="left">X Motif</td>
<td align="left">Murali and Kasif, 2003</td>
</tr>
<tr class="even">
<td align="left"><code>biclust</code></td>
<td align="left">Spectral</td>
<td align="left">Kluger <em>et al.</em>, 2003</td>
</tr>
<tr class="odd">
<td align="left"><code>biclust</code></td>
<td align="left">QuestMotif</td>
<td align="left">Kaiser, 2011</td>
</tr>
<tr class="even">
<td align="left"><code>biclust</code></td>
<td align="left">Bimax</td>
<td align="left">Prelic <em>et al</em>., 2006</td>
</tr>
<tr class="odd">
<td align="left"><code>fabia</code></td>
<td align="left">FABIA</td>
<td align="left">Hochreiter <em>et al.</em>, 2010</td>
</tr>
<tr class="even">
<td align="left"><code>isa2</code></td>
<td align="left">The Iterative Signature Algorithm</td>
<td align="left">Bergman <em>et al</em>., 2003</td>
</tr>
<tr class="odd">
<td align="left"><code>iBBiG</code></td>
<td align="left">Iterative Binary BIclustering of Genesets</td>
<td align="left">Gusenleitner <em>et al</em>., 2012</td>
</tr>
<tr class="even">
<td align="left"><code>rqubic</code></td>
<td align="left">Qualitative Biclustering</td>
<td align="left">Li <em>et al</em>., 2009</td>
</tr>
<tr class="odd">
<td align="left"><code>BicARE</code></td>
<td align="left">Biclustering Analysis and Results Exploration</td>
<td align="left">Gestraud and Barillot, 2014</td>
</tr>
<tr class="even">
<td align="left"><code>s4vd</code></td>
<td align="left">SSVD (Sparse Singular Value Decomposition)</td>
<td align="left">Lee <em>et al</em>., 2010</td>
</tr>
<tr class="odd">
<td align="left"><code>s4vd</code></td>
<td align="left">S4VD (SSVD incorporating stability correction)</td>
<td align="left">Sill <em>et al</em>., 2011</td>
</tr>
<tr class="even">
<td align="left"><strong>R Package</strong></td>
<td align="left"><strong>Diagnostics</strong></td>
<td align="left"><strong>Publication</strong></td>
</tr>
<tr class="odd">
<td align="left"><code>BcDiag</code></td>
<td align="left">Bicluster Diagnostic Plots</td>
<td align="left">Aregay <em>et al</em>., 2014</td>
</tr>
<tr class="even">
<td align="left"><code>superbiclust</code></td>
<td align="left">Generating Robust Biclusters from a Bicluster Set</td>
<td align="left">Khamiakova, 2013</td>
</tr>
</tbody>
</table>
