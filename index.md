---
layout: default
title: Riemann
description: Notes on the zeta function, its zeros, and the critical line, with the P versus NP slides kept alongside.
samwiki: true
---

<p class="sw-level sw-level-painfully-challenging"><span class="sw-level-idx">Level 4</span><span class="sw-level-name">Painfully challenging</span></p>

<section class="sw-lede" aria-labelledby="about-title">
  <div class="sw-lede-copy">
    <h2 id="about-title">Zeros, the critical line, and time-to-solve</h2>
    <p>This repository holds the Riemann zeta notes and the P versus NP slides that were written with them. For real part greater than 1, the zeta function is the series of reciprocal powers, and Euler’s product writes that series over the primes. The notes follow the function into the critical strip and state the Riemann hypothesis: every non-trivial zero has real part one half. The <a href="riemann-zeta-notes.html">HTML walkthrough</a> keeps the slides, the functional equation, and the Python appendices for the phase plot and the surface plot.</p>
    <p>The explicit formula is why the zeros sit next to the primes. The Chebyshev function ψ(x) has a main term x, a sum over the non-trivial zeros, and lower-order corrections. The prime-counting function picks up the same oscillation through a sum of Li(x<sup>ρ</sup>). Phase plots, contour plots, and a surface of the modulus show those zeros as singularities and as crossings of the real and imaginary zero curves. The plots record the zeros that were calculated. The hypothesis remains open.</p>
    <p>The same folder asks the question in the <a href="https://github.com/sdcastillo/Riemann/blob/main/README.md">README</a>: does every efficiently verifiable problem also have an efficiently solvable answer? The P versus NP Beamer sources and the deck <a href="P_vs_NP_Presentation_by_Sam.pdf">P vs NP</a> treat that as time-to-solve. Constant, logarithmic, linear, quadratic, and exponential growth are written out with everyday comparisons, from a dictionary lookup to guessing every character of a password. A recording of the presentation is on <a href="https://youtu.be/UgRNtOb6joY?si=YEPT820qiTTi9QgP">YouTube</a>. More writing is at <a href="https://www.predictiveinsightsai.com">predictiveinsightsai.com</a>.</p>
    <p><strong>Difficulty: painfully challenging.</strong> On the SamWiki ladder this is Level 4, painfully challenging, for analytic number theory. The Riemann hypothesis is open, and so is P versus NP. What is here is the presentation layer: definitions, the critical line, an error term the hypothesis would give the prime-number theorem, NP-completeness, and an AI-assisted frame for exploring both. A reader can start from the Basel problem and the verifier definition. Closing either question is the part that still needs a proof.</p>
  </div>
  <aside class="sw-find" aria-labelledby="facts-title">
    <h2 id="facts-title">On this page</h2>
    <ul>
      <li><strong>What it is</strong> Zeta-function notes and P versus NP slides, in PDF, PowerPoint, Beamer, and HTML.</li>
      <li><strong>Who it is for</strong> Analytic number theory, and readers following verification versus solving.</li>
      <li><strong>Difficulty: painfully challenging</strong> Level 4 on the SamWiki ladder. Research math. Both headline questions are open.</li>
      <li><strong>The bridge</strong> Non-trivial zeros enter the explicit formula for the primes. Plots show the zeros that were computed.</li>
      <li><strong>The outline</strong> Motivation, NP-completeness, the critical line, Big-O growth, and the about note from the README.</li>
    </ul>
  </aside>
</section>

## What you will learn

The README already lists the path through the talks:

- **Motivation and real-world impact.** Why P versus NP matters, and how time, memory, energy, and hardware bound what stays solvable.
- **Intuition and NP-completeness.** Verifying an answer and finding an answer are different jobs.
- **The Riemann hypothesis.** The zeros of the zeta function shape the oscillation in the primes. The claim is that every non-trivial zero lies on the critical line.

## Feasibility and runtime growth

The scale notes use Big O, as written in the README:

- **O(1), constant time.** Looking up the first item in a list.
- **O(log n), logarithmic.** Searching for a word in a physical dictionary.
- **O(n), linear time.** Reading through every page of a book one by one.
- **O(n²), quadratic time.** Checking a room of people for shared birthdays by making everyone introduce themselves to everyone else.
- **O(2ⁿ), exponential time.** Trying to crack a password by guessing every possible combination of characters.

## Files in this repository

- [HTML walkthrough](riemann-zeta-notes.html) of the zeta slides, including the phase-plot and surface-plot appendices.
- [The Riemann Zeta Function, by Sam Castillo (PDF)](The_Riemann_Zeta_Function_by_Sam_Castillo.pdf) and the [PowerPoint](The_Riemann_Zeta_Function_by_Sam_Castillo.ppt).
- [Zeros, the critical line, and computational exploration (PDF)](The_Riemann_Zeta_Fuction__Zeros__the_Critical_Line__and_Computational_Exploration.pdf), a [second PDF export](The_Riemann_Zeta_Fuction__Zeros__the_Critical_Line__and_Computational_Exploration-1.pdf), and the [zip](The_Riemann_Zeta_Fuction__Zeros__the_Critical_Line__and_Computational_Exploration.zip).
- [The sum of the reciprocals of the squares (PDF)](The_Sum_of_the_Reciprocals_of_the_Squares__Zeros_of_Reimman_.pdf), the [PowerPoint](The_Sum_of_the_Reciprocals_of_the_Squares__Zeros_of_Reimman_.pptx), and the [zip](The_Sum_of_the_Reciprocals_of_the_Squares__Zeros_of_Reimman_.zip).
- Beamer source: [riemann_zeta_beamer.tex](riemann_zeta_beamer.tex), [riemann_beamer_visual_refresh.tex](riemann_beamer_visual_refresh.tex), [p_vs_np_beamer.tex](p_vs_np_beamer.tex), and [p_vs_np_beamer_styled.tex](p_vs_np_beamer_styled.tex).
- [P vs NP (PDF)](P_vs_NP_Presentation_by_Sam.pdf) and the [PowerPoint](P_vs_NP_Presentation_by_Sam.ppt).
- [Page images zip](ilovepdf_pages-to-jpg.zip).

## About

Drawing on a B.S. in Mathematics (with honors) from UMass Amherst, a background in actuarial sciences (probability, statistics, financial mathematics, and time series analysis), and over six years of building computing systems, the presentations connect the theory to large-scale implementation.

## Topics

P versus NP, the Riemann hypothesis, quantum statistics, complexity theory, mathematics, computer science, Big O, number theory, NP-complete problems, algorithm design, computational complexity, actuarial science, data science, mathematical physics, the Millennium Prize problems, and quantum computing.

<section class="sw-contribute" aria-labelledby="contribute-title">
  <h2 id="contribute-title">Contribute</h2>
  <p>Fork <a href="https://github.com/sdcastillo/Riemann">sdcastillo/Riemann</a>, make the improvement, and send it back. A clearer step in the notes, a fix in the Beamer source, or a correction to a formula belongs in a pull request.</p>
  <p class="sw-actions">
    <a class="sw-btn sw-btn-pr" href="https://github.com/sdcastillo/Riemann/compare" target="_blank" rel="noopener noreferrer">Contribute / Open a PR</a>
  </p>
</section>
