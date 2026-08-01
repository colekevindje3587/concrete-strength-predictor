# Concrete Strength Predictor v1.0 - web tool 2026

> **A browser-based engineering utility for estimating concrete compressive strength from mix proportions, released here as version 1.0.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/colekevindje3587/concrete-strength-predictor?style=flat-square)](https://github.com/colekevindje3587/concrete-strength-predictor)

---

<p align="center">
  <a href="https://colekevindje3587.github.io/concrete-strength-predictor/">
    <img src="https://img.shields.io/badge/Download-Concrete%20Strength%20Predictor%20Latest-brightgreen?style=for-the-badge" alt="Download Concrete Strength Predictor">
  </a>
</p>

> **[Download Concrete Strength Predictor v1.0](https://colekevindje3587.github.io/concrete-strength-predictor/)**

---

[Download Latest Build](https://colekevindje3587.github.io/concrete-strength-predictor/)

---

## Overview

Concrete Strength Predictor is a compact web application that estimates concrete compressive strength in MPa using concrete mix inputs. Delivered through HTML, it runs in a browser and can be opened, shared, or demonstrated without a complicated installation process.

The project provides a practical learning aid for students, engineers, and others exploring the effects of cement, water, aggregates, admixtures, and curing age on concrete performance. Its results are intended for investigation and comparison rather than replacing laboratory measurements.

---

## What It Provides

- Predicts estimated concrete compressive strength from entered mix values
- Supports primary cement and water inputs
- Accounts for aggregate and admixture quantities
- Uses concrete age as part of the estimation process
- Reports the target strength measure in MPa
- Serves as an educational resource for engineering applications
- Uses a browser-ready HTML implementation
- Helps with demonstrations, learning exercises, and rapid mix comparisons

---

## Getting Started

1. Clone or download the repository:
   - `git clone https://github.com/colekevindje3587/concrete-strength-predictor.git
2. Move into the application directory:
   - `cd concrete-predictor`
3. Open the HTML entry file in a web browser, or run the files through a basic static web server.

When using a local server, launch it from the project directory and visit the address it displays in your browser.

---

## Using the Predictor

1. Load the application in a modern web browser.
2. Provide values for the mix characteristics you want to examine:
   - cement
   - water
   - aggregates
   - admixtures
   - age
3. Start the prediction to obtain an estimated compressive strength.
4. Repeat the process with alternate mix designs and compare the resulting estimates.

Possible comparisons include:

- Change the water quantity and observe the resulting estimate
- Increase the concrete age to review early-strength and later-strength differences
- Alter aggregate or admixture values to explore other mix conditions

---

## Project Configuration

In the basic HTML version, configuration is generally kept within the application files instead of a standalone configuration system. Any constants, formulas, or default interface values can be maintained in the HTML and script portions of the project.

A typical layout is:

    /concrete-predictor
      index.html
      assets/
      scripts/

When introducing additional parameters or adjusting tuning values, make the corresponding changes to both the input controls and the calculation logic in the application files.

---

## System Requirements

- A current web browser
- Support for HTML
- Local file access or a lightweight static web server
- Sufficient storage for the repository contents

The base web release does not require a separate runtime environment.

---

## Frequently Asked Questions

**What is the process for updating the application?**  
Pull the newest repository changes, or replace the files in your local copy with the latest build.

**Where can I find the primary configuration and formulas?**  
For this type of HTML project, the input definitions and calculation behavior are normally located in the page and script files.

**Why might the application fail to load?**  
Try opening it with a different browser, or use a local web server rather than loading the files directly from disk.

**Can the estimation process be customized?**  
Yes. The source files can be modified to change the inputs, calculation method, or way results are presented for a particular engineering workflow.

**Does this tool provide laboratory certification?**  
No. It is intended for educational exploration and understanding mix design relationships. It should not replace formal testing or a project-specific engineering assessment.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
