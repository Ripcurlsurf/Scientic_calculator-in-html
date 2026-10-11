Web Calculators Suite

A collection of standalone, single-file HTML5 calculators engineered with clean vanilla JavaScript, modern CSS, and keyboard accessibility. No build tools, external runtimes, or package managers required.
Included Applications
1. Kepler SC-9 (Ripcurlsurf_calculator.html)

An advanced scientific and engineering workstation pairing an algebraic LCD calculator with a multi-pane tool bench.   
HTML

    Algebraic Engine: Evaluates custom expressions, handles implicit multiplication (2π), brackets, variable assignments (e.g., r = 4), and stores historical entries.   
    HTML

    2D Function Plotter: Interactive canvas plotting up to 3 functions of x with zoom, pan, hover trace, and automatic root/intersection detection.   
    HTML

    Solvers: Root finding via bisection/golden-section search, polynomial root solving (real and complex), and linear system solving via Gaussian elimination (2×2 to 4×4).   
    HTML

    Calculus & Series: Numerical derivatives via five-point central differences, definite integration via adaptive Simpson's quadrature, and compensated summations/products (Σ / Π).   
    HTML

    Statistics: 1-variable analysis (summary statistics, IQR, skewness, and SVG box plots) and 2-variable analysis (linear regression and scatter plots).   
    HTML

    Base-N & Bitwise: Two's complement integer math in HEX, DEC, OCT, and BIN across 8, 16, 32, and 64-bit word sizes with interactive bit flipping.   
    HTML

    Unit Converter & Physical Constants: Multi-category unit conversions alongside standard CODATA 2018 physical constants.   
    HTML

2. Tape Calculator (standard-calculator.html)

A digital recreation of a classic desk office calculator (TC-12) featuring a printed audit paper tape.   
HTML

    Audit Paper Tape: Logs each operational step dynamically to an interactive virtual paper tape.   
    HTML

    Tape Recall: Click any previous total on the tape roll to pull it back into active calculation.   
    HTML

    Arithmetic & Quick Powers: Immediate-execution arithmetic, percentages, square roots, reciprocals, and squared values.   
    HTML

    State Persistence: Saves tape entries locally via localStorage.   
    HTML

Quick Start

Both calculators are completely self-contained single-page applications.

    Clone or download the repository:
    Bash

    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name

    Open either file directly in any modern browser:

        Double-click Ripcurlsurf_calculator.html or standard-calculator.html.

        Or serve locally via python:
        Bash

        python3 -m http.server 8000

Keyboard Shortcuts
Kepler SC-9

    Evaluate: Enter or =

       
    HTML

    Clear: Esc

       
    HTML

    History Navigation: ↑ / ↓

       
    HTML

    Operators: +, -, *, /, ^

       
    HTML

Tape Calculator

    Digits / Decimal: 0–9, .

       
    HTML

    Basic Operators: +, -, *, /, %

       
    HTML

    Equals / Total: Enter or =

       
    HTML

    Clear Entry / All Clear: Delete (C), Esc (AC)   
    HTML

    Delete Digit: Backspace

       
    HTML

    Math Functions: r (x​), q (x2), i (1/x)   
    HTML

License

This project is made available for free non-commercial use only.

    Non-Commercial Restriction: You may freely download, run, modify, and share this software for personal, academic, or non-commercial purposes.

    Commercial use, redistribution for profit, or bundling within commercial products and services is strictly prohibited without explicit prior written authorization from the author.
