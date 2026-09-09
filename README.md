# Energy Challenge | Vehicle Performance & Energy Optimisation

An Automotive Engineering case study focused on reducing the energy consumption of a model vehicle through aerodynamic evaluation, rolling-resistance testing, drivetrain analysis and Tank-to-Wheel energy modelling.

> **Publication note**  
> This repository contains my own portfolio documentation, recreated diagrams and simplified examples. It excludes course submission material, shared team code, raw datasets and non-public test files.

## Objective

The project investigated the main sources of vehicle energy loss and translated experimental findings into an energy-efficient driving strategy.

The analysis combined aerodynamics, rolling resistance, drivetrain efficiency and control-system considerations to estimate the battery energy required at the wheels.

## My Contribution

I contributed to the vehicle-performance analysis, energy modelling and engineering software work within a multidisciplinary team.

My work supported the connection between measured vehicle behaviour, the Tank-to-Wheel model and practical driving-strategy decisions.

## Engineering Methods

### Aerodynamic Analysis

Wind-tunnel data was used to compare four vehicle configurations and determine their effective drag area. The final configuration combined a bottom plate with wheel covers.

### Coast-Down Testing

Repeated coast-down runs were performed on a level surface. Speed-time data was processed in MATLAB to estimate deceleration and determine the rolling-resistance coefficient.

### Drivetrain Analysis

Dynamometer results were used to evaluate drivetrain losses and identify the efficiency behaviour across operating conditions.

### Tank-to-Wheel Energy Model

A Tank-to-Wheel model combined rolling resistance, aerodynamic drag and drivetrain efficiency to estimate energy consumption per distance and per lap.

```text
Aerodynamic drag + Rolling resistance + Drivetrain losses
                           ↓
               Tank-to-Wheel energy model
                           ↓
             Driving-strategy recommendations
```

## Selected Results

- The full aerodynamic package reduced drag from **1.67 N** to **1.58 N** at approximately **9.5 m/s**: an improvement of about **5.5%**.
- Coast-down testing produced an average rolling-resistance coefficient of approximately **0.042**.
- The associated rolling-resistance force was approximately **4.97 N** under the tested conditions.
- With the drivetrain engaged, effective resistance increased to approximately **5.91 N**, demonstrating that drivetrain losses were significant.
- Dynamometer analysis identified a higher-efficiency region in the mid-range of speed and torque, with peak efficiency around **0.7**.

## Key Engineering Insight

The most energy-efficient strategy was not simply to drive at the lowest possible speed.

The model showed that unnecessary acceleration and stop-start driving were energy-intensive, while steady driving near an efficient drivetrain operating region could reduce overall Tank-to-Wheel energy use.

## Technologies and Methods

MATLAB · Vehicle Energy Modelling · Wind-Tunnel Data Analysis · Coast-Down Testing · Dynamometer Testing · Vehicle Control · Embedded Systems

## Repository Contents

- `docs/` — technical case-study notes and methodology
- `assets/` — recreated diagrams and approved visuals
- `examples/` — simplified, independently written analysis examples
- `README.md` — project overview and selected findings

## Key Learning Outcomes

- Translating measured vehicle data into an engineering model
- Comparing aerodynamic configurations using experimental evidence
- Estimating rolling resistance from coast-down data
- Accounting for drivetrain efficiency in vehicle-energy analysis
- Using modelling and test results to guide vehicle-control decisions
