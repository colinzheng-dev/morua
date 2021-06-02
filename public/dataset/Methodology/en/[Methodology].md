The scientific visualizations presented on this platform were produced through the extensive data mining and analysis of declassified French documents and open access government sources.

The reconstruction of fallout patterns and cloud trajectories from French nuclear tests was done using the <a target="_blank" href="https://www.arl.noaa.gov/hysplit/hysplit/">US NOAA Hybrid Single-Particle Integrated Trajectory</a> (HYSPLIT) particle transport and dispersion model and meteorological data from the <a target="_blank" href="https://www.cpc.ncep.noaa.gov/products/wesley/reanalysis.html">NCEP/NCAR Reanalysis (1948 - present)</a> project. Initial stabilized radioactive clouds were represented as vertical linear sources with activity adequately distributed among the cap, skirt and stem of the cloud. The cloud particle sizes were assumed to be log-normally distributed. Calculations were run on a 12-core linux machine and involved the release of 3,000,000 3D particles each. Output data include particle air concentration between 0 and 500m and ground deposition. Different source terms were used for activity concentration maps or normalized dose rate contour using uranium-235 and plutonium-239 <a target="_blank" href="https://www.nndc.bnl.gov/endf/b8.0/">ENDF8</a> fission product yields at 500keV and 14 MeV involving hundreds of isotopes. Decay of the source term was conducted using <a target="_blank" href="https://onix-documentation.readthedocs.io/en/latest/overview.html">Onix, an open source depletion code developed at Princeton University</a>. Activity to dose factors were obtained from the <a target="_blank" href="https://www.epa.gov/radiation/federal-guidance-report-no-12-external-exposure-radionuclides-air-water-and-soil">US Federal Guidance Report No. 12</a> (External Exposure to Radionuclides in Air, Water, and Soil) and the <a target="_blank" href="https://www.icrp.org/publication.asp?id=ICRP%20Publication%2072">ICRP Publication 72</a> Age-dependent Doses to the Members of the Public from Intake of Radionuclides (Compilation of Ingestion and Inhalation Coefficients). More detailed calculations and discussion of the challenges and opportunities of modelling barge shots and air bursts at close and long ranges up to several weeks will be the focus of future publications.

The dose reevaluations presented on this platform were conducted through the careful analysis of French government dose reconstruction reports for key nuclear tests (<a target="_blank" href="http://moruroa.assemblee.pf/medias/pdf/impact dosim%C3%A9trique aldebaran 2006.pdf">available on moruroa.assemblee.pf</a>) that represent today the basis on which claims for compensation from members of the public are adjudicated. The hypothesis and input data of these studies were crossed checked with information available from the declassified historical documents as well as information available from the scientific literature.

The scientific results and findings of this investigation will be made available to the public and the scientific community. The list of papers and reports associated with this work will be regularly updated and linked to this page as they become available.

List of publications:

Paper 1. Sebastien Philippe, Sonya Schoenberger, and Nabil Ahmed, <a href="https://arxiv.org/abs/2103.06128" target="_blank" rel="noreferrer" class="hyperlink">“Radiation Exposures and Compensation of Victims from French Atmospheric Nuclear Tests in Polynesia”</a>.

![](https://fp-nuclear-bucket.s3.eu-west-3.amazonaws.com/VIDEO/FP-Global+Fallout.gif)
_Hysplit simulation of the global fallout from the 1966 Aldebaran test (results for visualization only)_