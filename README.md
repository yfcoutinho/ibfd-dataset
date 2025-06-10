This repository contains CSV files with complex-valued frequency-domain channel realizations used in my research.

## 📂 Files

| File Name                      | Description                        |
|--------------------------------|------------------------------------|
| `channel_freq_resp_si.csv`     | SI channel data                    |
| `channel_freq_resp_plc_0.csv`  | PLC channel data for alpha = 0 dB  |
| `channel_freq_resp_plc_20.csv` | PLC channel data for alpha = 20 dB |
| `channel_freq_resp_plc_40.csv` | PLC channel data for alpha = 40 dB |

## 🧾 Format Description

Each CSV file contains the frequency-domain channel matrix with the following structure:

- Each **row** corresponds to a **subcarrier**.
- Each **pair of columns** corresponds to the **real and imaginary parts** of a complex-valued channel realization.
