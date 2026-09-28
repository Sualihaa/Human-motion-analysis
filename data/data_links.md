# Real Data Resources for Week 1 and Later Projects

These are suitable sources of real gait and biomechanics data. Do not upload large full datasets directly into GitHub unless the dataset license permits redistribution and the file sizes are reasonable.

## Primary multimodal dataset for the internship

### Kim et al. multimodal gait dataset
- Article: *A multimodal gait dataset with ultrasound, EMG, and motion capture from young adults at various walking speeds*, Scientific Data, 2026.
- Link: https://www.nature.com/articles/s41597-026-08156-5
- Useful for: ultrasound-derived tibialis anterior fascicle length and pennation angle, EMG, motion capture, GRF, OpenSim outputs.
- Best use: later Week 2/3 and final undergraduate research projects.

## Motion capture + GRF + OpenSim-friendly data

### AddBiomechanics
- Website: https://addbiomechanics.org/
- SimTK project: https://simtk.org/projects/addbiomechanics
- Paper: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0295152
- Dataset paper / overview: https://pmc.ncbi.nlm.nih.gov/articles/PMC11948690/
- Useful for: marker trajectories, GRF, OpenSim scaling, inverse kinematics, inverse dynamics.
- Best use: demonstrations of how raw lab measurements become joint angles and moments.

### CAMARGO lower-limb biomechanics dataset
- Overview: https://www.epic.gatech.edu/opensource-biomechanics-camargo-et-al/
- Mendeley repository: https://data.mendeley.com/datasets/fcgm3chfff/1
- Paper: https://www.sciencedirect.com/science/article/abs/pii/S0021929021001007
- Useful for: locomotion across treadmill, level-ground walking, ramps and stairs; includes wearable sensors, motion capture and force-plate data.
- Best use: more advanced projects after students understand basic gait signals.

### SIAT-LLMD lower-limb motion dataset
- Article: https://www.nature.com/articles/s41597-023-02263-3
- Useful for: lower-limb sEMG, kinematics, kinetics and labelled motion tasks.
- Best use: EMG + kinematics/kinetics integration.

## IMU / wearable-sensor-oriented data

### BLISS dataset
- Repository page: https://researchdata.bath.ac.uk/1425/
- Useful for: bilateral EMG and wearable-sensor kinematics from healthy and gait-impaired participants.
- Best use: later wearable-sensor or rehabilitation-focused student projects.

### Irregular/uneven surface gait dataset
- Paper title to search: *A database of human gait performance on irregular and uneven surfaces collected by wearable sensors*.
- Useful for: wearable-sensor gait under uneven-surface conditions.
- Best use: IMU-based student projects that avoid machine learning or focus on descriptive gait measures.

## General motion-capture repository

### CMU Graphics Lab Motion Capture Database
- Link: http://mocap.cs.cmu.edu/
- Useful for: general human motion capture examples.
- Caution: not all trials include force plates, clinical gait variables or biomechanical outputs.

## Practical advice for the GitHub repository

- Include only small teaching files under `data/sample_data/`.
- Keep large datasets external and link to the official source.
- Record dataset citation, license/terms of use, variables used, and preprocessing assumptions.
- For teaching, start with small extracted files rather than asking students to handle the full dataset immediately.
