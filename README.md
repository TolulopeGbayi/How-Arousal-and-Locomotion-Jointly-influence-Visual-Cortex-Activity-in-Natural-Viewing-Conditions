# How Arousal and Locomotion Jointly Influence Visual Cortex Activity in Natural Viewing Conditions

## Project Overview

Sensory processing in the brain is greatly influenced by behavioral states like movement and arousal as a response to the environment. However, how locomotion (movement) and changes in arousal (indicated by pupil size) work synergistically to affect the brain exposed to natural experiences is not yet fully understood. 

### Research Questions

Locomotion has been shown to influence cortical gain and reliability of visual brain responses, while pupil size shows fast arousal-driven changes. However, most past research has focused on these factors in isolation or with simple visual stimuli, thereby leaving questions about how the combined effect influences state-to-state changes during real-life visual scenes. This project aims to address this gap by examining the joint influence of locomotion and arousal on visual cortex activity during naturalistic stimulation.

## Methodology

To understand this synergistic relationship, publicly available two-photon calcium imaging data extracted from the Allen Brain Observatory was analyzed, focusing on:

- **209 neurons** in the primary visual cortex (VISp)
- **Stimulus**: Natural movie presentation
- **Behavioral measures**: Running speed and pupil size (as an arousal proxy)
- **Analysis approach**: 
  - Frame-by-frame generalized linear models for single-cell responses
  - Principal component analysis (PCA) for population-level activity patterns
  - Joint modeling of locomotion and arousal interactions at fine time scales

## Key Findings

### Single-Cell Level
- Modest behavioral modulation was observed (median R² = 0.02), indicating that while individual neurons show some response to behavioral state, the modulation is relatively modest

### Population Level
Distinct and clear patterns emerged in low-dimensional space:
- **PC4 (Running-Active Mode)**: Accounted for 22% of variance associated with locomotion, representing cortical activity during active running states
- **PC3 (Running-Suppressed Mode)**: Represented suppressed activity during locomotion
- **Arousal Component**: Pupil-linked arousal had minimal contribution to the observed population variance

## Significance

The novel findings reveal that behavior modulates visual cortex activity through **specific, organized low-dimensional population dynamics**, rather than simple uniform changes in response strength. Through joint modeling of locomotion and arousal under real-life naturalistic stimulation, these findings from single- and population-level analyses **bridge the gap between experimental observations and computational models**, providing critical insights into how behavior shapes sensory processing in the brain.

## Data Source

All analyses are based on publicly available data from the [Allen Brain Observatory](https://observatory.brain-map.org/), ensuring reproducibility and accessibility.
