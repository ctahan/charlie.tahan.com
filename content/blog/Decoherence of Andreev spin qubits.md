---
title: "Decoherence of Andreev spin qubits"
date: 2025-04-12
tags:
  - blog
  - LinkedIn
---
> [!info] Originally published on LinkedIn
> **[Decoherence of Andreev spin qubits](https://www.linkedin.com/feed/update/urn:li:activity:7316841811195408384/)**
>
> Apr 12, 2025 | Charles Tahan
>
> This is an archived copy of a LinkedIn post. The original is at the link above.

---

With the craziness of the last few months, I forgot to highlight some recently published work on the decoherence of Andreev spin qubits led by Silas Hoffman in a team spread across LPS and MIT Lincoln Laboratory.

Hybrid superconductor-semiconductor systems are super interesting to me for both science and technology. A topological qubit may be the epitome of this journey because its performance is entirely different from what you would predict for superconducting or spin qubits. But there are intermediary situations which can teach us a lot.

The Andrew spin qubit exists as a sort of true mashup of spin and superconducting qubits. It’s a spin qubit trapped in a bound state that forms between two superconductors, and it takes on the properties of both. That’s interesting for a number of reasons, a few are that you can make them bigger than spin qubits otherwise would be, that you have more knobs to turn (like the phase between the superconductors), and maybe most technologically relevant, that there are new ways to readout and connect spin qubits through the superconducting circuit.

But the coherence time of these qubits measured to date are not good. The question was why. For spin qubits we found out pretty quickly that the nuclear spins prevalent in III-V semiconductor quantum dots limit coherence to tens of nanoseconds during gates. If you get rid of them, like in isotopically enriched silicon or germanium, this error mechanism decreases by orders of magnitude. But that is not obviously true for Andreev spin qubits, where the amount of “spin” itself can be tuned and there are potentially worse decoherence wmechanisms coming from the nature of the system. I mean, one way to think of Andreev spin qubits is that a super-current is flowing throw them all the time! That seems scary to me!

In this paper published in Physical Review B we take a stab at a theoretical model that would elucidate the effects of different decoherence mechanisms, those from magnetic or charge sources. Check it out below.

In short, it seems like our gut instinct was right: the poor coherence times are due to being in a nuclear spin 1/2 rich semiconductor. This is good news in the sense that assuming these type of qubits are realizable in germanium, for example, the coherence time should greatly increase. (Theorists are never wrong after all.)

It’s not quite that boring though. The theory gives a guide for experimentalists to verify what we predict. And there should be areas of parameter space where the nuclear source of noise can be turned off to an extent.

Now, I’m not saying that these Andreev spin states will make good qubits in the end. But they are interesting.

PRB: https://link.aps.org/doi/10.1103/PhysRevB.111.045304

arXiv: https://arxiv.org/abs/2403.00710
