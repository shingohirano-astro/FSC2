# First star clusters - II

<!--
A short description of your project, what kind of data it contains, and how it relates to your research or application.
--> 

## Overview

This repository contains:
- **`data/` directory** with CSV files (`FSC_Table1.csv`, `FSC_TableA1.csv`) providing analysis data of Hirano (2025).

## Data Description

- **FSC_Table1.csv**  
  | Column Name | Description                                    | Unit                   |
  |-------------|------------------------------------------------|------------------------|
  | `Class`     | Class name                                     | -                      |
  | `v_SV`      | Streaming velocity                             | RMS (sigma_SV)         |
  | `z`         | Redshift at the time of collapse               | -                      |
  | `R_vir`     | Halo radius at the virial scale                | solar radii (R_\odot)  |
  | `M_vir`     | Halo mass at the virial scale                  | solar masses (M_\odot) |
  | `f_b`       | Baryon fraction at the virial scale            | -                      |
  | `N_HD/N`    | Ratio of HD-cooling models                     | -                      | 
  | `N_c`       | Number of cores                                | -                      |
  | `M_ctot`    | Total mass of cores                            | solar masses (M_\odot) | 
  | `eps_III`   | Mass conversion efficiency                     | -                      | 
  | `M_c1`      | Mass of the primary massive core               | solar masses (M_\odot) |
  | `M_c2`      | Mass of the secondary massive core             | solar masses (M_\odot) |
  | `q_c`       | Mass ratio of the primary and secondary cores  | -                      |


- **FSC_TableA1.csv**  
  | Column Name | Description                                    | Unit                   |
  |-------------|------------------------------------------------|------------------------|
  | `Model`     | Model name                                     | -                      |
  | `v_SV`      | Streaming velocity                             | RMS (sigma_SV)         |
  | `z`         | Redshift at the time of collapse               | -                      |
  | `R_vir`     | Halo radius at the virial scale                | solar radii (R_\odot)  |
  | `M_vir`     | Halo mass at the virial scale                  | solar masses (M_\odot) |
  | `f_b`       | Baryon fraction at the virial scale            | -                      |
  | `Class`     | Class name                                     | -                      | 
  | `HD`        | Whether HD-cooling is enabled                  | -                      | 
  | `N_c`       | Number of cores                                | -                      |
  | `M_ctot`    | Total mass of cores                            | solar masses (M_\odot) | 
  | `eps_III`   | Mass conversion efficiency                     | -                      | 
  | `M_c1`      | Mass of the primary massive core               | solar masses (M_\odot) |
  | `M_c2`      | Mass of the secondary massive core             | solar masses (M_\odot) |
  | `q_c`       | Mass ratio of the primary and secondary cores  | -                      |

## Usage Notes

1. **Data Format**: CSV files are comma-separated (`,`), encoded in UTF-8.
3. **Citation**: If you use this data in your research or publication, please cite our paper:
   > Hirano (2025). Title of the paper. *Journal Name*, Volume(Issue), Pages.  
   > [DOI or arXiv link]

## License

This project is licensed under the CC-BY-4.0. See the LICENSE file for details.

## Contact

For any questions regarding this data, please open an issue on GitHub or email us at shingo-hirano@kanagawa-u.ac.jp.
