# 🌟 Spin-Photon Entanglement: How to Build a Quantum Walkie-Talkie!

Welcome! Have you ever wondered how to send a secret message across the planet instantly without anyone being able to snoop or copy it? 

Ordinary computers (Classical; regular laptops for example) use electrical pulses along wires, basically using electricity to transmit information. But in a different architecture, we can use **sparkling crystals**, **spinning atoms**, and **packets of light (photons)** to build the future Quantum Internet! In scientific terms, its the color centers in Silicon Carbide (SiC).

---

## 📖 Table of Contents
- [The Superpower: Spinning Coins (Qubits)](#-the-superpower-spinning-coins-qubits)
- [Why You Cannot Photocopy Quantum Secrets](#-why-you-cannot-photocopy-quantum-secrets)
- [Meet the Characters: The Vault and the Messenger](#-meet-the-characters-the-vault-and-the-messenger)
- [The Magic Trick: Turning Spin into Light](#-the-magic-trick-turning-spin-into-light)
- [The Magic Mirror (Beam Splitter)](#-the-magic-mirror-beam-splitter)
- [Why Don't We Have This Everywhere Yet?](#-why-dont-we-have-this-everywhere-yet)
- [Quick Summary Cheat Sheet](#-quick-summary-cheat-sheet)

---

## The Superpower: Spinning Coins (Qubits)

In regular computers (like your phone or game console), information is stored as **bits**:
* A regular bit is like a coin lying flat on a table. It is either **Heads** ($0$) or **Tails** ($1$).

In quantum mechanics, things get wild:
* A quantum bit (or **qubit**) is like a **coin spinning fast on a table**. While it spins, is it Heads or Tails? It is a blend of **both at the same time**! Physicists call this **superposition**.

---

## Why You Cannot Photocopy Quantum Secrets

Normally, if an internet signal gets weak over long cables, a booster machine reads the signal, copies it, and sends fresh copies down the road.

Nature has a strict rule called the **No-Cloning Theorem**:
> **You cannot make an exact photocopy of an unknown quantum secret.**

If anyone tries to look at or copy our spinning coin midway, it instantly falls flat and the secret vanishes! To send information far away, we cannot copy it—we must **teleport** it using **entanglement** (connecting two particles like invisible twins).

---

## Meet the Characters: The Vault and the Messenger

Inside our quantum computer sits a tough crystal called **Silicon Carbide (4H


# The Young Physicist's Guide to Quantum Repeaters: An Unbroken Story of Light, Spins, and Equations

Imagine you are standing at the edge of a new technological era. We want to build an unhackable planetary network called the Quantum Internet, connecting processors across continents. In the everyday digital world, computers speak in ordinary bits, which are physical switches that must be completely off ($0$) or completely on ($1$). But nature at its deepest level does not play by these rigid classical rules. Atoms and electrons obey quantum mechanics, where an object can exist in an unresolved blend of both possibilities at once. To build our network, our fundamental currency is the quantum bit, or qubit. We represent this state using Paul Dirac's bracket notation as a ket vector:

$$
\vert\psi\rangle = \alpha\vert 0\rangle + \beta\vert 1\rangle
$$

Here, $\vert 0\rangle$ and $\vert 1\rangle$ act as the baseline states, much like the heads or tails of a coin suspended in mid-air. The coefficients $\alpha$ and $\beta$ are probability amplitudes, which are complex numbers containing both magnitude and phase. When you finally force the qubit to reveal itself through an observation, the probability of measuring state $\vert 0\rangle$ is precisely $\vert\alpha\vert^2$, while the probability of measuring state $\vert 1\rangle$ is $\vert\beta\vert^2$. Because an outcome must occur, nature enforces the strict normalization condition:

$$
\vert\alpha\vert^2 + \vert\beta\vert^2 = 1
$$

When both amplitudes share an equal magnitude of $1/\sqrt{2}$, calculating their squared values yields $\vert 1/\sqrt{2}\vert^2 = 1/2$, meaning there is an exact fifty-fifty chance of finding either state. This defines a balanced superposition: $\vert\psi\rangle = \frac{1}{\sqrt{2}}(\vert 0\rangle + \vert 1\rangle)$.

Now, you might wonder why we cannot simply send this delicate qubit through standard telecom fibers the way internet providers transmit streaming video. In an ordinary fiber-optic line, light fades over distance, so engineers install repeaters every eighty kilometers to measure the incoming pulses, amplify them, and spit out fresh copies. But in quantum physics, this instinct hits an impenetrable brick wall known as the No-Cloning Theorem. It is mathematically impossible to construct a universal machine that takes an unknown quantum state and duplicates it without destroying the original superposition.

To see why this is true, consider an imaginary cloning machine operating through a unitary operator $U_{\text{clone}}$ that attempts to stamp any state $\vert\psi\rangle$ onto a blank target qubit $\vert 0\rangle$:

$$
U_{\text{clone}}(\vert\psi\rangle \vert 0\rangle) = \vert\psi\rangle \vert\psi\rangle
$$

If you feed pure state $\vert 0\rangle$ into this operator, it reliably outputs two zeros:

$$
U_{\text{clone}}(\vert 0\rangle \vert 0\rangle) = \vert 0\rangle \vert 0\rangle
$$

Likewise, feeding it pure state $\vert 1\rangle$ yields two ones:

$$
U_{\text{clone}}(\vert 1\rangle \vert 0\rangle) = \vert 1\rangle \vert 1\rangle
$$

The disaster strikes the instant you feed it a superposition state $\vert\psi\rangle = \frac{1}{\sqrt{2}}(\vert 0\rangle + \vert 1\rangle)$. Because quantum evolution is strictly linear, the operator must distribute across each component independently, forcing the output to become:

$$
U_{\text{clone}}\left(\frac{\vert 0\rangle + \vert 1\rangle}{\sqrt{2}} \vert 0\rangle\right) = \frac{1}{\sqrt{2}}\vert 00\rangle + \frac{1}{\sqrt{2}}\vert 11\rangle
$$

Yet, if this machine had actually succeeded in cloning the entire state $\vert\psi\rangle$, basic algebra dictates that the true product state should have expanded into four distinct terms:

$$
\vert\psi\rangle \otimes \vert\psi\rangle = \left(\frac{\vert 0\rangle + \vert 1\rangle}{\sqrt{2}}\right)\left(\frac{\vert 0\rangle + \vert 1\rangle}{\sqrt{2}}\right) = \frac{1}{2}\vert 00\rangle + \frac{1}{2}\vert 01\rangle + \frac{1}{2}\vert 10\rangle + \frac{1}{2}\vert 11\rangle
$$

The machine completely failed to produce the cross-terms $\vert 01\rangle$ and $\vert 10\rangle$. The mathematics proves that copying an unknown qubit is fundamentally forbidden by the laws of our universe. Because we cannot copy qubits to extend their range, we are forced to take a completely different path: we must establish quantum entanglement across distant nodes, using light to stitch stationary matter memories together.

This realization brings us straight to the physical hardware. Where do we store these fragile quantum states while waiting for network signals to cross a continent? We cannot use fragile isolated atoms floating in vacuum chambers if we want scalable, commercial technology. Instead, we use solid-state chips made of Silicon Carbide (4H-SiC), an industrial semiconductor already mass-manufactured for high-power electric vehicles. Inside the crystalline grid of silicon and carbon atoms, scientists engineer a microscopic point defect called a divacancy, formed where a silicon atom and an adjacent carbon atom are missing from their lattice sites.

This tiny divacancy functions as a microscopic atom trapped in crystal, housing two distinct spin systems that play opposite, complementary roles. Deep in the defect sits a single Silicon-29 atomic nucleus with nuclear spin $I = 1/2$. Because this nucleus is physically small and buried beneath electron clouds, it is shielded from thermal vibrations, acting as an isolated memory vault. Surrounding this nucleus is the electronic spin of the divacancy itself, possessing spin $S = 1$. The electron spin couples strongly to optical light and microwave pulses, acting as a reactive messenger.

The interaction between the electron messenger and the nuclear vault is governed by the spin Hamiltonian:

$$
H = D S_z^2 + \gamma_e B_z S_z + A_{zz} S_z I_z + \gamma_n B_z I_z
$$

In this energy expression, $D S_z^2$ represents the ground-state zero-field splitting ($D = 1.334\text{ GHz}$), separating the $m_s = 0$ sublevel from the $m_s = \pm 1$ sublevels even in zero magnetic field. The term $\gamma_e B_z S_z$ denotes the Zeeman interaction with an applied static magnetic field $B_z$, tuning the operational levels. Crucially, the cross-term $A_{zz} S_z I_z$ represents the longitudinal hyperfine coupling ($A_{zz} \approx 1.20\text{ MHz}$) between the electron spin $S_z$ and the $^{29}\text{Si}$ nuclear spin $I_z$. This magnetic bond allows us to transfer quantum information between the two spins at will.

We begin each networking attempt by initializing the nuclear memory into a balanced superposition:

$$
\vert\psi_n\rangle = \frac{1}{\sqrt{2}}\left(\vert 0\rangle_n + \vert 1\rangle_n\right)
$$

Because the nuclear vault is so well protected, its off-diagonal quantum coherence decays remarkably slowly, following an exponential relaxation curve:

$$
\rho_{01}(t) = \rho_{01}(0) \cdot \exp\left(-\frac{t}{T_{2,n}^*}\right)
$$

In 4H-SiC, the nuclear coherence time reaches $T_{2,n}^* \approx 0.50\text{ seconds}$ ($500{,}000\ \mu\text{s}$). If a communication round takes $t = 274\ \mu\text{s}$ for light to make a round trip across a 50-kilometer link, the surviving coherence fraction is:

$$
\exp\left(-\frac{2.74 \times 10^{-4}\text{ s}}{0.50\text{ s}}\right) = \exp(-0.000548) \approx 0.99945 = 99.945\%
$$

The nuclear vault retains over $99.9\%$ of its quantum secret while waiting for network signals to return.

Once the nuclear register is prepared, we must convert this stored stationary state into a traveling photonic signal. To begin this conversion, we apply a microwave dynamical decoupling pulse sequence lasting $\tau_{\text{swap}} = 12.0\ \mu\text{s}$. This executes an effective unitary SWAP gate, transferring the quantum state from the nuclear vault onto the electron bus:

$$
U_{\text{SWAP}}\vert\psi\rangle_n \vert 0\rangle_e = \vert 0\rangle_n \vert\psi\rangle_e
$$

In our simulation, we account for realistic laboratory imperfections by assigning this operation a gate fidelity $\mathcal{F}_{\text{gate}} = 0.992$, introducing a small depolarizing error probability $p_{\text{error}} = 2(1 - \mathcal{F}_{\text{gate}}) = 0.016$.

With the quantum state now loaded onto the electron spin bus ($\vert\psi_e\rangle = c_0\vert 0\rangle_e + c_1\vert 1\rangle_e$), we can finally generate spin-photon entanglement. We fire a resonant optical laser pulse tuned directly to the defect's zero-phonon line (ZPL) at wavelength $\lambda = 1078.0\text{ nm}$. This optical transition is strictly state-selective: it resonantly couples the electron spin state $\vert 1\rangle_e$ to an orbital excited state $\vert e\rangle$, while leaving state $\vert 0\rangle_e$ completely dark and unaffected.

When the excited electron drops back down, spontaneous emission releases a single flying photon into a nearby on-chip waveguide:

$$
\vert 1\rangle_e \xrightarrow{\text{spontaneous emission}} \vert 0\rangle_e \vert 1\rangle_{\text{photon}}
$$

Accounting for a tunable optical excitation probability $p_e$, the joint electron-photon state evolves into an entangled superposition:

$$
\vert\psi_{e,\text{ph}}\rangle = c_0 \vert 0\rangle_e \vert 0\rangle_{\text{ph}} + c_1 \sqrt{p_e}\vert 1\rangle_e \vert 1\rangle_{\text{ph}} + c_1 \sqrt{1 - p_e}\vert 1\rangle_e \vert 0\rangle_{\text{ph}}
$$

When the excitation probability is set to unity ($p_e = 1.0$), the system collapses into a pure spin-photon entangled pair:

$$
\vert\psi_{e,\text{ph}}\rangle = c_0 \vert 0\rangle_e \vert 0\rangle_{\text{ph}} + c_1 \vert 1\rangle_e \vert 1\rangle_{\text{ph}}
$$

The presence or absence of a photon traveling down the fiber is now bound to the magnetic orientation of the electron trapped on the chip.

Now that both Node A and Node B have launched their spin-entangled photons, the scene shifts from the chips to the fiber network. Both photons travel through optical fiber arms of length $L_0 = L/2$ toward a central entangling station located halfway between the nodes. The core engine of this central station is a 50:50 non-polarizing beam splitter, which acts as a half-silvered mirror with two input ports and two output ports monitored by superconducting detectors.

In the language of quantum optics, incoming photons are represented by creation operators $a^\dagger$ for Node A and $b^\dagger$ for Node B, while outgoing photons heading toward the detectors are represented by $c_1^\dagger$ and $c_2^\dagger$. The beam splitter performs a unitary matrix transformation mixing these optical modes:

$$
\begin{pmatrix} c_1^\dagger \\ c_2^\dagger \end{pmatrix} = \frac{1}{\sqrt{2}} \begin{pmatrix} 1 & 1 \\ 1 & -1 \end{pmatrix} \begin{pmatrix} a^\dagger \\ b^\dagger \end{pmatrix}
$$

Inverting this relationship expresses the original emitter modes in terms of the detector modes:

$$
a^\dagger = \frac{1}{\sqrt{2}}\left(c_1^\dagger + c_2^\dagger\right), \quad b^\dagger = \frac{1}{\sqrt{2}}\left(c_1^\dagger - c_2^\dagger\right)
$$

This mathematical mixing produces quantum erasure. Consider the case where exactly one photon was emitted across the two nodes. The joint state entering the beam splitter is:

$$
\vert\Psi_{\text{input}}\rangle = \frac{1}{\sqrt{2}}\left(\vert 10\rangle_{AB} a^\dagger + \vert 01\rangle_{AB} b^\dagger\right)\vert\text{vacuum}\rangle
$$

When we substitute the beam splitter transformation into this input state, the optical expressions expand into:

$$
\vert\Psi_{\text{output}}\rangle = \frac{1}{\sqrt{2}}\left[\vert 10\rangle_{AB} \left(\frac{c_1^\dagger + c_2^\dagger}{\sqrt{2}}\right) + \vert 01\rangle_{AB} \left(\frac{c_1^\dagger - c_2^\dagger}{\sqrt{2}}\right)\right]\vert\text{vacuum}\rangle
$$

Regrouping these terms according to which detector receives light reveals the underlying physics:

$$
\vert\Psi_{\text{output}}\rangle = \frac{1}{2} c_1^\dagger \underbrace{\left(\vert 10\rangle_{AB} + \vert 01\rangle_{AB}\right)}_{\text{Bell State } \vert\Psi^+\rangle} + \frac{1}{2} c_2^\dagger \underbrace{\left(\vert 10\rangle_{AB} - \vert 01\rangle_{AB}\right)}_{\text{Bell State } \vert\Psi^-\rangle}
$$

This equation explains how remote entanglement is born. If Detector 1 registers a click ($c_1^\dagger$), the wave function collapses into the symmetric maximally entangled Bell state:

$$
\vert\Psi^+\rangle = \frac{1}{\sqrt{2}}\left(\vert 01\rangle + \vert 10\rangle\right)
$$

If Detector 2 registers a click ($c_2^\dagger$), the state projects onto the antisymmetric Bell state:

$$
\vert\Psi^-\rangle = \frac{1}{\sqrt{2}}\left(\vert 01\rangle - \vert 10\rangle\right)
$$

Because the beam splitter reflects and transmits with equal fifty-percent amplitudes, it is impossible even in principle to deduce which chip emitted the photon. Nature erases the which-way information, and in doing so, forces the two separate Silicon Carbide nodes into a shared entangled state.

A fascinating quantum phenomenon called Hong-Ou-Mandel bunching occurs if both nodes emit a photon at the exact same instant ($a^\dagger b^\dagger$). Expanding their product through the beam splitter yields:

$$
a^\dagger b^\dagger = \left(\frac{c_1^\dagger + c_2^\dagger}{\sqrt{2}}\right)\left(\frac{c_1^\dagger - c_2^\dagger}{\sqrt{2}}\right) = \frac{1}{2}\left(c_1^{\dagger 2} - c_1^\dagger c_2^\dagger + c_2^\dagger c_1^\dagger - c_2^{\dagger 2}\right)
$$

Because bosonic photon operators commute ($c_1^\dagger c_2^\dagger = c_2^\dagger c_1^\dagger$), the cross-terms subtract to zero:

$$
a^\dagger b^\dagger = \frac{1}{2}\left(c_1^{\dagger 2} - c_2^{\dagger 2}\right)
$$

Two identical photons never exit through opposite ports. They bunch together, either exiting into Detector 1 ($c_1^{\dagger 2}$) or Detector 2 ($c_2^{\dagger 2}$). Coincident clicks between both detectors simultaneously are forbidden by quantum interference.

However, transmitting light across kilometers of optical fiber introduces significant physical channel loss. Glass fibers absorb photons exponentially over distance according to the attenuation equation:

$$
T_{\text{fiber}}(L) = 10^{-\frac{\alpha \cdot (L/2)}{10}}
$$

Here, $L/2$ is the length of each fiber arm, and $\alpha = 0.20\text{ dB/km}$ is the attenuation coefficient of high-purity silica fiber at the standard telecom C-band wavelength of $1550\text{ nm}$. For a total separation distance of $L = 10\text{ km}$ ($5\text{ km}$ per arm), the fiber loss is $0.20 \times 5 = 1.0\text{ dB}$, yielding a transmittance of $T_{\text{fiber}} = 10^{-0.10} \approx 0.794$, meaning $79.4\%$ of photons survive. Over an intercity link of $L = 50\text{ km}$ ($25\text{ km}$ per arm), the loss grows to $0.20 \times 25 = 5.0\text{ dB}$, cutting the transmittance to $T_{\text{fiber}} = 10^{-0.50} \approx 0.316$, meaning only $31.6\%$ survive.

To determine whether an emitted photon triggers an electrical click at the entangling station, we calculate the total single-arm efficiency $\eta_{\text{total}}$ by compounding every transmission bottleneck:

$$
\eta_{\text{total}} = \eta_{\text{coll}} \cdot \eta_{\text{wg}} \cdot \eta_{\text{qfc}} \cdot T_{\text{fiber}} \cdot \eta_{\text{det}}
$$

In our Silicon Carbide model, the extraction efficiency from the crystal bulk into a solid immersion lens is $\eta_{\text{coll}} = 0.35$, the nanophotonic waveguide transmission is $\eta_{\text{wg}} = 0.75$, the quantum frequency conversion efficiency converting the defect's native $1078\text{ nm}$ emission to the low-loss $1550\text{ nm}$ telecom band is $\eta_{\text{qfc}} = 0.50$, and the superconducting nanowire single-photon detector (SNSPD) efficiency is $\eta_{\text{det}} = 0.90$. Over a 10-kilometer link, compounding these hardware efficiencies results in:

$$
\eta_{\text{total}} = 0.35 \times 0.75 \times 0.50 \times 0.794 \times 0.90 \approx 0.0938 = 9.38\%
$$

This compounding photon loss forces a critical architectural choice between two distinct entangling protocols: Barrett-Kok and Cabrillo.

The Barrett-Kok protocol prioritizes quantum phase safety. It executes two consecutive optical rounds separated by an electron spin bit-flip ($\pi$-pulse: $\vert 0\rangle \leftrightarrow \vert 1\rangle$). Suppose temperature fluctuations and acoustic vibrations stretch the fiber, introducing an unknown optical phase shift $\Delta\phi(t) = \phi_A(t) - \phi_B(t)$. In Round 1, a single photon click projects the chips onto:

$$
\vert\psi_1\rangle = \frac{1}{\sqrt{2}}\left(\vert 01\rangle + e^{i\Delta\phi_1}\vert 10\rangle\right)
$$

Both chips immediately invert their electron spins using microwave pulses:

$$
\vert\psi_1'\rangle = \frac{1}{\sqrt{2}}\left(\vert 10\rangle + e^{i\Delta\phi_1}\vert 01\rangle\right) = \frac{e^{i\Delta\phi_1}}{\sqrt{2}}\left(\vert 01\rangle + e^{-i\Delta\phi_1}\vert 10\rangle\right)$$

When the second optical pulse is applied in Round 2, the subsequent single-photon click imparts an opposing phase shift:

$$
\vert\psi_2\rangle \propto \vert 01\rangle + e^{i(\Delta\phi_2 - \Delta\phi_1)}\vert 10\rangle
$$

Because both rounds complete within a few microseconds, the thermal environment of the fiber cannot change appreciably, meaning $\Delta\phi_2 \approx \Delta\phi_1$. The phase shifts cancel out identically:

$$
e^{i(\Delta\phi_2 - \Delta\phi_1)} = e^0 = 1 \implies \vert\Psi^+\rangle = \frac{1}{\sqrt{2}}\left(\vert 01\rangle + \vert 10\rangle\right)
$$

The optical phase noise vanishes from the heralded state. However, because two photons must survive the channel across consecutive rounds, the success probability scales quadratically with link efficiency:

$$
P_{\text{succ}}^{\text{BK}} \approx \frac{1}{2}\eta_{\text{total}}^2
$$

At a distance of $50\text{ km}$, where $\eta_{\text{total}} \approx 0.037$, the squared term drops to $\eta_{\text{total}}^2 \approx 0.0014$, pulling the entanglement generation rate down to $2.55\text{ Hz}$.

The Cabrillo single-photon protocol takes the opposite trade-off, prioritizing communication speed. By exciting both emitters weakly ($p_e \approx 0.03$ or $3\%$), a single detector click heralds entanglement. Its success probability scales linearly with channel transmission:

$$
P_{\text{succ}}^{\text{SP}} \approx 2 p_e (1 - p_e) \eta_{\text{total}}
$$

At $50\text{ km}$, this linear scaling delivers an entanglement rate of $8.55\text{ Hz}$—more than $3.4\times$ faster than Barrett-Kok. However, this speed comes with vulnerabilities. If both nodes emit photons simultaneously (an event occurring with probability $p_e^2$) and one photon is lost in the fiber while the other is detected, the chips collapse into an unentangled error state $\vert 11\rangle$:

$$
\text{Error}_{\text{double}} \approx p_e(1 - \eta_{\text{total}})
$$

Furthermore, because there is no second round to cancel phase drift, fiber vibrations wash out off-diagonal quantum coherence according to a Gaussian expectation value:

$$
\langle e^{i\Delta\phi}\rangle = \exp\left(-\frac{\sigma_\phi^2}{2}\right)
$$

If acoustic phase jitter in the fiber exceeds $\sigma_\phi > 0.25\text{ rad}$ (about $14^\circ$), the entanglement fidelity falls below $90\%$.

Finally, to grade how well our simulated repeater functions, we quantify the generated state using density matrix metrics. The first metric is Bell State Fidelity ($\mathcal{F}$), which measures the mathematical projection of our real physical density matrix $\rho$ onto the ideal target state $\vert\Psi^+\rangle$:

$$
\mathcal{F} = \langle\Psi^+\vert \rho \vert\Psi^+\rangle = \frac{1}{2}\left(\rho_{01,01} + \rho_{10,10} + 2\text{Re}(\rho_{01,10})\right)
$$

A score of $\mathcal{F} = 1.0$ represents a flawless Bell state, while any value strictly above $0.50$ exceeds classical correlation bounds, proving the presence of genuine quantum entanglement. In our 4H-SiC simulation, Barrett-Kok achieves a fidelity of F_BK ≈ 0.967 (96.7%), while the single-photon protocol achieves F_SP ≈ 0.938 (93.8%).

The second metric is Wootters Concurrence ($\mathcal{C}$), which measures the non-classical entanglement of formation for an arbitrary mixed state. We compute the spin-flipped density matrix:

$$
\tilde{\rho} = \left(\sigma_y \otimes \sigma_y\right) \rho^* \left(\sigma_y \otimes \sigma_y\right)
$$

where the Pauli-Y operator is:

$$
\sigma_y = \begin{pmatrix} 0 & -i \\ i & 0 \end{pmatrix}
$$

Taking the matrix product $\rho\tilde{\rho}$, we extract the square roots of its eigenvalues sorted in descending order, $\lambda_1 \ge \lambda_2 \ge \lambda_3 \ge \lambda_4$, yielding the concurrence:

$$
\mathcal{C}(\rho) = \max\left(0, \lambda_1 - \lambda_2 - \lambda_3 - \lambda_4\right)
$$

A concurrence of $\mathcal{C} = 0$ indicates a separable classical state, while $\mathcal{C} = 1$ denotes maximal entanglement. Our Silicon Carbide simulation yields C_BK ≈ 0.935 and C_SP ≈ 0.902, confirming that the generated state carries dense quantum entanglement.

By walking through this sequence—from the initial qubit definition and the no-cloning restriction, through local spin Hamiltonian control in Silicon Carbide, optical spin-photon emission, beam splitter interference, and channel loss scaling—we obtain an end-to-end mathematical description of how distant quantum chips can be entangled across metropolitan distances.
