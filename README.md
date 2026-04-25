# Strong-ARM-Latch
This project presents the design and analysis of a StrongARM Latch, a widely used dynamic comparator in high-speed and low-power analog/mixed-signal circuits. It operates without static power consumption and is commonly used in ADCs, sense amplifiers, and high-speed data converters.

**🎯 Objectives**
Design a dynamic latch-based comparator
Achieve high-speed decision making
Minimize power consumption (zero static power)
Analyze transient response and regeneration

**⚙️ Circuit Overview**

The StrongARM latch consists of:

Input differential pair (NMOS)
Cross-coupled inverters (positive feedback)
Tail transistor controlled by clock
🔄 Operation Phases
Reset Phase (CLK = 0)
Output nodes are precharged to VDD
No current flows through tail transistor
Evaluation Phase (CLK = 1)
Tail transistor turns ON
Differential input is amplified
Positive feedback regenerates outputs rapidly

**🧠 Theory**

The StrongARM latch uses positive feedback (regeneration) to quickly resolve small input voltage differences into full logic levels.

Faster decision due to exponential regeneration
No static power consumption (only dynamic power)
Offset depends on device mismatch

**📊 Results**
High-speed comparison achieved
Rail-to-rail digital output
Zero static power consumption
Fast regeneration during evaluation phase

**📈 Applications**
Analog-to-Digital Converters (ADC)
Sense amplifiers in memory circuits
High-speed comparators
Data communication systems
