# fgas-2021-paper

Data underlying figures and tables in [this paper]().

Note that our cosmological analysis can **not** be reproduced solely from these data; this repository contains only what is directly shown in figures and tables, and nothing else.
You can find the necessary code and data to reproduce the analysis itself [here](https://github.com/abmantz/fgas-cosmo).

Numerous (unrelated) cosmological parameter contours can be found [here](https://github.com/abmantz/cosmo-contours).

Maintenance of this repository is expected to be minimal to non-existant.

### Figure data

`figure_data/` contains data that are plotted in various figures, generally with no further manipulation.

Knowing what files contribute to what figure (see below) should, hopefully, be enough to make their contents either self-explanatory or easily inferred.

Figure 1:
* `figure_data/fgasDiff_profiles/*.dat`

Figure 2:
* `figure_data/table_z_fgas_M2500.dat`

Figure 3:
* `figure_data/perseus.reg`

Figure 4:
* `figure_data/a2029/*.dat`

Figure 5:
* `figure_data/table_z_fgas_M2500.dat`
* `figure_data/predictions.dat`

Figure 6:
* `figure_data/w__lowz_nopriors__fbaryon_h__*.dat`
* `figure_data/planck18_w__planck__fbaryon_h__*.dat`
* `figure_data/riess19__fbaryon_h__*.dat`

Figure 7:
* `figure_data/fLCDM__fgas_noUprior__OMpost.dat`

Figure 8a:
* `figure_data/omegak__fgas__*.dat`
* `figure_data/omegak__pantheon__*.dat`
* `figure_data/eBOSS2007.08991/om_ol_*s.dat`
* `figure_data/omegak__planck__*.dat`

Figure 8b:
* `figure_data/w__fgas__*.dat`
* `figure_data/w__pantheon__*.dat`
* `figure_data/eBOSS2007.08991/om_w_*s.dat`
* `figure_data/w__planck__*.dat`

Figure 9a:
* `figure_data/omegak__fgas__*.dat`
* `figure_data/old_fgas/A08__lcdm__om_ol__*.dat`
* `figure_data/old_fgas/M14__lcdm__om_ol__*.dat` 

Figure 9b:
* `figure_data/w__fgas__*.dat`
* `figure_data/old_fgas/A08__w__om_w__*.dat`
* `figure_data/old_fgas/M14__w__om_w__*.dat`

Figure 10a:
* `figure_data/omegak_w__fgas_planck_pantheon_baoDR12__*.dat`

Figure 10b:
* `figure_data/wa__fgas_planck_pantheon_baoDR12__*.dat`
* `figure_data/omegak_wa__fgas_planck_pantheon_baoDR12__*.dat`

### Table data

`tables/` contains the paper's tables in latex format, and are identical to the corresponding files in the paper's source on the arxiv (including markup).
