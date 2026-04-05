# CMOS-OpAmp-Design
Low-power two-stage CMOS Op-Amp designed using Cadence Virtuoso achieving >80 dB gain and >60° phase margin with Miller compensation and stability optimization.
# Low-Power Two-Stage CMOS Op-Amp Design

## 📌 Overview
This project presents the design and analysis of a two-stage CMOS operational amplifier optimized for high gain, stability, and low power consumption.

## 🎯 Specifications
- Gain: ~85 dB
- Phase Margin: ~65°
- Power Consumption: ~0.85 mW
- Technology: 90nm CMOS

## 🛠 Tools Used
- Cadence Virtuoso
- LTSpice

## ⚙️ Design Details
- Differential input stage with active load
- Gain-boosted second stage
- Miller compensation for stability
- Optimized transistor sizing for low power

## 📊 Results

### Schematic
![Schematic](opamp_schematic.png)

### Gain Response
![Gain Plot](gain_plot.png)

### Phase Margin
![Phase Plot](phase_plot.png)

### Gain/Phase plot
![Gain/Phase Plot](gain_over_phase_plot.png)

### Transient Response
![Transient](transient.png)

### Power analysis
![Power analysis](power_analysis.png)

## 📘 Report
Detailed report available here:  
[View Report](OP_AMP_PROJECT_REPORT.pdf)

## 🔍 Key Learnings
- Stability analysis using phase margin
- Trade-offs between gain, bandwidth, and power
- Importance of compensation techniques
- Layout-aware design considerations

## 🚀 Future Work
- Layout design and parasitic extraction
- Post-layout simulation
- Further power optimization
