# Addiction in 3D

Interactive 3D lessons for first-year biology on the molecular and cellular mechanisms of addiction, with a focus on opioids.

**Portal: https://gladcolor.github.io/addiction-3d-lessons/**

| Page | What it is |
|---|---|
| [The Molecular Game of Addiction](https://gladcolor.github.io/addiction-3d-lessons/Molecular_Game_of_Addiction.html) | A 50-minute active-learning session: 3D synapse, real opioid receptor structure, body explorer, team design challenge |
| [The Dopamine Pathway](https://gladcolor.github.io/addiction-3d-lessons/Dopamine_Pathway_3D.html) | One dopamine pathway in 3D, as a metro map and as an animated machine: where seven drugs and gambling break in, healthy vs addicted brains, a 3D brain of the three addiction systems (reward, control, stress and habit) with real specimen photos, a brain atlas of 78 regions (lobes, gyri, cortex areas, deep structures, brainstem, the twelve cranial nerves and the brain’s coverings) with a midline cut view, a drawing pen and image saving, fully in six languages, with name origins, pronunciation, everyday activities, real photos of 76 of the 78 regions with the region marked on each, a search by name or function, an Addiction mode ([addictions.win/#addiction](https://addictions.win/#addiction)) with step-by-step stories of which regions nicotine, alcohol, opioids, stimulants, cannabis, gambling and gaming involve and how they change, and a quiz in two forms (name the glowing region, or find a named region on the brain), a hands-on view, the Opioids tab (molecule, cells and the Brake Game), and a glossary in the six UN languages ([accuracy notes](Dopamine_Pathway_accuracy_notes.md)) |
| [Opioids in 3D](https://gladcolor.github.io/addiction-3d-lessons/Opioids_3D_Lesson.html) | A guided 40-minute lesson, from the whole body down to single proteins |
| [Opioids up close](https://gladcolor.github.io/addiction-3d-lessons/Dopamine_Pathway_3D.html#da) | The Opioids tab of The Dopamine Pathway: meet dopamine, five cell types and three molecule classes in 3D, and the [Brake Game](https://gladcolor.github.io/addiction-3d-lessons/Dopamine_Pathway_3D.html#game). The older standalone page, [Opioids_Cells_Molecules_3D.html](https://gladcolor.github.io/addiction-3d-lessons/Opioids_Cells_Molecules_3D.html), still works |

Each page is a single standalone HTML file, except that the Brain atlas tab of The Dopamine Pathway loads its 3D model from `brain_atlas_mesh.js`, its real photos from `brain_atlas_photos.js` and its recordings of the English region names from the `audio` folder, which must stay next to the page. The 3D views load three.js from a CDN, so an internet connection is needed. The pages are teaching models: they show the direction of each real effect, not its exact size or timing.

## License

© 2026 Huan Ning ([huanning.me](https://huanning.me))

The lessons in this repository (text, illustrations, simulations and code) are licensed under [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/). The full legal text is in [LICENSE](LICENSE).

- **Share and adapt** the lessons for teaching and other non-commercial uses.
- **Credit Huan Ning.** Link to this repository or to [addictions.win](https://addictions.win), link to the license, and say whether you changed anything.
- **No commercial use** without written permission.
- **Share alike.** If you publish an adapted version, publish it under CC BY-NC-SA 4.0 too.

Suggested credit line:

> "The Dopamine Pathway" by Huan Ning, https://addictions.win, licensed under CC BY-NC-SA 4.0. Adapted by [your name]: [what you changed].

For commercial use, please contact Huan Ning through [huanning.me](https://huanning.me).

### Third-party material

The items below keep their own licenses and are not covered by CC BY-NC-SA 4.0. The changes made for these lessons are noted in the first column.

| Material | Where | Source | License |
|---|---|---|---|
| Human anatomy meshes (simplified and compressed) | 3D lessons | [BodyParts3D](https://dbarchive.biosciencedbc.jp/en/bodyparts3d/lic.html), © The Database Center for Life Science | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Protein structures, reduced to Cα traces or one bead per residue (4DKL, 5C1M, 6DDE, 6HUP, 2HHB, 9EO4, 5KXI) | 3D lessons | [RCSB Protein Data Bank](https://www.rcsb.org) | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| Predicted protein structures, reduced to one bead per residue | 3D lessons | [AlphaFold Protein Structure Database](https://alphafold.ebi.ac.uk), Google DeepMind and EMBL-EBI | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Small-molecule 3D structures and properties | 3D lessons | [PubChem](https://pubchem.ncbi.nlm.nih.gov), NCBI | Public domain |
| Photo "Human brain frontal (coronal) section", with labels, outline and ruler added | The Dopamine Pathway, Real size tab | John A. Beal, LSU Health Sciences Center Shreveport, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Human_brain_frontal_(coronal)_section.JPG) | [CC BY 2.5](https://creativecommons.org/licenses/by/2.5/) |
| Brain specimen photos (lateral, inferior and midline views; coronal section; insula dissection), with circles added | The Dopamine Pathway, 3D brain tab | John A. Beal, LSU Health Sciences Center Shreveport, via Wikimedia Commons: [lateral](https://commons.wikimedia.org/wiki/File:Human_brain_lateral_view.JPG), [inferior](https://commons.wikimedia.org/wiki/File:Human_brain_inferior_view.JPG), [midline](https://commons.wikimedia.org/wiki/File:Human_brain_midsagittal_cut.JPG), [insula](https://commons.wikimedia.org/wiki/File:Human_brain_view_on_transverse_temporal_and_insular_gyri.JPG) | [CC BY 2.5](https://creativecommons.org/licenses/by/2.5/) |
| Photo "Cut section of human brain", with circles added | The Dopamine Pathway, 3D brain tab | Dr. Roshan Nasimudeen, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Cut_section_of_human_brain.jpg) | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) |
| Photo "Hippocampus and seahorse" | The Dopamine Pathway, 3D brain tab | Professor László Seress, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Hippocampus_and_seahorse.JPG) | [CC BY-SA 1.0](https://creativecommons.org/licenses/by-sa/1.0/) |
| Photo "Formalin-fixated human brain 3" (nucleus accumbens), with a circle added | The Dopamine Pathway, 3D brain tab | Mavridis IN and Anagnostopoulou S, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Formalin-fixated_human_brain3.jpg) | [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) |
| Photo "Slide3HOM" (substantia nigra), with circles added | The Dopamine Pathway, 3D brain tab | Anatomist90, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Slide3HOM.JPG) | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) |
| Ten more brain specimen photos, with rings, bands and outlines added (positions read from the photographer’s own labeled versions) | The Dopamine Pathway, Brain atlas tab (`brain_atlas_photos.js`) | John A. Beal, LSU Health Sciences Center Shreveport, via Wikimedia Commons: [inner surface](https://commons.wikimedia.org/wiki/File:Human_brain_inferior-medial_view.JPG), [midline close-up](https://commons.wikimedia.org/wiki/File:Human_brain_left_midsagitttal_view_closeup.JPG), [brainstem from behind](https://commons.wikimedia.org/wiki/File:Human_brainstem-thalamus_posterior_view.JPG), [brainstem from the front](https://commons.wikimedia.org/wiki/File:Human_brainstem_anterior_view.JPG), [underside with cranial nerves](https://commons.wikimedia.org/wiki/File:Human_brain_anterior-inferior_view.JPG), [ventricle from the inside](https://commons.wikimedia.org/wiki/File:Human_brain_left_dissected_midsagittal_view.JPG), [ventricle from the side](https://commons.wikimedia.org/wiki/File:Human_brain_right_dissected_lateral_view.JPG), [arachnoid](https://commons.wikimedia.org/wiki/File:Human_brain_arachnoid.JPG), [folds of the dura](https://commons.wikimedia.org/wiki/File:Human_brain_dura_mater_(reflections).JPG), [dura mater](https://commons.wikimedia.org/wiki/File:Human_brain_dura_mater_description.JPG) | [CC BY 2.5](https://creativecommons.org/licenses/by/2.5/) |
| Photo "Slide10kk" (globus pallidus, ventricles), with rings added | The Dopamine Pathway, Brain atlas tab (`brain_atlas_photos.js`) | Anatomist90, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Slide10kk.JPG) | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) |
| Photo "Hippocampus macroscopy", with rings added | The Dopamine Pathway, Brain atlas tab (`brain_atlas_photos.js`) | Jensflorian, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Hippocampus_macroscopy.jpg) | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| Recordings of the English names of brain regions by real speakers: 53 clips, with leading and trailing silence shortened, the level adjusted and converted to MP3. 44 of the 78 regions have one; the others use the browser's computer voice and say so | The Dopamine Pathway, Brain atlas tab (`audio/`) | Volunteers of Lingua Libre and Wiktionary, via [Wikimedia Commons](https://commons.wikimedia.org/wiki/Category:Lingua_Libre_pronunciation-eng). Each clip's speaker, license and source page are in [audio/credits.json](audio/credits.json) and in the region's card | CC0, [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) or [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), as listed per clip; each converted clip keeps the license of its source |
| Zombie sprites | Guard the Dopamine Factory | [Toon Characters 1](https://kenney.nl/assets/toon-characters-1) by Kenney | [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) |
| three.js r128, loaded from cdnjs | 3D lessons | [three.js authors](https://github.com/mrdoob/three.js) | MIT |
| SmilesDrawer 1.0.10, loaded from jsDelivr | The Molecular Game of Addiction | [Daniel Probst and contributors](https://github.com/reymond-group/smilesDrawer) | MIT |
| Inter and Source Serif 4 fonts, loaded from Google Fonts | All pages | Rasmus Andersson; Adobe | SIL Open Font License 1.1 |

Other notes:

- The nucleus accumbens slice in the Real size tab and the 3D brain tab is an AI-generated image (OpenAI image generation through Codex). It is labeled as such on the page.
- Mouse Party and Meth Mouse (Genetic Science Learning Center, University of Utah) and the YouTube videos are linked, not copied.
- Short quotations from published papers are cited where they appear and remain under their publishers' copyright.
- Facts and figures come from the CDC, NIDA, the DEA and published papers, and the pages cite their sources.
