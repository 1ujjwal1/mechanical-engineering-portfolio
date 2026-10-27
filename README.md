# Ujjval Jha — Mechanical Engineering Portfolio

A responsive, dark-themed portfolio for GitHub Pages. The site includes a homepage/profile and five individually navigable case studies.

## Case studies
1. Full Vehicle Assembly & Mass Properties — 232-component SolidWorks assembly, packaging, CAD mass properties and CG/wheelbase estimates.
2. Roll Cage Design Iterations & Validation — the four supplied iterations, driver-clearance checks, AISI 4130 material reference and the supplied ANSYS plots.
3. Motor Mounting Bracket — concept/assembly images, the existing 1,000 N ANSYS result set, supplemental braking-load estimate, and next validation steps.
4. EV Powertrain Integration — gearbox/gear analysis, chain/sprocket layout and the current 10:1 gearbox and 1.28:1 sprocket reduction assumptions.
5. Motor-to-Sprocket Spline Adapter — OEM constraints, reviewed adapter CAD, sprocket reference, prototype fit check and preliminary ANSYS FOS result.

## Preview locally
Extract the ZIP and open `index.html` in a browser. All images and page styles are included locally.

## Publish on GitHub Pages
1. Create or open the repository to host the portfolio.
2. Upload the **contents** of this folder to the repository root (so `index.html` is at the root, not one folder deeper).
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` (or your publishing branch), and choose `/ (root)`.
5. Save and wait for GitHub Pages to publish the site.

## Accuracy and validation notes
- The assembly's 270.86 kg value is the mass reported by the supplied SolidWorks Mass Properties screenshot for that CAD configuration; total physical vehicle mass remains unfinalized.
- CG height is a CAD estimate, not a physical measurement. The supplied estimate is approximately 26 in.
- The roll-cage safety-factor screenshot included for the selected direction displays a minimum of 1.9401. This does not substantiate a separate reported target/result above 2; use a matched final solve to confirm it.
- The motor-bracket 1,000 N ANSYS result and the separate 833 N / 56.7 N·m braking estimate are distinct load cases and should not be conflated.
- The spline-adapter ANSYS screenshot reports a preliminary minimum FOS of 1.8. The screenshot alone does not validate fatigue, overspeed or high-RPM retention.
- Simulation images are evidence of the supplied analysis setup/results, not certification. Verify material cards, loads, supports, connections, mesh quality and applicable competition rules before design sign-off.
