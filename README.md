# Freedom Calculator

## Monthly Deposit
**Formula:**  
Monthly Deposit = Monthly Bill + Buffer Amount  
Buffer Amount = Monthly Bill × Buffer Percentage

## Monthly Investment
**Formula:**  
Initial Monthly Investment = Monthly Deposit × Investment Ratio  
Monthly Investment = Initial Monthly Investment + (Reinvestment Amount ÷ 12)

Investment Ratios by Buffer:
- 15%: 34.41%
- 20%: 55.8%
- 25%: 65.1%
- 30%: 76.26%
- 35%: 89.28%
- 40%: 92.07%

## USDC Carry Over
**Formula:**  
Year 1: (Monthly Deposit - Monthly Investment) × 12  
Reinvestment = Previous Carry Over × Current Reinvestment Rate
Reinvestment Rate starts at 10% and increases by 10% each year (max 90%)

## Asset Value
**Formula:**  
Asset Value = Initial Investment + Yearly Investment + Initial Gains + Investment Gains  
Yearly Investment = Monthly Investment × 12  
Initial Gains = Initial Investment × Growth Rate  
Investment Gains = Yearly Investment × Growth Rate

## Loan Amount
**Formula:**  
Year 1: Monthly Bill × 12 × (1 + Loan Interest Rate)  
Next Years: Previous Loan + (Monthly Bill × 12 × (1 + Interest Rate))

## Reinvestment Strategy
**Formula:**  
Reinvestment Amount = USDC Carry Over × Current Reinvestment Rate  
Remaining Carry Over = USDC Carry Over - Reinvestment Amount  
Reinvestment Rate starts at 10% and increases by 10% each year (max 90%)

## Total Value
**Formula:**  
Total Value = Asset Value + Remaining USDC Carry Over

## Net Asset Value
**Formula:**  
Net Asset Value = Total Value - Total Loan Amount

## Financial Freedom
**Formula:**  
Monthly Passive Income = (Total Value × 10%) ÷ 12  
Freedom achieved when: Monthly Passive Income ≥ Monthly Desired Amount
