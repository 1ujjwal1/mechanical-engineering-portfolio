# Analysis screenshot reference guide

## Roll cage
- The case page includes the selected CAD representation, iteration screenshots, driver-clearance references, AISI 4130 property sheet and the supplied ANSYS safety-factor plot.
- The visible minimum FoS on the selected-direction plot is 1.9401. The separately reported target/result above 2 needs a screenshot from the exact final model and solve before claiming it as verified.

## Motor mounting bracket
- Existing result set: 1,000 N static load; max von Mises stress 81.696 MPa; max total deformation 0.16674 mm; displayed minimum FoS 3.0601 for that result setup.
- Separate preliminary braking estimate: 25 kg motor, 60 km/h to 0 in 0.5 s gives about 833 N equivalent inertial force. At a 68 mm perpendicular offset, the associated moment magnitude is about 56.7 N·m.
- Do not treat the 833 N / 56.7 N·m estimate as though it were already solved in the screenshots above.

## Full vehicle assembly
- Supplied SolidWorks Mass Properties screenshot: 270.86 kg for that CAD configuration.
- Current CG estimate: about 26 in high. Longitudinal distances supplied are 90.36 cm from the front wheel reference and 51.88 cm from the rear reference, summing to 142.24 cm (56 in). Treat as CAD reference measurements, not physical scale measurements.

## Powertrain
- Current design assumptions: gearbox reduction 10:1 and sprocket reduction 1.28:1; combined reduction 12.8:1 if the definitions are consistent and the ratios multiply in the stated direction.
- Gear/chain ANSYS screenshots are retained as supplied; verify their material, force/torque, supports and contact definitions before presenting them as final validation.

## Spline adapter
- Supplied static ANSYS screenshot reports minimum FoS 1.8. The screenshot does not establish fatigue life, safe maximum RPM, spline contact pressure, or operational retention.
