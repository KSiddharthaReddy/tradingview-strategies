Overview
This strategy uses a fast/slow EMA crossover to capture trending moves, combined with stop-loss and take-profit controls. Position size is calculated as a percentage of account equity for realistic compounding.

How it works
• Long when fast EMA crosses above slow EMA
• Exit on opposite cross or when SL/TP is hit
• Commission and slippage included
• Non-repainting logic (no future data)

Why this strategy can perform well
Trend systems typically have lower win rates but aim to hold winners longer. In backtests on ETERNAL (1H timeframe), returns benefited mainly from a few strong trending periods.

Limitations
• Performs poorly in sideways/choppy markets
• Drawdowns can be significant
• Historical performance does NOT predict future results
• Results change across symbols, timeframes, and parameters

Suggested use
This script is intended for testing, learning, and strategy development. Always forward-test before risking real capital, and never rely on a single indicator to make trading decisions.
<img width="2785" height="1361" alt="ETERNAL_2026-01-01_23-42-51" src="https://github.com/user-attachments/assets/6384408e-40a1-4c6b-a7ef-f5bc3a9d867e" />
<img width="1377" height="592" alt="Screenshot 2026-01-01 at 11 43 58 PM" src="https://github.com/user-attachments/assets/12d70844-a118-4f9a-bde4-54c21a1b4af4" />
<img width="1392" height="594" alt="Screenshot 2026-01-01 at 11 47 27 PM" src="https://github.com/user-attachments/assets/086eb8ee-7578-436e-8e1d-41092e4ceea7" />
