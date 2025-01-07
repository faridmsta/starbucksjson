# Starbucks JSON Data

This repository contains a JSON file for representing the content and structure of Starbucks-related data. The data includes home promotions, menu items, featured gifts, and seasonal offerings.

## Structure

### Home Promotions
- The home section includes a series of promotional banners with the following fields:
  - `id`: Unique identifier for the promotion.
  - `img`: Path to the image associated with the promotion.
  - `headtext`: Headline text of the promotion.
  - `text`: Description of the promotion.
  - `bgcolor`: Background color of the promotion.
  - `bttext`: Text for the call-to-action button.
  - `txtcolor`: Text color for the description and button.

### Menu Items
The `menu` section categorizes Starbucks products into drinks, food, at-home coffee, and merchandise. For each drink, additional information includes:
  - `name`: Name of the drink.
  - `img`: Image of the drink.
  - `more`: Additional details like calorie count, ingredients, and customization options.

### Featured Gifts
The `gift` section highlights different gift card designs for various occasions:
- `featured`: A list of featured gift cards.
- `lunaryear`: A collection of gift cards for Lunar New Year.
- `winter`: A collection of gift cards for winter.
- `celebration`: A collection of celebratory gift cards.

## Usage

You can use this JSON data to populate a website or application with Starbucks-related content, including promotions, drinks, food options, and gifts. The JSON is structured to allow for easy customization and integration into a frontend framework.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/faridmsta/starbucksjson.git
   ```

2. Use the JSON file in your project to display Starbucks promotions, menu items, and gift options.

1. OR just Fetch [https://raw.githubusercontent.com/faridmsta/starbucksjson/refs/heads/main/db.json]
