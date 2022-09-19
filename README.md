# DATA22
Source files, alignmnet results and ground truth data files for DATA22 Workshop (BuildSys/Sensys).

### Folder structure
    .
    ├── backbone-ontology				# Backbone ontology interlinking building ontologies with Brick
    └── reproducibility
        ├── alignment-results
        │   ├── processed-results                       # AML and LogMap mappings after removing non-valid classes
        │   ├── raw-results                             # Raw mappings for AML, LogMap and TrioNet
        │   ├── union-groundtruth-verified              # Manually-verified groundtruth from union mappings of AML/LogMap/TrioNet              
        │   │   ├── raw-groundtruth                       # Raw groundtruth in .csv based on the union of raw mappings              
        │   │   ├── 1_IFC_BRICK.rdf                       # Processed groundtruth (non-valid classes removed) in RDF aligment format      
        │   │   ├── 2_SAREF_BRICK.rdf                     # Processed groundtruth (non-valid classes removed) in RDF aligment format              
        │   │   ├── 3_SAREF4BLDG_BRICK.rdf                # Processed groundtruth (non-valid classes removed) in RDF aligment format              
        │   │   ├── 4_IOTLITE_BRICK.rdf                   # Processed groundtruth (non-valid classes removed) in RDF aligment format              
        │   │   ├── 5_BOT_BRICK.rdf                       # Processed groundtruth (non-valid classes removed) in RDF aligment format              
        │   ├── valid-classes                           # HTML files with valid classes for each ontology
        ├── annotated mappings				# Annotations provided to TrioNet from the ground truth                
        └── fig                                         # Plotted results


## Authors

- Celia Garrido-Hidalgo (Universidad de Castilla-La Mancha, celia.garrido@uclm.es).
- Jonathan Fürst (Zürich University of Applied Sciences and NEC Laboratories Europe).
- Bin Cheng (NEC Laboratories Europe).
- Luis Roda-Sanchez (NEC Ibérica S.L. and Universidad de Castilla-La Mancha).
- Teresa Olivares (Universidad de Castilla-La Mancha).
- Ernö Kovacs (NEC Laboratories Europe).
