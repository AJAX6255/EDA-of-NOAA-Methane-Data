## EDA-of-NOAA-Methane-Data
Exploratory Data Analysis of NOAA Atmospheric Methane Data

--------------------------------------------------------------------
USE OF NOAA GML DATA
These data are made freely available to the public and the
scientific community in the belief that their wide dissemination
will lead to greater understanding and new scientific insights.
The availability of these data does not constitute publication
of the data. NOAA relies on the ethics and integrity of the user to
ensure that GML receives fair credit for their work. If the data
are obtained for potential use in a publication or presentation,
GML should be informed at the outset of the nature of this work.
If the GML data are essential to the work, or if an important
result or conclusion depends on the GML data, co-authorship
may be appropriate. This should be discussed at an early stage in
the work. Manuscripts using the GML data should be sent to GML
for review before they are submitted for publication so we can
ensure that the quality and limitations of the data are accurately
represented.
Contact: Xin Lan (xin.lan@noaa.gov)
File Creation: Mon Feb 6 16:24:44 2023
RECIPROCITY
Use of these data implies an agreement to reciprocate.
Laboratories making similar measurements agree to make their
own data available to the general public and to the scientific
community in an equally complete and easily accessible form.
Modelers are encouraged to make available to the community,
upon request, their own tools used in the interpretation
of the GML data, namely well documented model code, transport
fields, modeled mole fractions, and additional information
necessary for other scientists to repeat the work and to run
modified versions. Model availability includes collaborative
support for new users of the models.
--------------------------------------------------------------------

See gml.noaa.gov/ccgg/trends/ for additional details.

Uncertainties in the global monthly means are estimated using two
terms: The first is a bootstrap (resampling) method that varies the
sites in our network. Each pseudo-network contains the same number of
sites as our actual NOAA ESRL cooperative global air sampling network,
but some are repeated and some are excluded. The second term is a
Monte Carlo method that randomly modifies the data to account for
measurement uncertainty. In both cases, 100 globally-averaged time
series are created. Standard deviations of the monthly means are
calculated, and the two terms (network and analytical) are taken in
quadrature to give the reported uncertainties. A default value (-9.9)
indicates the uncertainty has not yet been calculated for that month.
Please see Dlugokencky et al., 1994, JGR, vol. 99, 17021-17043, for a
complete discussion.
CH4 expressed as a mole fraction in dry air, nanomol/mol, abbreviated as ppb
NOTE: In general, the data presented for the last year are subject to change,
depending on recalibration of the reference gas mixtures used, and other quality
control procedures. Occasionally, earlier years may also change for the same
reasons. Usually these changes are minor. 
