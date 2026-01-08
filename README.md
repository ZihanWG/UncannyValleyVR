# Uncanny Valley VR: Facial Realism and Perception Study
https://zihanwportfolio.wordpress.com/2024/11/30/uncanny-valley-exploration-in-vr/
> A VR-based experimental system for studying how facial tracking accuracy, lip synchronization, and eye micro-motions influence the uncanny valley effect.

---

##  Overview

The **Uncanny Valley VR Project** investigates how subtle imperfections in virtual avatar facial animation affect user perception in immersive virtual reality.

Rather than focusing on visual fidelity alone, this project studies the **interaction between tracking accuracy, animation noise, and perceptual realism**, with a particular emphasis on:

- Facial expression alignment
- Lip synchronization accuracy
- Eye micro-motions (blinking, saccades)
- Controlled imperfections and temporal noise

The system is designed as a **research-oriented VR experience**, guiding users through structured interactions to evaluate which factors mitigate or amplify the uncanny valley effect.

---

## Research Objectives

- Analyze how **facial tracking precision** influences perceived realism
- Compare **tracking-driven lip sync** vs. audio-driven approaches
- Study the role of **subtle eye motion** in reducing uncanny responses
- Evaluate how **controlled noise and imperfections** affect user comfort
- Establish a repeatable **VR-based evaluation framework** for avatar realism

---

##  Experimental Design

The experience is structured as a **guided VR experiment**, where users:

1. Observe a humanoid avatar under controlled conditions  
2. Interact with the avatar using natural gestures and head motion  
3. Experience variations in:
   - Lip sync accuracy
   - Eye movement behavior
   - Facial tracking smoothing and latency
4. Provide qualitative feedback on realism, comfort, and eeriness

This design allows isolating individual variables while maintaining immersion.

---

##  Key Features

### Facial Tracking Accuracy
- Real-time facial expression mapping from user to avatar
- Emphasis on temporal coherence and latency reduction

### Tracking-Based Lip Sync
- Lip motion driven directly by facial tracking data  
- Avoids audio-only phoneme estimation to preserve expression consistency

### Eye Subtle Motion System
- Procedural blinking with randomized intervals
- Micro eye movements and gaze stabilization
- Prevents unnatural “static stare” artifacts

### Controlled Noise & Imperfections
- Adjustable smoothing and jitter parameters
- Used to study tolerance thresholds in user perception

### Natural Hand Interaction
- Gesture-based interaction using hand tracking
- Supports more embodied and intuitive user engagement

---

##  Technology Stack

**Hardware**
- Meta Quest Pro (facial, eye, and hand tracking)

**Engine**
- Unity

**Languages**
- C#

**SDKs & Tools**
- Meta Movement SDK (Body & Facial Tracking)
- OpenXR
- Oculus Integration SDK
- Unity Animator & BlendShape system

---

##  Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/THANKSHANK/UncannyValleyVR.git
   cd UncannyValleyVR
2. Open the project in Unity (recommended LTS version).
3. Install required packages:
  -  Oculus Integration
  -  OpenXR
  -  Meta Movement SDK
4. Connect Meta Quest Pro and enable:
  -  Facial Tracking
  -  Eye Tracking
  -  Hand Tracking
5. Build and run the project in VR mode.

## Usage

Launch the VR experience and follow on-screen instructions

Observe avatar facial behavior under different configurations

Interact naturally using gaze, head movement, and gestures

Provide feedback through guided prompts or post-experience surveys

## Findings & Insights

High facial tracking accuracy alone does not guarantee realism

Subtle eye motion significantly reduces perceived eeriness

Temporal stability is often more important than raw accuracy

Small, well-controlled imperfections can sometimes improve perceived naturalness

These observations support existing uncanny valley research while demonstrating the importance of dynamic facial cues in VR.

## Limitations

Limited avatar diversity

Small-scale user testing

Focused on facial cues rather than full-body realism

Hardware-dependent (Quest Pro tracking features)


## Future Work

AI-driven facial animation blending

Expanded user study and quantitative metrics

Support for additional XR headsets

Integration with FACS-based expression analysis

Machine learning–assisted noise modeling


## Author

Zihan Wang (王滋涵)
VR / XR Developer · Computer Graphics · HCI

GitHub: https://github.com/THANKSHANK

Portfolio: [https://zihanwg.github.io//zihanw.github.io](https://zihanwg.github.io/ZihanW.github.io)
Related Write-up

Project blog & technical notes:
[https://zihanwportfolio.wordpress.com/2025/05/06/uncanny-valley-vr/](https://zihanwportfolio.wordpress.com/2024/11/30/uncanny-valley-exploration-in-vr/)
