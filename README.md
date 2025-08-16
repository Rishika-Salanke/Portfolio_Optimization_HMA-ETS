# Portfolio Optimization with HMA-ETS Hybrid Forecasting

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

This repository contains the implementation code for the research paper:  
**"Portfolio Optimization Using Hybrid Method with Uncertainty Forecasting (HMA+ETS)"**

## Key Features
- 🎯 **Hybrid Forecasting**: Combines Hull Moving Average (HMA) trend signals with Exponential Smoothing (ETS) for robust predictions
- 📊 **Uncertainty-Aware Optimization**: 70/30 weighting between point forecasts and conservative estimates
- ⚡ **Lightweight Implementation**: No complex optimization required
- 📈 **Backtested Performance**: 28% better Sortino ratio than traditional MVO

## Installation
```bash
git clone https://github.com/Rishika-Salanke/Portfolio_Optimization_HMA-ETS.git
cd Portfolio_Optimization_HMA-ETS
pip install -r requirements.txt
