---
tags:
  - drosophila
  - development
---
in drosophila, the establishment of the anteroposterior axis and segmentation occurs through a hierarchical cascade of segmentation genes, where the products of one class of genes regulate expression of the next, progressively refining the embryonic pattern. This intricate process moves from broad regional specifications to a fine grain pattern of individual segments

maternal genes --> [[gap genes]] --> [[pair-rule genes]] --> [[segment-polarity genes]]

cascade begins with maternal-effect genes, whose products are deposited in the egg by the mother, setting up initial regional differences and gradients. A key example is the [[Bicoid]] protein, which forms an anteroposterior concentration gradient. This gradient provides the primary positional information, activating the first set of zygotic genes, known as [[gap genes]]

[[gap genes]]
- general function: gap genes are the first zygotic genes to be expressed along the anteroposterior axis. they subdivide the early embryo into broad, contiguous blocks of segments. All gap genes encode [[Transcription factors]]. Their activity converts the maternal gradients into an aperiodic pattern of transcription factors, defining major body regions
- mutant phenotype: mutations in gap genes lead to embryos missing large, contiguous blocks of segments, creating 'gaps' in the segmentation pattern
- regulation and expression: their expression is initiated by the maternal Bicoid protein gradient. For example, Bicoid directly activates the anterior expression of [[hunchback]]. Gap gene proteins in turn act as morphogens to activate and repress other gap genes in a conc dependent manner. ==There is also extensive cross inhibition between overlapping gap gene proteins to sharpen and stabilise the expression boundaries. Gap proteins are expressed in blocks of cells corresponding to the segments missing in their respective mutants==
- key gene example: [[hunchback]] is a prominent gap gene is activated in the anterior half of the embryo by [[Bicoid]] and itself acts as a morphogen, activating and repressing other gap genes like [[Kruppel]] (Activated by low hunchback, repressed by high)

[[pair-rule genes]]
- general function: pair-rule genes are responsible for establishing the initial periodic segmentation pattern, dividing the embryo into 14 developmental units called parasegments. all pair rule genes encode transcription factors. they convert the broad, aperiodic information from gap genes, into a precise, repeating pattern
- mutant phenotype: mutations in pair rule genes cause the loss of parts of each pair of segments 
- regulation and expression: expression directly influenced by activity of gap genes. pair rule genes are expressed in seven striking transverse stripes across the embryo, with each stripe corresponding to every second parasegment. each of these stripes is controlled independently by specific cis-acting regulatory elements that integrate combinatorial inputs from multiple transcription factors (maternal and gap proteins)
- key gene example" even skipped (eve) is a well studies pair rule gene. expressed in the odd numbered parasegments with its stripes being regulated by combinations of Bicoid, Hunchback (activators), and Giant and Kruppel (suppressors)

### [[gap genes]] vs [[pair-rule genes]]

Gap genes are the first set of zygotic genes to be expressed along the anterior-posterior axis. Their job is to interpret the broad, smooth gradients of maternal effect proteins (like Bicoid and Hunchback) and translate them into smaller, more defined domains.
- **Function:** To establish large, multi-segment regions of the embryo. Think of them as drawing the rough outlines of major body sections (e.g., head, thorax, abdomen).
- **Expression Pattern:** They are expressed in broad, overlapping domains. For example, the gene _Krüppel_ is expressed in a wide band in the central part of the embryo. Other key gap genes include _hunchback_, _knirps_, and _giant_.
- **Regulation:** They are regulated directly by maternal effect gene gradients. The concentration of the Bicoid protein, for example, determines the anterior boundary of some gap genes and activates others
- **Mutant Phenotype:** A mutation in a gap gene causes a large **"gap"** in the larval body plan, where several adjacent segments are deleted. For example, a _Krüppel_ mutant is missing its thoracic and anterior abdominal segments

Pair-rule genes are the next level down in the hierarchy. They read the more detailed positional information provided by the gap genes and use it to create a more periodic, repeating pattern
- **Function:** To divide the broad domains defined by the gap genes into a repeating series of smaller units. They establish the boundaries of **parasegments**, which are the fundamental developmental units that later give rise to the visible body segments.
- **Expression Pattern:** They are typically expressed in a characteristic pattern of **seven transverse stripes** along the embryo. Each stripe corresponds to every other parasegment. Famous examples include _even-skipped_ (_eve_) and _fushi tarazu_ (_ftz_), which are expressed in complementary seven-stripe patterns.
- **Regulation:** They are regulated by the gap genes. The intricate seven-stripe pattern is achieved because each individual stripe is controlled by a unique combination of different gap gene proteins acting as activators or repressors. For instance, stripe 2 of the _eve_ gene is activated by Bicoid and Hunchback but repressed by Giant and Krüppel.
- **Mutant Phenotype:** A mutation in a pair-rule gene results in the deletion of **every other segment**. This gives the larva a "paired" or shortened appearance, as it only has half the normal number of segments.

[[segment-polarity genes]]
- general function: segment polarity genes are crucial for aptterning within each segment and for stabilising parasegment boundaries. unlike earlier genes, they operate in cellularised environment, involving intercellular communication. they further refine the segmental organization set by [[pair-rule genes]]
- mutant phenotype: mutations in here lead to defects in segment polarity and number, often resulting in loss of parts of each segments
- regulation and expression: they're activated in response to [[pair-rule genes]] expression. --> include gene products such as transcription factors (E.g. engrailed), secreted signalling proteins (ligands like Wingless and hedgehog), and transmembrane receptors (like Patched). a critical feature is an intercellular signalling circuit involving engrailed, hedgehog and wingless. Engrailed-expressing cells also express and secrete Hedgehog, which acts on adjacent cells to activate _wingless_. Wingless, in turn, signals back to the _engrailed_-expressing cells, maintaining both _engrailed_ and _hedgehog_ expression, thereby stabilizing the parasegment boundary and establishing it as a signaling center. Segment polarity genes are expressed in **14 distinct transverse stripes**, one per segment, which are typically one to two cells wide
- **Key Gene Example**: **Engrailed** (_en_) is a segment polarity gene. It encodes a transcription factor and is expressed continuously throughout the fly's life, marking the posterior compartment of each segment. It functions as a **selector gene**, maintaining the identity of the posterior compartment and influencing cell surface properties to prevent mixing with adjacent cells

.![[Pasted image 20250912112027.png]]

This step-by-step genetic cascade, from broad maternal gradients to refined segment patterning, illustrates how a complex body plan is orchestrated during development