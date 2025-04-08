# BOGO Product Selection Component

This component allows users to select a product offer under a BOGO (Buy One Get One) promotion. Users can choose product sizes and colors for two items, and select from multiple purchase plans with respective discounts.

## Features

- **BOGO Offer Interface**
  - "Buy One Get One" layout with unit selection.
  - Multiple unit options: 1, 2, or 3 units with increasing discounts (10%, 20%, and 30% respectively).
  - Size and color selection for two units when BOGO is active.
  
- **Discount Badges**
  - Each unit option displays a discount label (e.g., "10% Off").
  - "Most Popular" tag for 2-unit option to guide user decision-making.

- **Pricing**
  - Shows discounted and original prices.
  - Total dynamically updates based on selected option.

- **Call to Action**
  - `+ Add to Cart` button triggers purchase action.
  - Free delivery label.

## Usage

Embed this component in any product page where promotional pricing is offered.

### Props / State

- `selectedUnit`: Controls which unit package is currently selected.
- `sizeSelection`: Tracks size for each item (#1, #2).
- `colorSelection`: Tracks color for each item (#1, #2).
- `totalPrice`: Dynamically updated based on selected unit and discount.