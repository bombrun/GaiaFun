# GaiaFun
Some Gaia DR2 data exploration 

## Ophiuchus cloud
Explore the [Ophiuchus cloud notebook](OphiuchusCloud.ipynb)in 3D with GAIA second data release and plot.ly 

Based on Gaia archive ADQL query
<pre>
SELECT * FROM gaiadr2.gaia_source  WHERE CONTAINS(POINT('ICRS',gaiadr2.gaia_source.ra,gaiadr2.gaia_source.dec),CIRCLE('ICRS',247.025,-24.5417,2))=1  AND
gaiadr2.gaia_source.parallax>1
</pre>


## See also
* Pre Gaia era : 
  * Section 6.9 "Kinematic groups" in "Astronomical Applictions of Astrometry" by Michael Perryman, 2009
  * THE SCORPIUS OB2 COMPLEX :
       * http://iopscience.iop.org/article/10.1086/300491/pdf
       * http://www.pas.rochester.edu/~emamajek/scocen.pdf
* DR2 :
  * http://sci.esa.int/gaia/60131-gaia-s-view-of-dark-interstellar-clouds/
  * https://www.cosmos.esa.int/web/gaia/image-of-the-week Milky way map within 3000 parsec of Earth 
* wikipedia :
  * https://en.wikipedia.org/wiki/Rho_Ophiuchi_cloud_complex
  * https://en.wikipedia.org/wiki/Stellar_kinematics#OB_associations

