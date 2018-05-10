# GaiaFun
Some Gaia DR2 data exploration 

## Ophiuchus cloud
Explore the [Ophiuchus cloud notebook](OphiuchusCloud.ipynb)in 3D with GAIA second data release and plot.ly 

All the stars lie on a perfect half sphere! See the final 3D plot on https://plot.ly/~A.Bombrun/1

Based on Gaia archive ADQL query
<pre>
SELECT * FROM gaiadr2.gaia_source  WHERE CONTAINS(POINT('ICRS',gaiadr2.gaia_source.ra,gaiadr2.gaia_source.dec),CIRCLE('ICRS',247.025,-24.5417,2))=1  AND
gaiadr2.gaia_source.parallax>1
</pre>

See also [wikipedia](https://en.wikipedia.org/wiki/Rho_Ophiuchi_cloud_complex) 

