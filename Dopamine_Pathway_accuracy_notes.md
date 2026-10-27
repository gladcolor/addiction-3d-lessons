# Dopamine Pathway page: accuracy corrections (2026-10-27)

Two independent reviews checked all student-facing text (captions, tips, tables, glossary, Chinese teacher notes). Every finding below was checked against the cited source and applied to `Dopamine_Pathway_3D.html`.

## Errors fixed

| Where | Was | Now | Source |
|---|---|---|---|
| Takeaways card | "tolerance and craving outlast the drug" | Craving can last months; **tolerance fades during a break, so an old dose after a break can cause an overdose** | Strang et al. 2003 BMJ; Binswanger et al. 2007 NEJM |
| Takeaways card | ΔFosB linked to tolerance; "the long-term change is at the finish" | ΔFosB switches genes on and off; lasting changes also happen at station 1 | McClung & Nestler 2003; Ungless et al. 2001 Nature |
| Station 5 text | "every one of the six changes this station (fewer D2)" | Drug use does; gambling disorder usually shows normal D2; opioids also act on accumbens μ receptors | Clark et al. 2012; Boileau et al. 2013 |
| Gambling quiz | "No molecule is involved" | No drug is involved; the brain uses its own glutamate, GABA and dopamine | Schultz 2016 |

## Misleading statements corrected

| Topic | Change | Source |
|---|---|---|
| Nicotine long term | Smokers do not clearly show fewer D2 receptors; the "Healthy vs addicted" nicotine machine keeps all D2 cups | Ashok, Mizuno & Howes 2019 Psychopharmacology |
| Cocaine and firing | "does not act on the rotor itself"; the slowing via autoreceptors is real but the model shows a mild version | Lüscher & Ungless 2006; Einhorn et al. 1988; Koulchitsky et al. 2012 |
| Metro and 3D teacher notes | No longer say cocaine leaves firing unchanged | Lüscher & Ungless 2006 |
| "Take the drug" (Chinese note) | Now matches the English: large rise only for cocaine and meth; "feel normal" only for the milder drugs | Di Chiara & Imperato 1988; Volkow et al. 1997 |

## Smaller precision fixes

- ΔFosB "switches genes on or off" (not only "on"); with opioids it builds up in both D1 and D2 cells (Robison & Nestler 2011; Lobo et al. 2013).
- Opioids: part of their reward does not need dopamine (Hnasko et al. 2005; Fields & Margolis 2015).
- Alcohol: excites dopamine neurons directly, plus quiets the GABA brake (Brodie et al. 1999; Morikawa & Morrisett 2010).
- Nicotine: also strengthens glutamate input and, after minutes, weakens the GABA brake (Mansvelder & McGehee 2002).
- Near-miss: "brain scans suggest it acts like a smaller win" (fMRI evidence, not recorded bursts; Clark et al. 2009).
- Gambling bursts come with surprise wins, not with uncertainty itself (Fiorillo, Tobler & Schultz 2003).
- D1 "low affinity" labeled as the standard model, with newer evidence that D1 and D2 cells respond more alike (Marcott et al. 2014; Hunger et al. 2020).
- D2 loss: one cup in the drawing; real scans show about 10 to 20 percent fewer, and some people may start with fewer (Volkow et al. 2001; Nader et al. 2006).
- Meth: VMAT2 loss is an animal finding; in people, scans show fewer DAT and less stored dopamine (Boileau et al. 2008; Volkow et al. 2001).
- Cannabis: about 20 percent fewer CB1 receptors, mainly cortical, back to normal after about a month (Hirvonen et al. 2012).
- Gambling disorder: slightly more dopamine synthesis and release (van Holst et al. 2018; Boileau et al. 2014).
- "Less dopamine per pulse" instead of "per package" (PET measures release, not vesicle content).
- Dopamine per vesicle: "几千到几万个" (Omiatek et al. 2013).
- Glossary: varicosities, reward prediction error (burst vs pause), D2 receptors (incl. autoreceptors), Parkinson's (substantia nigra), hippocampus (places and situations), pacemaker firing, cell body.
- Tetrabenazine question: "imagine it does nothing else"; answer note adds MAO breakdown and the meth contrast.
- "Two kinds of doors" card: cocaine keeps dopamine longer; meth pushes it out even when the neuron is quiet.

## Machine tab, 2026-10-27: seesaw brake, nicotine rockets, story notes

- GABA brake: a GABA pulse is drawn as the operator stepping on a seesaw pedal; the far end presses a red pad on the rim of the rotor hub. Opioids, alcohol and cannabis put the operator to sleep: the foot comes off and the pad drops (disinhibition; Johnson & North 1992 for opioids).
- Nicotine: nicotinic receptors (mainly α4β2) are drawn as small rockets on three rotor arms; nicotine is a copy of acetylcholine's key. Lit rocket = open channel, Na⁺ and Ca²⁺ flow in, the neuron fires more.
- New story step "Minutes later": the rockets burn out (desensitization of α4β2 on the dopamine neuron) while dopamine stays up, because α7 receptors on glutamate terminals keep adding glutamate (the glove pushes more often) and the GABA neurons' own α4β2 receptors desensitize (the operator brakes less). Mansvelder & McGehee 2000; Mansvelder, Keath & McGehee 2002; Pidoplichko et al. 1997.
- In the model this step sets desSet = 1: no direct push, drive +20 percent, GABA rate −35 percent, plus a two-spike glutamate burst every 3 to 5 s, so firing stays about where it was in the first seconds. The long-run numbers in captions and tables still use the acute model.
- Hours later: nicotine is turned into cotinine in the liver (mainly CYP2A6); cotinine has little action on these receptors.
- After months of smoking: up-regulation, a rocket on every arm, but between cigarettes many stay desensitized (Benwell et al. 1988; Perry et al. 1999; Staley et al. 2006 for SPECT imaging in smokers).
- The rocket flame stands for the push from ions flowing in. No "+" signs are drawn in the flame, because the ions move into the cell, not out of it.
- Story notes flash only for what the picture cannot show (calcium, VMAT2, receptor binding, where each drug binds and what it changes), one at a time, next to the part.
