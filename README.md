# Bargain Sale Calculator

A professional web-based calculator for land conservancies to use during bargain sale negotiations with landowners.

## Live Demo

Visit the calculator at: `https://timothydehm.github.io/bargainsale/`

(Once you enable GitHub Pages in your repository settings)

## What is a Bargain Sale?

A bargain sale is a transaction where a landowner sells property to a land conservancy for less than its fair market value. The difference between the fair market value and the sale price becomes a charitable deduction for the landowner, providing significant tax benefits while generating immediate cash.

## Features

- **Real-time Calculations**: Instantly see how different offer amounts affect the landowner's financial outcome
- **Comprehensive Tax Analysis**: 
  - Charitable deduction amounts
  - Capital gains tax calculations
  - Federal and state tax savings
  - 5-year carryforward projections
  - Cost basis allocation
- **Visual Comparisons**: Bar charts comparing bargain sale vs. full market sale scenarios
- **Negotiation Tools**: Key talking points section for use during meetings
- **Print Functionality**: Generate printable summaries for landowners
- **Mobile Responsive**: Works on tablets and laptops for field use

## How to Use

1. Enter the property's **Fair Market Value** (from qualified appraisal)
2. Input your **Purchase Price** offer
3. Add the landowner's **Cost Basis** (original purchase price + improvements)
4. Enter the landowner's **Annual Gross Income (AGI)**
5. Adjust tax rates as needed (federal, state, capital gains)
6. Review the calculated results and comparison charts
7. Use the talking points section during negotiations

## Calculations Included

- **Bargain Element**: The charitable deduction amount (FMV - Purchase Price)
- **Tax Savings**: Combined federal and state tax savings from the deduction
- **Capital Gains Tax**: Tax owed on the sale portion
- **Net Proceeds**: Cash received minus taxes plus tax savings
- **Carryforward Value**: Unused deductions that can be carried forward up to 5 years
- **Comparison**: Side-by-side comparison with a full market sale scenario

## Technical Details

- Built with React 18
- Styled with Tailwind CSS
- No backend required - runs entirely in the browser
- No data is stored or transmitted
- Works offline after initial load

## Setup for GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"
6. Your calculator will be live at `https://timothydehm.github.io/bargainsale/`

## Local Development

Simply open `index.html` in any modern web browser. No build process or server required.

## Disclaimer

This calculator is for informational purposes only. Landowners should consult with qualified tax and legal advisors before making any financial decisions. Tax laws vary by jurisdiction and individual circumstances.

## License

© 2025 - For use by land conservancies in bargain sale negotiations.

## Support

For questions or issues, please open an issue in this repository.
