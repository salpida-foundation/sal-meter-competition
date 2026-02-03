# Technical Details: How the Sal-Meter Works

## Overview

The Sal-Meter is a device that measures consciousness-related states using an **aptamer-based sensor** and **iodine oxidation-state sensing**.

This document explains the operation of the Sal-Meter in 7 steps.

---

## Step 1: Biological Sample Collection

First, a small biological sample is collected from the user.

### Sample collection methods

- **Blood**: 1–2 drops from the fingertip (similar to a glucose meter)
- **Saliva**: Swab from the inside of the cheek (similar to DNA test kits)
- **Breath**: Exhalation through a dedicated filter cartridge

### Why these sample types?

- Non-invasive or minimally invasive
- Easy to collect (potentially even at home)
- Contain neurochemical information related to consciousness states

---

## Step 2: Sample Pre-Processing

The sample is prepared so that it can be analyzed reliably by the sensor.

### Pre-processing pipeline

1. **Centrifugation**
   - Spin the sample at high speed
   - Remove blood cells and separate plasma/serum

2. **Filtration**
   - Remove large particles and debris
   - Typically use a 0.2 µm filter

3. **Dilution**
   - Adjust to an appropriate working concentration
   - Typical dilution: around 1:10

4. **pH Adjustment**
   - Set the buffer to an optimal range (around pH 7.4)
   - Use a physiological buffer such as PBS (phosphate-buffered saline)

---

## Step 3: Aptamer–Iodine Reaction

This is where the **core chemistry** happens.

### What is an aptamer?

- A DNA- or RNA-like molecule
- Binds selectively to specific target molecules
- Its optical properties (e.g., color/absorbance) can change under certain conditions

### Role of iodine

Iodine exists in several oxidation states:

- **I⁻** (iodide) → colorless
- **I₂** (molecular iodine) → brown
- **I₃⁻** (triiodide) → brown
- **I₅⁻** (pentaiodide) → dark brown

Each oxidation state has a different **color and optical absorption spectrum**.

### Connection to consciousness-related states

- When conscious activation is high, certain neurotransmitter systems (e.g., glutamatergic signaling) and related redox dynamics change.
- These changes influence specific molecular species in the sample.
- Those species, in turn, modulate the iodine oxidation state distribution.
- **Aptamers are designed to sense and transduce these iodine-state shifts** into measurable optical signals.

> Note: The precise biochemical mechanisms and target panels are under active development and are subject to ongoing experimental refinement.

---

## Step 4: Optical Detection

The device detects color/absorbance changes using an optical sensor.

### Optical sensor configuration

1. **Light source (LED)**
   - Emits light at specific wavelengths
   - Example bands: 280 nm (near UV), 350 nm, 450 nm (visible)

2. **Light passing through the sample**
   - Each iodine species absorbs different wavelengths to different degrees
   - Some light is absorbed; the rest is transmitted

3. **Detector (photodiode or photodetector array)**
   - Converts transmitted light into electrical signals
   - Measures absorbance at each wavelength

### Example measurement data

- Absorbance at 280 nm: 0.45  
- Absorbance at 350 nm: 0.12  
- Absorbance at 450 nm: 0.08  

These values are not fixed “normal ranges” but examples of the type of multi-wavelength data used for downstream analysis.

---

## Step 5: Signal Processing

Raw optical signals are cleaned and transformed into robust features.

### Noise reduction (signal filtering)

- Remove measurement noise and artifacts
- Use filters such as:
  - Kalman filter
  - Low-pass filter or band-pass filter (depending on design)

### Signal normalization

Normalize measurements to reduce variability due to external factors:

- Remove background light offsets
- Compensate for temperature (reaction kinetics change with temperature)
- Adjust for sample concentration and path length

### Feature extraction

Derive meaningful features from multi-wavelength signals, such as:

- Ratios between different iodine oxidation states
- Reaction kinetics (how fast absorbance changes over time)
- Signal amplitude and stability over repeated measurements

These features form the input to the AI model.

---

## Step 6: AI-Based Index Computation

Using the processed signal features, the Sal-Meter computes three indices.

### VCE (Vibrational Consciousness Energy)

**Index of vibrational/activation energy of consciousness**

Conceptual computation:

- A function of:
  - Dynamic properties of iodine-state transitions
  - Response speed and amplitude of the optical signal
  - Other CAIS-defined features related to excitation

Interpretation (illustrative ranges):

- **≥ 0.8**: High activation, high arousal, often associated with stress or intense engagement
- **0.4–0.6**: Typical waking-state activation
- **≤ 0.2**: Low activation, such as deep sleep, sedation, or deep meditation-like states

### CRI (Consciousness Resonance Index)

**Index of resonance and stability of consciousness**

Conceptual computation:

- \( \text{CRI} \approx \frac{\text{stability of oxidation patterns} \times \text{signal consistency}}{\text{noise level}} \)

Interpretation:

- **≥ 0.8**: Highly stable and coherent state, clear thinking, emotional stability
- **0.4–0.6**: Mild distraction or moderate instability
- **≤ 0.2**: Marked instability, confusion, or fragmentation

### CFI (Conscious Field Index)

**Index of field-level integration of consciousness**

Conceptual computation:

- A function combining:
  - Structural alignment of VCE-related features
  - Temporal stability captured by CRI
  - Measures of integration across multiple signal dimensions

Interpretation:

- **High CFI**: Conscious field is integrated and coherent
- **Low CFI**: Conscious field is fragmented or highly dispersed

### Model training

The machine-learning model is trained using:

1. Large sets of sensor signal data (multi-wavelength, time-series features)
2. Reference labels for the corresponding consciousness-related conditions or states
3. Neural networks or other ML models that learn mappings:  
   **signal features → VCE/CRI/CFI**

Once trained, the model predicts VCE, CRI, and CFI for new incoming measurements.

---

## Step 7: Output and Interpretation

The final results are presented in a machine-readable and human-readable form.

### Digital output (JSON format)

```json
{
  "timestamp": "2026-02-03T15:30:00Z",
  "VCE": 0.68,
  "CRI": 0.82,
  "CFI": 0.75,
  "interpretation": "normal_alert",
  "confidence": 0.87
}

### Example user-level interpretation

VCE: 0.68 – higher than baseline; moderate activation / alert state

CRI: 0.82 – highly stable; mental clarity and emotional stability

CFI: 0.75 – good overall integration; relatively harmonious state

---

### Example guidance (non-clinical, research-only):

Suitable moment for light work or creative tasks

Short periods of rest or gentle meditation may help maintain balance

---

## Visualization in the companion app

The app may provide:

- Real-time graphs of VCE/CRI/CFI over time
- Comparison charts: current state vs. personal baseline
- Short-term trends (e.g., last day or week)
- Long-term patterns across weeks or months

These visualizations are for research and self-observation, not for clinical diagnosis.

---

## References

### Core technical references (canonical DOIs):

- CAIS Architecture v1.0: https://doi.org/10.5281/zenodo.18160387
- CAIS Prototype Roadmap v1.0: https://doi.org/10.5281/zenodo.18161872
- Aptamer G-Iodine Concept Note: https://doi.org/10.5281/zenodo.18161302
- Universal Consciousness Sensor Architecture v1.0: https://doi.org/10.5281/zenodo.17705813

---

## Next Steps

For deeper technical details, read the DOI documents above.

If you have questions, use the GitHub Discussions tab in the competition repository.

If you want to build a prototype, see the Phase roadmap and Team composition guide documents.

---

**License:** CC BY-SA 4.0

**Last updated:** 3 February 2026
