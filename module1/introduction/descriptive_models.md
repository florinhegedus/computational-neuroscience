# Week 1: What is Computational Neuroscience?

## Introduction to Computational Neuroscience

### Definition by Terry Sejnowski
- **Goal:** Explain in computational terms how brains generate behaviors.
- **Note:** Terry Sejnowski is one of the founding fathers of the field and was also the instructor's postdoctoral advisor.

### Definition by Peter Dayan and Larry Abbott
- **Objective:** Provide tools and methods for:
  1. Characterizing what nervous systems do.
  2. Determining how they function.
  3. Understanding why they operate in particular ways.
- **Correspondence:** These objectives align with the three types of computational models discussed earlier: descriptive, mechanistic, and interpretive models.

## Example: Receptive Fields
### Early Experiments by Hubel and Wiesel (1960s)
- **Focus:** Understanding the visual system of the cat.
- **Method:** Implanted tiny electrodes into the visual area of the cat's brain to record electrical signals from brain cells.
- **Findings:** 
  - Brain cells respond to tiny digital pulses (spikes or action potentials).
  - Different types of stimuli elicit different responses from brain cells.

#### Experiment Details
- **Stimulus:** A bar of light oriented at approximately 45 degrees.
- **Response:** The brain cell responds robustly to this specific orientation and not to broad field illumination.

### Definition: Receptive Field
- **Concept:** Specific properties of a sensory stimulus that generate a robust response from a recorded cell.
- **Examples:**
  - A cell in the retina responding to spots of light at particular locations.
  - A visual cortex cell in the cat's brain responding to a bar of light at a specific orientation and location.

## Three Types of Computational Models Applied to Receptive Fields

### 1. Descriptive Models
- **Example:** Retinal receptive fields
  - **Process:** Flash circular spots of light at different locations on the retina.
  - **Findings:**
    - Cells respond robustly when a spot of light is turned on in a specific central region.
    - Cells stop responding when a spot of light is turned on in the surrounding area (annulus).
  - **Concepts:** On-Center, Off-Surround, and Off-Center, On-Surround Receptive Fields.
- **Transmission:** Information from the retina is passed to the lateral geniculate nucleus (LGN) and then to the primary visual cortex.

### 2. Mechanistic Models
- **Focus:** Transition from center-surround receptive fields in the retina and LGN to oriented receptive fields in the primary visual cortex.
- **Next Lecture:** Detailed discussion on Mechanistic Models of Receptive Fields.

### 3. Interpretive Models
- **Objective:** Extract computational principles underlying brain circuit functions (covered in later lectures).

## Observations in the Primary Visual Cortex
- **Variety:** Receptive fields vary in orientation (vertical, horizontal, different angles).
- **Response:** Some cells respond to bright bars while others respond to dark bars at various orientations.

### Quantitative Estimation
- **Technique:** Reverse correlation (covered later in the course).
