## Subpixel Diameter Measurement at Different Angles

This repository contains subpixel-based diameter measurements at **0°, 30°, and 60°**, evaluating measurement accuracy, precision, and angular sensitivity against a nominal diameter of **27.6 mm**.

### Dataset Files

- `subpixel_measurement_0_degree.csv` — Measurements at 0°.
- `subpixel_measurement_30_degree.csv` — Measurements at 30°.
- `subpixel_measurement_60_degree.csv` — Measurements at 60°.

The CSV files contain subpixel-based measurements used to evaluate diameter estimation at different angles.

### Measurement Results

| Angle | Accepted N | Mean Diameter (mm) | SD (mm) | Bias (mm) | RMSE (mm) |
|-------|-----------:|-------------------:|--------:|----------:|----------:|
| 0°    | 1435       | 27.59996           | 0.000287 | -0.0000415 | 0.00029 |
| 30°   | 407        | 27.37000           | 0.000157 | -0.23000   | 0.23000 |
| 60°   | 422        | 22.36000           | 0.000132 | -5.24000   | 5.24000 |


### Conclusion

The subpixel measurement method demonstrates excellent accuracy at 0°, but increasing angular orientation introduces substantial systematic bias. These results highlight the importance of angular calibration and geometric correction for accurate diameter estimation.
