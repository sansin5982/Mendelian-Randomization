# Mendelian Randomization

## 1. Introduction

**Mendelian Randomization (MR)** is an analytical approach that
leverages genetic variants as **instrumental variables** to **infer
causal relationship between exposure (e.g., lifestyle factor or
biomarker) and an outcome (e.g., disease risk)**. If there is a cusal
relationship between two variables it also **estimate magnitude of
causal effect**. MR is based on the principle that genetic variants are
randomlly allocated at conception and are thus **less likely to
influenced by confounding factors** or **reverse causation**, which are
common issues in observationals studies.

<img src="Figures/reverse causation.jpg" alt="Figure 1: Reverse Causation"  />
<p class="caption">
Figure 1: Reverse Causation
</p>

[Image
Credit](https://nap.nationalacademies.org/read/11908/chapter/10#157)

By using genetic instruments, MR provides an approach to estimate causal
effects in a manner analogus to **randomized clinical trials** (RCTs),
offering valuable insights into public health and biomedical research.

<img src="Figures/RCT vs MR.png" alt="Figure 2: Similarities between Mendelian Randomization and Randomized Clinical Trial" width="1272" />
<p class="caption">
Figure 2: Similarities between Mendelian Randomization and Randomized
Clinical Trial
</p>

[Image
Credit](https://cloufield.github.io/GWASTutorial/16_mendelian_randomization/)

Mendelian Randomization uses Mendel’s **law of segregation** and **law
of independent assortment**.

### Mendel’s Laws of Inheritance

Gregor Mendel, known as the **“Father of Genetics,”** formulated three
fundamental laws of inheritance based on his experiments with pea
plants. These laws describe how traits are passed from parents to
offspring.

#### 1. Law of Segregation (First Law)

-   **Definition**:
    -   Each individual has two alleles for each gene, and these alleles
        segregate (separate) randomly during gamete formation, so that
        each gamete receives only one allele. <br> <br>
-   **Explanation**:
    -   Organisms inherit two copies of each gene (one from each
        parent). <br> <br>
    -   During meiosis (gamete formation), the two alleles segregate
        randomly, ensuring that each gamete carries only one allele for
        each gene. <br> <br>
    -   Fertilization restores the diploid state, with offspring
        receiving one allele from each parent. <br> <br>
-   **Example**:
    -   If a pea plant has one allele for tall height (T) and one for
        short height (t), these alleles separate during gamete
        formation. The offspring may inherit either T or t, but not both
        from the same parent.

#### 2. Law of Independent Assortment (Second Law)

-   **Definition**:
    -   Genes for different traits assort independently of one another
        during gamete formation, given that the genes are located on
        different chromosomes.
-   **Explanation**:
    -   When genes are located on different chromosomes, the inheritance
        of one trait does not influence the inheritance of another.

    -   This leads to genetic variation in offspring.
-   **Example**:
    -   In a dihybrid cross involving pea plants, if we consider two
        traits—seed shape (Round, R vs. Wrinkled, r) and seed color
        (Yellow, Y vs. Green, y)—the inheritance of seed shape is
        independent of seed color.

    -   A cross between RrYy × RrYy will produce offspring with various
        combinations of these traits in a 9:3:3:1 ratio.

#### 3. Law of Dominance (Third Law)

-   **Definition**:
    -   When two different alleles for a trait are present in an
        organism, one allele may dominate over the other, masking its
        effect.
-   **Explanation**:
    -   The dominant allele is expressed in the phenotype, while the
        recessive allele remains hidden unless an organism has two
        copies of it.

    -   This explains why some traits disappear in one generation but
        reappear in the next.
-   **Example**:
    -   In Mendel’s pea plants, the allele for tall plants (T) is
        dominant over the allele for short plants (t).

    -   A Tt plant will be tall because the dominant T masks the effect
        of t.

These laws form the foundation of classical genetics, although modern
genetics has shown exceptions (e.g., linked genes, incomplete dominance,
and polygenic traits)

[⬅ Back to Home](../index.md)
