# USD Futures – Previous-Day Settlement Reach Analysis

This repo contains a Python script that measures:

1. How often the USD futures price touches the **previous day's settlement**.
2. The same probability **conditioned on**:
   * the current day's open being above or below the prior close;
   * the current day's candle staying completely inside the previous day's range.

## Usage

```bash
pip install pandas
python settlement_reach_analysis.py
