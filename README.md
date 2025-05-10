# Monte Carlo Simulation for Option Pricing 📈

This project uses Monte Carlo simulation in R to price European-style call and put options. It compares results with the Black-Scholes model, estimates the Greeks (Delta, Vega, Theta, Gamma, Rho), and includes visualizations like stock path plots, histograms, and heatmaps.

## 📊 Model Features
- Monte Carlo simulation using GBM  
- Antithetic variance reduction  
- Confidence intervals for option prices  
- Visual diagnostics: paths, histograms, and heatmaps  
- Black-Scholes comparison  
- Estimates of option Greeks  

## 🧠 Built With
- R and R Markdown  
- Financial modeling concepts (Black-Scholes, Greeks)  
- Simulation and visualization best practices  

## 📂 What's Inside
- `montecarlo.Rmd`: R Markdown file with full model, visuals, and results  
- `montecarlo.html`: Rendered HTML version of the notebook  
- Sample plots: Simulated paths, payoff distributions, and heatmaps  

## ▶️ How to Run
1. Open `montecarlo.Rmd` in **RStudio**  
2. Install required packages (see below)  
3. Click “Knit” to generate the full HTML report  

## 🛠️ Required Packages
`tidyquant`, `ggplot2`, `dplyr`, `tidyr`, `tibble`, `knitr`, `kableExtra`, `quantmod`, `viridis`

## 🚀 Author
Jimmy Kane – [LinkedIn](https://www.linkedin.com/in/jimmy-kane-72795720a/)

## 📄 View Report
- Click to see the full output: [Rendered HTML Report](MonteCarlo.html)  
- Click to view the full source code: [montecarlo.Rmd](MonteCarlo.Rmd)
