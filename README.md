# EnergyUsageCalculator ⚡

## 📱 Project Overview
EnergyUsageCalculator is an Android application developed to help users estimate their monthly electricity bills based on the tiered pricing (blocks) system. The app calculates costs based on specific consumption thresholds and applies a user-defined rebate.

---

## 🚀 Key Features

### 1. Advanced Bill Calculation (Tiered Pricing)
The app implements a tiered calculation logic based on the following rates:
| Consumption Block | Rate (RM/kWh) |
| :--- | :--- |
| **First 200 kWh** (1 - 200) | 0.218 |
| **Next 100 kWh** (201 - 300) | 0.334 |
| **Next 300 kWh** (301 - 600) | 0.516 |
| **Next 300 kWh+** (601 onwards) | 0.546 |

### 2. Rebate System
* Users can input a rebate percentage between **0% and 5%**.
* The final cost is calculated as: `Final Cost = Total Charges - (Total Charges * Rebate %)`
