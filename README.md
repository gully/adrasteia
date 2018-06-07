adrasteia
===
exploring Gaia data with Pandas and Jupyter Notebooks

gully, September 14, 2016


Exploring data with the flat files from the Gaia Archive:
- [TGAS](http://cdn.gea.esac.esa.int/Gaia/tgas_source/)
- [GaiaSource](http://cdn.gea.esac.esa.int/Gaia/gaia_source/)


# notebooks

The Jupyter notebooks show my exploratory analysis of Gaia DR1 in September 2016 and Gaia DR2 in May 2018.  The notebooks are exploratory and in some cases un-commented and hard-coded.  Some pieces of data retrieval and exploratory analysis may be useful.

### 01- *deprecated*
### 02- Gaia DR1 first look
### 03- Gaia DR1 exploratory analysis

  1. Compare space density of TGAS and a small portion of GaiaSource
  2. Explore noise properties of TGAS parallaxes
  3. Demo a simple cross match of TGAS with a short table of [RA, Dec] positions
  4. Another demo of a cross match of TGAS with [RA, Dec] positions

### 04- Batch retrieve all Gaia DR1 GaiaSource CSV flat files

### 05- Gaia DR2 exploratory analysis

  1. DR1 Demo of applying `Dask` to parallelize dataframe analysis
  2. Summary statistics of Gaia DR2 variability catalogs
  3. Exploratory analysis of Rotational Modulation catalog of Gaia DR2
  4. Spot check instances of Gaia DR2's sparse lightcurves
  5. Cross-match K2 and Gaia DR2's rotational Modulation
