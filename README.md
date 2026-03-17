# ⚡ DC-DC Converter Control Techniques

An interactive Reveal.js presentation covering all major control techniques for DC-DC converters — PWM (voltage-mode, peak/valley/average current-mode), PFM, hysteretic, and constant on-time (COT) — with interactive waveform graphics, efficiency comparisons, tradeoff analysis, and future directions.

## ▶ [Open the Presentation](https://brendanjameslynskey.github.io/DCDC_Control_Techniques/)

---

## Contents

| # | Topic | Description |
| --- | --- | --- |
| 01 | Title | DC-DC converter control overview |
| 02 | Agenda | Topics at a glance |
| 03 | Why Control Matters | Line/load regulation, transient response, stability |
| 04 | The Buck Converter | Synchronous buck topology and feedback loop |
| 05 | Voltage-Mode vs Current-Mode | VMC vs CMC — architecture, compensation, tradeoffs |
| 06 | PWM Overview | Fixed-frequency pulse width modulation |
| 07 | Interactive: PWM Waveforms | Adjustable duty cycle, VM/CM mode toggle |
| 08 | Peak Current-Mode PWM | Sub-harmonic oscillation, slope compensation, sensing methods |
| 09 | Valley & Average Current-Mode | When to use each variant |
| 10 | PFM Overview | Pulse frequency modulation, pulse-skipping, burst mode |
| 11 | Interactive: PWM vs PFM Efficiency | Log-scale load sweep with real-time efficiency comparison |
| 12 | Hysteretic Control | Bang-bang operation, advantages, limitations |
| 13 | COT Overview | Constant on-time principles and the ripple requirement |
| 14 | COT Variants | Classic, emulated ripple, D-CAP / D-CAP2 / D-CAP3 |
| 15 | Interactive: COT Timing | Adjustable V_IN showing on-time and frequency adaptation |
| 16 | Tradeoff Comparison | Full comparison table across all five techniques |
| 17 | Application Selection Guide | Server PoL, IoT, automotive, FPGA/CPU core rails |
| 18 | Interactive: Load Transient | Animated transient response comparison across control types |
| 19 | Digital Control & DPWM | ADC → PID → DPWM architecture, MPC, industry adoption |
| 20 | Advanced & Emerging Techniques | AOT, spread-spectrum, V², AI/ML-assisted, coupled inductors |
| 21 | Compensation Design | Type II and Type III compensator overview |
| 22 | EMI & Frequency Spectrum | Fixed vs variable frequency EMI signatures and filter design |
| 23 | Multi-Phase Converters | Interleaving, phase shedding, control compatibility |
| 24 | Future Directions | GaN/SiC, integrated modules, 48V PoL, autonomous tuning |
| 25 | Summary & Key Takeaways | Decision tree, design guidelines, further reading |
| 26 | References & Resources | Textbooks, application notes, simulation tools |

---

## Slide Controls

| Action | Key |
| --- | --- |
| Next / Previous | `→` `←` or swipe |
| Overview | `Esc` |
| Fullscreen | `F` |
| Export to PDF | Append `?print-pdf` to URL, then print |

## Technology

[Reveal.js 4.6](https://revealjs.com) · [highlight.js](https://highlightjs.org) · Playfair Display + DM Sans + JetBrains Mono

Single self-contained `index.html` — no build step, no npm, no dependencies to install.

## References

Erickson & Maksimović, *Fundamentals of Power Electronics*, 3rd ed. · Kazimierczuk, *Pulse-Width Modulated DC-DC Power Converters* · Ridley, *Power Supply Design*, Vol. 1–3 · TI SLVA057, *Understanding Current-Mode Control Theory* · TI SLVA281, *Voltage Mode vs Current Mode* · TI SLVA470, *D-CAP2 Operation* · NPTEL, *Switched Mode Power Conversion*

## License

Educational use. Code examples provided as-is.
