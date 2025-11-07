[![Makefile CI](https://github.com/shaoyinguo-portfolio/warpage-pca/actions/workflows/makefile.yml/badge.svg)](https://github.com/shaoyinguo-portfolio/warpage-pca/actions/workflows/makefile.yml)

# Warpage Analysis Using Principal Component Analysis

In the semiconductor packaging and Printed Circuit Board Assembly (PCBA) industries, **warpage control is critical to manufacturing yield and reliability.** Excessive warpage can lead to various defects, including opens, shorts, and adhesive delamination.

Conventional warpage analysis typically relies on simple surface flatness characterization methods, often measured as the total indicator reading (TIR)—the difference between maximum and minimum height values ($\text{Max height} - \text{Min height}$). This scalar approach provides a single aggregate value, which is often **inadequate for attributing complex warpage profiles to specific, underlying process factors.** It fails to capture the spatial characteristics and dominant shapes of the deformation.

**Principal Component Analysis (PCA) offers a powerful alternative** by providing a robust framework for spatial decomposition and dimensionality reduction. PCA transforms the complex, high-dimensional surface topography data into a set of orthogonal basis vectors, known as "eigen shapes" or principal components.

This methodology effectively preserves the most significant deformation shapes of the packages, which often directly correlate with specific process factors. PCA finds multiple advanced use cases in both technology development and High-Volume Manufacturing (HVM):

*   **Eigen Shape Magnitude Evolution:** Tracking the evolution of dominant warpage shapes across sequential manufacturing process operations (e.g., molding, reflow, die attach, lid/stiffener attach).
*   **Supplier Quality Management:** Investigating and addressing substrate supplier transparency issues related to incoming material quality and inherent warpage profiles.
*   **Localized Feature Correlation:** Correlating specific local substrate undulations or features with yield outcomes.
*   **HVM Statistical Process Control (SPC):** Implementing advanced SPC monitoring for key principal components to detect process drifts.
*   **Anomaly Detection:** Identifying subtle anomalies, such as those indicative of latent adhesive delamination or unexpected material behaviors.
*   **Tooling Health Monitoring:** Detecting consistent deformation patterns indicative of tooling wear-and-tear or fixture misalignment.

This demo project will illustrate how PCA can be applied to warpage data to uncover insights that conventional methods miss.
