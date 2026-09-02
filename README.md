# GBM8360E — Laboratoire 1 : données IRM, espace k et artéfacts

Un laboratoire à faire à la maison, en trois exercices, faisant suite à la séance d'acquisition IRM à l'ICM. L'objectif est de manipuler de vraies données IRM et de développer une intuition du lien entre l'espace k et les images obtenues.

- **Ex. 1 — Manipulation de fichiers :** Extraire les paramètres d'acquisition (intensité du champ, TR, TE, angle de bascule) des en-têtes DICOM, visualiser les images, les convertir en NIfTI, et comparer ce que chaque format conserve ou perd.
- **Ex. 2 — Intuition de Fourier :** Dix jeux de données d'espace k modifiés sont présentés sous forme de paires magnitude/phase. Identifier la propriété de Fourier à l'origine de chacun, déterminer lesquels pourraient survenir sur un vrai scanner, et reproduire soi-même un artéfact.
- **Ex. 3 — Reconstruction à partir de l'espace k :** Générer l'espace k à partir de vos propres données, reconstruire à partir du centre puis de la périphérie pour voir où résident le contraste et les détails, puis sous-échantillonner volontairement pour créer du repliement et expliquer comment l'éviter.

L'accent est mis sur la compréhension et l'interprétation des résultats, plutôt que sur l'obtention du résultat attendu. Les questions d'observation et d'intuition doivent être répondues sans l'aide d'un LLM.

# GBM8360E — Lab 1: MRI Data, k-Space, and Artifacts

A take-home lab in three exercises, following the MRI acquisition session at the ICM. The point is to get hands-on with real MRI data and build intuition for how k-space relates to the images you actually see.

- **Ex. 1 — File handling:** Read acquisition parameters (field strength, TR, TE, flip angle) out of DICOM headers, view the images, convert to NIfTI, and compare what each format keeps and loses.
- **Ex. 2 — Fourier intuition:** Ten manipulated k-space datasets are shown as magnitude/phase image pairs. Identify which Fourier property produced each one, judge which could happen on a real scanner, and reproduce an artifact yourself.
- **Ex. 3 — k-space reconstruction:** Generate k-space from your own scan data, reconstruct from the center vs. the periphery to see where contrast and detail live, then undersample deliberately to create aliasing and explain how to avoid it.

Emphasis is on understanding and interpreting results, not just producing the right output. Observation and intuition questions should be answered without LLM help.
