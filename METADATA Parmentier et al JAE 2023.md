
GENERAL INFORMATION

1. Title of Dataset: "You are what your host eats: The trophic structure and food chain length of a symbiont community are coupled with the plastic diet of the host ant” published in Journal of Animal Ecology

2. Author Information
	A. Principal Investigator Contact Information
  	 Name: Thomas Parmentier	
  	 Institution: Ghent University
  	 Address: Ghent, Belgium
  	 Email: Thomas.Parmentier@ugent.be
	
3. Date of data collection (single date, range, approximate date): July-August 2021

4. Geographic location of data collection: Belgium, France

5. Information about funding sources that supported the collection of the data: FWO (grant 1203020N) and FNRS (30257865)


SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: CC0 1.0 Universal (CC0 1.0) Public Domain

2. Links to publications that cite or use the data:

Parmentier T, Boeckx P, Bonte D, De Laender F (2023). You are what your host eats: The trophic structure and food chain length of a symbiont community are coupled with the plastic diet of the host ant. Journal of Animal Ecology

3. Links to other publicly accessible locations of the data: None

4. Links/relationships to ancillary data sets: None

5. Was data derived from another source? No

6. Recommended citation for this dataset: 

Parmentier, T., Boeckx, P., Bonte, D. & De Laender, F.  (2023). Data from: You are what your host eats: the trophic structure and food chain length of a symbiont community are coupled with the plastic diet of the host ant, Dryad, Dataset, https://doi.org/10.5061/dryad.jsxksn0gg


DATA & FILE OVERVIEW

The data is stored in an excel file "data Parmentier et al JAE 2023.xslx" with two tabs:


first tab "d15Nvalues" contains the raw δ15N values of four symbiont species 
following columns can be found:

	nest: nest identity (categorical data)
	site: site where the nest was found (categorical)
	forest: forest fragment where the nest was found (categorical)
	cluster: cluster id to which the nest belongs (categorical)
	polydom: degree of polydomy = number of nests in the cluster to which the nest belongs (integer)
	d15N_Organicmaterial: d15N values of organic nest material (continuous)
	d15N_Worker: δ15N value of host workers (continuous)
	d15N_Thiasophila: δ15N value of the symbiont Thiasophila angulata (continuous)
	d15N_Monotoma: δ15N value of the symbiont Monotoma angusticollis (continuous)
	d15N_Thyreosthenius: δ15N value of the symbiont Thyreosthenius biovatus (continuous)
	d15N_Cyphoderus: δ15N value of the symbiont Cyphoderus albinus (continuous)
	d15N_Organicmaterial_forest: mean δ15N value of the nest material in the forest fragment where the nest was found (continuous)

Missing data codes: NaN (data not available)

second tab "nest parameters" contains the nest parameters, specific information on the nest parameters can be found in the main article
following columns can be found:

	nest_id: nest identity, this column is identical to column nest in the first tab and allows to link the nest parameters with the δ15N values of the first tab. (categorical)
	moisture: moisture content of a nest (continuous)
	pH: acidity of nest material (continuous)
	surface: nest surface (m²) of a nest as a proxy for nest size (continuous)
	y: latitude (continuous)
	x: longitude (continuous)
	forest_cover: percentage forest cover in a radius of 50 m around the nest (proportion)

Missing data codes: NaN (data not available)
