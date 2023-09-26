# Physics 1140 Exam 1 Crib Sheet

## Types of waves

### Concepts of waves

A wave is a pattern of motion. Waves can change through time, through space, or through time and space. If a wave is moving, then its motion obeys:

$$
v = \lambda f = \frac{\lambda}{T}
$$

Additionally, waves have a quantity called the **phase** $\phi$, which is the angular measure of how much of a cycle they have covered - a phase of $2\pi$ is a complete cycle. Phase can be calculated for spacial waves with:

$$
\phi = \frac{2\pi}{\lambda} (x - x_0)
$$

And for temporal waves with:

$$
\phi = \frac{2\pi}{T} (t - t_0)
$$

The **phase shift** is how much shifted to the right a wave is. It can be determined visually by how much of a cycle is missing from the front of the wave. For a wave that has a portion of $\frac{1}{n}$ cycles missing, the phase shift is $\frac{\pi}{2n}$.

### Harmonic waves

A harmonic wave is a stationary 1D wave that can be represented by:

$$
y(t) = A \sin(\omega t + \phi_0)
$$

Here, $\phi_0$ is the phase shift, $A$ is the amplitude, and $\omega = \frac{2\pi}{T} = 2\pi f$ is the angular frequency.

### Travelling waves

A travelling wave is a moving 2D wave that can be represented by:

$$
y(x, t) = y_m \sin (k(x - vt) + \phi_0)
$$

Here, $k = \frac{2\pi}{\lambda}$ and is the wavenumber, and $\omega = 2\pi f$.

## Interference

When two waves with a phase difference add, they interfere, according to:

$$
\small y_3 (t) = 2y_0 \cos \left(\frac{\phi_1 - \phi_2}{2} \right) \sin \left(\omega t + \frac{\phi_1 + \phi_2}{2}\right)
$$

The amplitude of the new sine wave is:

$$
A = 2y_0 \cos \left(\frac{\phi_1 - \phi_2}{2} \right)
$$

The time-averaged intensity $I_R$ of two waves is given by:

$$
I_R = I_1 + I_2 + 2\sqrt{I_1 I_2} \cos(\Delta \phi)
$$

If the two original waves had the same intensity and have a phase difference $\Delta \phi$, then:

$$
I_R = 4 I_1 \cos^2 \left(\frac{\Delta \phi}{2}\right)
$$

## Michelson interferometer

The intensity at the detector is given by:

$$
I_{detector} = I_0 \cos^2 \left(\frac{2\pi}{\lambda}|A - B|\right)
$$

where $A$ and $B$ are the two individual path lengths between the mirror and beam-splitter.

## Light 

The intensity of light is given by:

$$
I = \phi E = \phi hf
$$
where $\phi$ is the flux, given by:

$$
\phi = \frac{N}{A t}
$$

## Young double-slit experiment

Given light waves passing through two slits separated by distance $d$ which are a distance $D$ from a distant screen, and that a peak (maximum) in the observed interference pattern on the screen is $m$ wavelengths from the center of the screen, then:

$$
\theta = \frac{y}{D}
$$

$$
y = m \lambda
$$

$$
\lambda = \frac{d \sin \theta}{m}
$$

## Quantum mechanics

Light is composed of quanta called photons. The energy of a photon is given by:

$$
E = hf
$$

where $h$ is Planck's constant.

## Photoelectric effect

Light is incident on a metal cathode placed in a vacuum chamber. If photons have sufficiently high frequency, then they eject electrons from the cathode, causing a current. The **stopping potential** $V_0 = -\Delta V$ is the potential that results in no current, and is given by:

$$
V_0 = 
\begin{cases}
0, f < f_0 \\\\
\frac{hf}{e} - \frac{h f_0}{e}, f \geq f_0
\end{cases}
$$

Millikan found that the stopping potential depends only on the **frequency** of the incident light wave, and **not** on the intensity of the light. No current is observed when light has a frequency below a _threshold_ frequency $f_0$. The (confusingly-named) work function, the energy of a photon of the threshold frequency, is given by $W = hf_0$, and is a constant.
