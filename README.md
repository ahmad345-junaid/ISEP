# CSV Data Files

This repository contains CSV datasets for calibration, STM measurements, vibration testing, and computational performance.

## File Structure

```text
.
├── README.md
├── calibration_intermediates.csv
├── compute_flops_layerwise.csv
├── compute_latency_summary.csv
├── frame_level_vibration.csv
├── latency_runs.csv
├── perspective_correction_factors.csv
├── stm_intermediate_measurements.csv
└── stm_scanline_distances.csv
```

## File Descriptions

- **`calibration_intermediates.csv`** — Checkerboard calibration values, pixel scales, and camera geometry at different viewing angles.
- **`compute_flops_layerwise.csv`** — Layer-by-layer model operations, MACs, FLOPs, and parameter counts.
- **`compute_latency_summary.csv`** — Overall latency, FPS, and throughput estimates for different precisions and devices.
- **`frame_level_vibration.csv`** — Frame-by-frame diameter measurements and errors across vibration test cases.
- **`latency_runs.csv`** — Individual processing-stage latency measurements for TF32, FP16 AMP, and TensorRT FP16.
- **`perspective_correction_factors.csv`** — Perspective correction factors and diameter biases at different angles.
- **`stm_intermediate_measurements.csv`** — Intermediate STM distance measurements, filtering statistics, and diameter accuracy metrics.
- **`stm_scanline_distances.csv`** — Per-scanline pixel distances, converted millimeter distances, and residual errors.
