# LeverUp Miner Economics Simulator

Public boundary simulator for the LeverUp Contribution Engine (miner model).

Pull the sliders, find the equilibrium N*, verify the math yourself:

- `R(m) = P · m / (N · μ̄)` — per-machine weekly revenue
- `N* = m · P / (μ̄ · fuel)` — market equilibrium fleet size
- Refuel boundary: `R(m) ≥ fuel + 0.7 × own boost fee`
- Anti-wash identity: recovery ≤ 30% of any fee you pay

Static site — no build step. `index.html` is the entire app.

## Deploy

Vercel: import this repo, framework preset **Other**, no build command, output directory `/`.
