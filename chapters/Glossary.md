# Glossary of Terms in Mendelian Randomization (MR)

<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 88%" />
</colgroup>
<thead>
<tr>
<th><strong>Term</strong></th>
<th><strong>Definition</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Mendelian Randomization (MR)</strong></td>
<td>A method that uses genetic variants as <em>instrumental
variables</em> to infer causal relationships between a modifiable risk
factor and an outcome.</td>
</tr>
<tr>
<td><strong>Instrumental Variable (IV)</strong></td>
<td>A variable (often a genetic variant) that: (1) is associated with
the risk factor, (2) is not associated with confounders, and (3) affects
the outcome <em>only</em> through the risk factor.</td>
</tr>
<tr>
<td><strong>Multiple Instruments</strong></td>
<td>Use of more than one genetic variant (e.g. SNPs) as instruments in
MR to improve statistical power and robustness.</td>
</tr>
<tr>
<td><strong>Allele Score / Genetic Risk Score (GRS)</strong></td>
<td>A summary measure counting the number of risk alleles carried by an
individual. Variants can be unweighted or <em>weighted</em> by their
strength of association with the risk factor (typically from GWAS).</td>
</tr>
<tr>
<td><strong>Weak Instrument Bias</strong></td>
<td>Bias arising when the instruments (genetic variants) explain only a
small proportion of the variance in the risk factor, especially
problematic in small samples.</td>
</tr>
<tr>
<td><strong>Pleiotropy</strong></td>
<td>Occurs when a genetic variant influences more than one trait. </td>
</tr>
</tbody>
</table>

# Statistical Methods in MR

<table>
<colgroup>
<col style="width: 18%" />
<col style="width: 81%" />
</colgroup>
<thead>
<tr>
<th><strong>Term</strong></th>
<th><strong>Definition</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Single Sample MR</strong></td>
<td>Instrument-exposure and instrument-outcome associations are
estimated in the same dataset. Vulnerable to weak instrument bias if not
handled carefully.</td>
</tr>
<tr>
<td><strong>Two Sample MR</strong></td>
<td>Uses separate, independent datasets (often from consortia) for the
instrument-exposure and instrument-outcome associations. Enables greater
statistical power and flexibility.</td>
</tr>
<tr>
<td><strong>MR-Egger Regression</strong></td>
<td>A regression method that accounts for <em>unbalanced horizontal
pleiotropy</em>. It provides a test for directional pleiotropy and an
adjusted causal estimate under the InSIDE assumption (Instrument
Strength Independent of Direct Effect).</td>
</tr>
<tr>
<td><strong>Inverse-Variance Weighted (IVW) Method</strong></td>
<td>A commonly used method in two-sample MR that combines effect
estimates from multiple instruments assuming no horizontal
pleiotropy.</td>
</tr>
<tr>
<td><strong>Weighted Median Estimator</strong></td>
<td>Provides a consistent estimate even if up to 50% of the instruments
are invalid, assuming the majority are valid.</td>
</tr>
<tr>
<td><strong>MR-PRESSO (Pleiotropy RESidual Sum and
Outlier)</strong></td>
<td>Detects and corrects for horizontal pleiotropic outliers among
instruments. Improves robustness of causal inference.</td>
</tr>
<tr>
<td><strong>Multivariable MR (MVMR)</strong></td>
<td>Allows for simultaneous estimation of causal effects of multiple
exposures on an outcome using genetic instruments for each
exposure.</td>
</tr>
<tr>
<td><strong>Steiger Filtering</strong></td>
<td>A method used to test whether the direction of causality is more
consistent with the exposure affecting the outcome, not vice versa.</td>
</tr>
</tbody>
</table>

# Properties of Genetic Instruments

<table>
<colgroup>
<col style="width: 8%" />
<col style="width: 91%" />
</colgroup>
<thead>
<tr>
<th><strong>Term</strong></th>
<th><strong>Definition</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Instrument Strength</strong></td>
<td>The extent to which a genetic variant explains variation in the
exposure. Quantified using statistics like the <strong>partial
F-statistic</strong> (F &gt; 10 is considered strong), and
<strong>R²</strong> (proportion of variance explained).</td>
</tr>
<tr>
<td><strong>Hausman Test</strong></td>
<td>A test used in single-sample MR to compare observational
vs. instrumental variable (causal) estimates for continuous
outcomes.</td>
</tr>
<tr>
<td><strong>Heterogeneity Tests</strong></td>
<td>Tests like <strong>Cochran’s Q</strong> assess variability in causal
estimates across instruments, often used to detect pleiotropy or invalid
instruments.</td>
</tr>
<tr>
<td><strong>Assumptions of MR</strong></td>
<td></td>
</tr>
</tbody>
</table>
