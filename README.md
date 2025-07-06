# Energy ROI Model: Spain Solar + BESS

This project models the return on investment (ROI) and investment required to replace all fossil-fuel electricity generation in Spain with solar photovoltaic (PV) and battery energy storage systems (BESS).

## Features
- User-configurable inputs (costs, demand, efficiency, etc.)
- Optionally fetch real data via APIs
- Sizing logic for solar and storage based on daily cycles and night coverage
- Clear separation of CAPEX and OPEX for solar and storage
- ROI, investment, and annual savings calculations for a range of fossil share replacement targets
- Informative graphs: investment, ROI, annual savings, cumulative cash flow, sensitivity analysis
- Autobidding simulation framework for market-based revenue estimation
- Transparent, open-source, and designed for community feedback

## Getting Started
1. Install dependencies:
   ```bash
   pip install matplotlib numpy
   ```
2. Open the main notebook:
   - `roi.ipynb` (recommended)
   - Or run the script: `python roi_model.py` (legacy, less featured)

## Customization
- Adjust all key parameters in the first cell of the notebook (`roi.ipynb`).
- All calculations use consistent units (MWh, GWh, MW, €).
- The model is fully transparent and easy to adapt for other countries or scenarios.

## Open-Source Collaboration
- **Review and suggest improvements**: Propose enhancements, corrections, or new features (e.g., advanced market simulation, nonlinear scaling, fixed OPEX, etc.).
- **Share and discuss**: Share this model on LinkedIn or other platforms to invite feedback from the energy and engineering community.
- **Contribute on GitHub**: Pull requests and issues are welcome!

## How to Share and Collaborate
1. **Publish this notebook to a public GitHub repository** (see below).
2. **Post the GitHub link on LinkedIn** with a short summary and invitation for feedback (see example post in the notebook).
3. **Encourage open, non-political, engineering-focused discussion and improvement.**

