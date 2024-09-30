# Blazor EMI Calculator with Detailed Breakdown

This Blazor application allows users to calculate and view a detailed breakdown of EMI payments, including principal, interest, and additional costs like GST and processing fees. It supports both regular EMI and No-Cost EMI options and offers flexible inputs for loan amount, tenure, interest rate, and processing fees.

## Features

- **EMI & No-Cost EMI**: Choose between regular EMI and No-Cost EMI options.
- **Loan Breakdown**: Provides a detailed breakdown of each EMI installment, including principal, interest, GST on interest, and EMI amount.
- **Processing Fee**: Allows for a fixed or percentage-based processing fee with a default value of ₹199.
- **GST Calculation**: Automatically applies 18% GST on both the interest component and the processing fee.
- **Bootstrap Styling**: The UI is styled with Bootstrap for a clean, responsive layout.

## Requirements

- [.NET 6 SDK](https://dotnet.microsoft.com/download/dotnet/6.0)
- [Blazor](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor) (Server-Side)
- [Bootstrap](https://getbootstrap.com/) for UI styling

## Installation

1. Clone the repository or download the source code.

    ```bash
    git clone https://github.com/your-username/blazor-emi-calculator.git
    ```

2. Open the project folder in your favorite IDE (e.g., Visual Studio, Visual Studio Code).

3. Install the required packages.

    ```bash
    dotnet restore
    ```

4. Run the project using HTTPS.

    ```bash
    dotnet run
    ```

5. Access the application by navigating to `https://localhost:5001` in your web browser.

## Usage

1. **Loan Amount**: Enter the loan amount you want to calculate EMI for.
2. **Tenure**: Provide the number of months over which the loan will be repaid.
3. **Interest Rate**: Enter the annual interest rate (e.g., 12%).
4. **EMI Type**: Select between "EMI" and "No-Cost EMI". The default is "No-Cost EMI".
5. **Processing Fee**: You can either use a fixed amount or a percentage. The default processing fee is ₹199.
6. Click on "Calculate EMI" to see the detailed breakdown of your EMIs, including principal, interest, GST, and total payable.

## Breakdown Table

Once the calculation is complete, you will see a table with the following details:

- **Installment No.**: The number of the installment (e.g., 1, 2, 3...).
- **Billing Date**: The date when each EMI is due.
- **Outstanding Principal**: The remaining loan balance before the installment.
- **Principal**: The amount of the EMI that goes toward repaying the loan.
- **Interest**: The interest portion of the EMI.
- **GST on Interest**: 18% GST applied to the interest.
- **EMI Amount**: The total amount of each EMI installment.
- **Processing Fee**: Added as a row at the bottom of the table with GST applied.

### No-Cost EMI

For No-Cost EMI, the total payable amount is adjusted by subtracting the total interest from the loan. This ensures that the borrower only pays the principal amount without any extra interest burden.

## License

This project is licensed under the MIT License.

## Contributions

Feel free to submit issues or pull requests if you have any improvements or suggestions for this application.

## Contact

For any queries, reach out via [ashwini@fnlsg.in](ashwini@fnlsg.in).

