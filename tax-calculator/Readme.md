# Form Table

This project demonstrates a form table implemented using HTML and Bootstrap.

## Features

- The form table allows users to input various financial details.
- Each input field represents a specific financial category, such as annual income, employee PF, house rent allowance, exemptions under 80C (excluding PF), and other exemptions.
- The form table calculates tax-related information based on the provided inputs, including income tax, standard exemptions, employer PF, professional tax, and cess.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Yash0922/Advance-tax-calculator.git

2. Open the `index.html` file in a web browser.

# Tax Calculation

The form table provides an easy way to calculate income tax based on the input values. It considers the following factors:

- **Income Tax Slabs**: The applicable tax slabs and rates are used to calculate the income tax based on the provided annual income.
- **Standard Exemption**: The standard exemption of Rs. 50,000 is automatically included in the tax calculation.
- **Employee PF**: The employee PF amount is deducted from the total income before calculating the tax liability.
- **House Rent Allowance**: The house rent allowance is considered for calculating the taxable income and determining the tax liability.
- **Exemptions under 80C**: Exemptions under Section 80C, excluding PF, are considered for reducing the taxable income.
- **Other Exemptions**: Any other exemptions are also considered for reducing the taxable income.
- **Employer PF**: The employer PF amount is deducted from the total income before calculating the tax liability.
- **Professional Tax**: The professional tax amount of Rs. 2500 is deducted from the total income before calculating the tax liability.
- **Cess**: A 4% cess is added to the income tax amount as per the tax regulations.

## Choosing the Tax Regime

The choice between the old and new tax regimes depends on various factors, including the taxpayer's income, deductions, and financial goals. Here are a few key points to consider:

- **Old Tax Regime**: In the old tax regime, you can claim various deductions and exemptions available under the Income Tax Act. This regime allows you to reduce your taxable income by considering exemptions like HRA, investments under 80C, medical insurance premiums, etc. It is suitable for individuals who have significant deductions and exemptions, resulting in lower tax liability.
- **New Tax Regime**: The new tax regime offers lower tax rates but eliminates most deductions and exemptions. Under this regime, you cannot claim exemptions such as HRA, investments under 80C, medical insurance premiums, etc. However, the tax rates are lower compared to the old regime. It is suitable for individuals who have fewer deductions and exemptions and prefer simplicity in tax calculations.

It is recommended to consult a tax professional or use tax calculators provided by the government to determine which tax regime is more beneficial for your specific financial situation.

## Tax Slabs

The income tax slabs for the assessment year 2023-2024 in India are as follows:

- Up to Rs. 2,50,000: No tax
- Rs. 2,50,001 to Rs. 5,00,000: 5% of total income exceeding Rs. 2,50,000
- Rs. 5,00,001 to Rs. 10,00,000: 10% of total income exceeding Rs. 5,00,000
- Rs. 10,00,001 to Rs. 50,00,000: 15% of total income exceeding Rs. 10,00,000
- Rs. 50,00,001 to Rs. 1,00,00,000: 20% of total income exceeding Rs. 50,00,000
- Above Rs. 1,00,00,000: 25% of total income exceeding Rs. 1,00,00,000

Please note that these tax slabs are subject to change as per the government's regulations.

## House Rent Allowance (HRA)

House Rent Allowance (HRA) is an allowance provided by employers to employees to meet their rental expenses. The amount of HRA eligible for exemption is determined based on the following factors:

- Actual HRA received from the employer
- Rent paid for the accommodation
- 10% of salary (basic salary + dearness allowance)

The lowest of the above three amounts is eligible for exemption under Section 10(13A) of the Income Tax Act.

It is recommended to consult the Income Tax Act or a tax professional for detailed information and eligibility criteria regarding HRA exemptions.

## Conclusion

The form table provides a convenient way to input financial details and calculate income tax based on the provided information. It allows individuals to compare tax liabilities under different tax regimes and make informed decisions regarding tax planning.



