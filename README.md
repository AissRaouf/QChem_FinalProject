# Spooky Quantum Barrier Scattering

A computational exploration of quantum mechanical scattering 
in natural units (ℏ=1, m=1). This notebook implements exact 
plane-wave scattering solutions for two barrier models, WKB 
approximation, and Gaussian wavepacket analysis.

## Features
- Exact analytic T(E) and R(E) for square and Eckart (sech²) barriers
- Three-regime solver: tunneling, threshold, and above-barrier reflection
- Above-barrier resonance finder (Fabry-Pérot condition q·a = nπ)
- WKB approximation vs exact comparison in the tunneling regime
- Gaussian wavepacket momentum-space analysis and average transmission
- Probability conservation verified to machine precision across all energies

## Physics Highlights
- Tunneling: T > 0 even when E < V₀ (classically forbidden)
- Above-barrier reflection: T < 1 even when E > V₀ (classically unexpected)
- Resonances: T = 1 when integer half-wavelengths fit inside barrier
- Wavepacket: ⟨T⟩ converges to plane-wave T(E₀) as σₖ → 0

## Units
All calculations use natural units: ℏ = 1, m = 1
k = √(2E),  κ = √(2(V₀−E))
