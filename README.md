### Mortgage Calculator GitHub Description

#### Overview

This repository contains a Mortgage Calculator built using Excel, designed to calculate the monthly mortgage payments, total payments, and total interest for a given loan. It provides a comprehensive amortization table, breaking down each payment into principal and interest components.

#### Real-Life Formula Used

**Monthly Mortgage Payment (PMT) Formula**:

\[ \text{PMT} = \frac{P \times r(1 + r)^n}{(1 + r)^n - 1} \]

Where:
- \( P \) = Principal loan amount
- \( r \) = Monthly interest rate (annual rate divided by 12)
- \( n \) = Total number of payments (loan term in years multiplied by 12)

#### Implementation Details

The Excel Mortgage Calculator leverages built-in functions and custom formulas to compute various mortgage-related values. Below are the details of how each key component is calculated:

1. **Principal (P)**:
   - This is calculated by subtracting the down payment from the price of the home.
   - Example: For a home priced at $200,000 with a 20% down payment, the principal is $160,000.

2. **Monthly Interest Rate (r)**:
   - The annual interest rate is divided by 12 to get the monthly rate.
   - Example: For a 5% annual rate, the monthly rate is \( \frac{0.05}{12} \approx 0.004167 \).

3. **Total Number of Payments (n)**:
   - This is the product of the loan term in years and the number of months per year (12).
   - Example: For a 30-year loan term, the total number of payments is \( 30 \times 12 = 360 \).

4. **Monthly Loan Payment (PMT)**:
   - Using the PMT formula, the monthly mortgage payment is calculated.
   - Example: With the given values, the Excel `PMT` function is used to compute the monthly payment.

5. **Total Payments**:
   - The total amount paid over the life of the loan is calculated by multiplying the monthly payment by the total number of payments.
   - Example: \( \text{Total Payments} = \text{Monthly Payment} \times 360 \).

6. **Total Interest**:
   - This is the difference between the total payments and the principal.
   - Example: \( \text{Total Interest} = \text{Total Payments} - \text{Principal} \).

#### Additional Components

- **Property Taxes, HOA Fees, and Property Insurance**:
  - These monthly expenses are added to the mortgage payment to provide a more comprehensive view of the monthly housing cost.

#### Excel Features Used

- **PMT Function**: Used to calculate the monthly mortgage payment.
- **SUM and Basic Arithmetic**: Used for total payments and total interest calculations.
- **Cell Referencing**: To dynamically update calculations based on input changes.

#### How It Functions

1. Input the price of the home, down payment percentage, annual interest rate, loan term, and monthly expenses (property taxes, HOA fees, and property insurance).
2. The calculator computes the principal, monthly interest rate, and total number of payments.
3. The monthly mortgage payment is calculated using the PMT function.
4. Total payments and total interest are computed for the loan term.
5. An amortization table is generated, detailing the breakdown of each monthly payment.

By providing these functionalities, the Mortgage Calculator helps users understand their financial commitments over the loan period, enabling better financial planning and decision-making.

This Excel-based Mortgage Calculator showcases the use of financial formulas and Excel functions to create a practical tool for prospective homeowners and financial planners. The detailed calculations and user-friendly interface make it an invaluable resource for mortgage-related decision-making.
