# data_organization
 Scripts to organize NMR and MS data for the Sinergia Project


Desired structure

output_path/
└── PF001/
    ├── PF001_metadata.tsv
    ├── ms_extracts_data/
    │   ├── file1_pos.mzML
    │   └── file2_neg.mzML
    ├── compounds/
        ├── compound1/
            ├── ms_data_compound/
                ├── compound1_pos.mzML
                ├── compound1_neg.mzML
                └── compound1_dual.mzML
            ├── NMR data/
                └── compound_id_NMR/
