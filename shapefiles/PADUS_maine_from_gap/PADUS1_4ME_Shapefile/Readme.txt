State, Regional, LCC Shapefile
PAD-US Version 1.4 data download.

This Readme file is intended to provide a short description of the items contained with the data download. For more information, visit the PAD-US Website: http://gapanalysis.usgs.gov/padus/.

Items in the download:

Fee and Easements - (PADUS1_4Fee_Easments) - This shapefile contains the PAD-US Fee and Easements features together. These data are exported from the complete PAD-US file based on a selection of “State Name” for the States and Regions, and is clipped using the LCC Boundaries for the LCC files.
			
MPA - States, Regions and LCC’s that contain Marine Protected Areas (MPA) also include a PADUS1_4MPA shapefile - This is the entire PAD-US 1.4 MPA file provided directly by the National Oceanic and Atmospheric Administration (NOAA) Marine Protected Areas Center (MPA, http://marineprotectedareas.noaa.gov ) tracking the National Marine Protected Areas System (includes “member” and “eligible” MPAs only).  
				
*These shapefiles were exported from a File Geodatabase that uses coded domains, the shapefile includes two fields for those with standard domains: one field attributed with the domain code and the other with the domain description.

LUT - Lookup tables for each of the eight coded domains used within the feature classes of the original geodatabase. These .dbf tables describe both the domain codes and descriptions.

NOTE: Many legitimate boundary overlaps (and some errors) exist in the PAD-US geodatabase.  A selection where “Category” = “Designation” or Category = “Other” highlights the majority of known overlaps (fed theme, MPAs).  Sliver errors are created during the aggregation of authoritative source data.  These are identified and shared with agencies while source data are edited over time.

Metadata (PADUS1_4_Metadata_xml_FGDC.xml) - Complete metadata file containing specific information about PAD-US data development, contributors, contacts, standards, uses and access.

Layers (ArcGIS Layer files) - Twenty-three symbology layers offer standard visualizations, intended to aid interpretation, using the PADUS1_4Combined feature class. For information about specific files, please see the PADUS1_4 Layer Files Description.pdf included in this download. These layers are also avaliable as viewable layers in the PAD-US online web viewer (http://gapanalysis.usgs.gov/padus/viewer/) and as consumable web services that can be accessed from (http://gapanalysis.usgs.gov/data/web-services/)

Layer Description (PADUS1_4 Layer Files Description.pdf) - contains information relating to the Layer files provided in the download that can be used to symbolize the data. This Readme file is intended to provide a short description of the items contained with the data download. For more information about PAD-US please visit the Protected Areas Data Portal of the USGS Gap Analysis Program website. (http://gapanalysis.usgs.gov/padus/).			



MXD (PADUS1_4LayerFiles.mxd) - ESRI ArcMap Map Document, contains two data frames PAD-US Standard Symbology and Raw PAD-US Data. The “PAD-US Standard Symbology” contains the twenty-three layers included with the data download, drawing from the Fee and Easements  shapefile. It also includes the 2014 Census state boundary file. The Second Data frame “Raw PAD-US Data” includes the Fee and Easements shapefile, and the MPA file where applicable,  with no standard symbolization, it also includes the Census state boundary file.

Census State Boundary (tl_2014_us_state_AlbersUSGS.shp)
Census is the authoritative source of state line boundaries for PAD-US.  GAP intersected 2014 Census TIGER/Line state boundaries, as a common standard, into source files in the PAD-US 1.4 aggregation.  This process introduces boundary slivers where discrepancies occur.  No other alterations of source line work are permitted, unless edits are approved by data stewards to prevent reoccurrence in source data files. Errors are identified and shared with data stewards to edit source data directly, improving PAD-US aggregations over time.  See “Census Boundary and Annexation Survey Shapefiles and Maps” website for best available boundaries for state stewards: http://www.census.gov/geo/partnerships/bas/bas_download.html.  Nationally aggregated state boundaries (TIGER/Line Shapefiles) are also available (previous year) for national data stewards seeking a boundary standard.  See: http://www.census.gov/geo/maps-data/data/tiger-line.html for current data.  
