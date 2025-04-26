# EEG Emotion Classification Dataset

This directory contains the EEG data used for emotion classification.

## Directory Structure
- `raw_data/`: Contains raw EEG recordings (.mat files)
- `filtered_data/`: Contains preprocessed and filtered EEG data
- `artifact_removal/`: Contains EEG data after artifact removal

## Data Format
The EEG data is stored in MATLAB .mat files with the following format:
- File naming convention: `{task_type}_sub_{subject_id}_trial{trial_num}.mat`
- Each file contains a variable 'Clean_data' with dimensions [channels × timepoints]
