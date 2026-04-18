# Design and Analysis of a Low Power Conditional Capture Flip-Flop in 32 nm CMOS

**Authors:**  
Maisam AbuJaber, Student ID: 1220014  
Khadija Fakhri, Student ID: 1220458

---

## Abstract
This paper presents a low-power Conditional Capture Flip-Flop (CCFF) in 32 nm CMOS that reduces clock power by preventing internal switching when D = Q. Pre-layout simulations show 39% average power reduction and 48.6% clock power reduction. Post-layout results with extracted parasitics confirm 37% power reduction with setup time of 45 ps, hold time of 12 ps, and clock-to-Q delay of 40.4 ps. The design achieves these savings with only 18% area overhead. A 16-bit register bank implementation validates scalability, achieving 34% total power reduction and 49% clock power reduction under realistic workloads.

**Index Terms:** Low power design, conditional capture flip-flop, clock power reduction, CMOS, VLSI, 32 nm technology.

---

## I. Introduction
Clock power constitutes 30–45% of total chip power in modern processors. Conventional master-slave flip-flops suffer from redundant switching when D = Q.

---

## II. Proposed Design
The CCFF uses conditional clock gating and data comparison to eliminate unnecessary switching.

---

## III. Results Summary
- Pre-layout power reduction: 39%
- Post-layout power reduction: 37%
- Setup time: 45 ps
- Hold time: 12 ps
- Clock-to-Q delay: 40.4 ps

---

## IV. Conclusion
The proposed CCFF achieves significant power reduction with minimal timing and area overhead, making it suitable for low-power VLSI systems.

---

## Authors
Maisam AbuJaber (1220014)  
Khadija Fakhri (1220458)
