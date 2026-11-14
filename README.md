# Unit Price Calculator

A simple, mobile-friendly web application that helps users compare product prices and find the best value for money.

## Features

- **Real-time Calculation** – Automatically calculates unit prices as you enter product information.
- **Multiple Products** – Add or remove products for comparison.
- **Automatic Unit Conversion** – Converts different units into a common standard for accurate comparison.
- **Best Value Ranking** – Automatically ranks products from the lowest to the highest unit price.
- **Mobile-Friendly Design** – Simple and responsive interface designed for smartphone use.
- **Reset Function** – Clear all products and start a new comparison.

## Supported Units

| Category | Supported Units | Standard Unit |
|---|---|---|
| Weight | mg, g, kg, oz | g |
| Volume | ml, L, cc | ml |
| Quantity | pcs, pc, piece, ชิ้น | pcs |

### Unit Conversion

- 1 kg = 1,000 g
- 1 g = 1,000 mg
- 1 oz = 28.3495 g
- 1 L = 1,000 ml
- 1 cc = 1 ml

Products are compared only within the same measurement category.

## How to Use

1. Open the application.
2. Enter the product price in Thai Baht (฿).
3. Enter the product quantity with its unit (e.g., `500 g`, `1 kg`, `16 oz`, `450 ml`, or `12 pcs`).
4. Add more products to compare.
5. View the calculated unit prices and ranking.
6. The product with the lowest unit price offers the best value.

**Note:** If no unit is specified, the application automatically treats the quantity as pieces (pcs).

## Calculation Method

The application calculates the standardized unit price using the following formulas:

- Weight: Price per 100 g
- Volume: Price per 100 ml
- Quantity: Price per piece

The product with the lowest calculated unit price is ranked as the best value within its category.

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Installation

No installation or backend is required.

1. Clone this repository:

   ```bash
   git clone https://github.com/louuu-ktn/unit-price-calculator.git
   ```

2. Open the project folder.
3. Open `index.html` in your web browser.

## Live Demo

[Open Unit Price Calculator](https://louuu-ktn.github.io/unit-price-calculator/)

## Project Structure

```text
unit-price-calculator/
│
├── index.html
└── README.md
```

## License

This project is open-source and available for educational and personal use.