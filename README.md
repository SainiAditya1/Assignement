# Frontend Assignment - Accuknox

## Overview

This assignment involves creating a dynamic dashboard/widget system using JSON. The dashboard will support multiple categories, each containing multiple widgets. Users will have the ability to add and remove widgets dynamically within these categories.

## Requirements

1. **JSON Structure**: Create a JSON structure to build the dashboard/widgets dynamically. The JSON should contain categories, and each category can contain multiple widgets.
2. **Dynamic Widget Management**: Users should be able to:
   - Add a widget to a category.
   - Remove a widget from a category.
3. **Widget Content**: For the purpose of this assignment, each widget can contain random text.
4. **Add Widget Functionality**: When a user clicks on "+Add Widget", they should be able to:
   - Enter the widget name.
   - Enter the widget text.
   - Add the widget to the selected category.
5. **Remove Widget Functionality**: Each widget should have a cross icon to remove it from the category. Alternatively, users can go to the add category section and uncheck from the category list.
6. **Search Functionality**: Users should be able to search through a list of all the widgets.

## JSON Structure Example

```json
{
  "categories": [
    {
      "name": "CSPM Executive Dashboard",
      "widgets": [
        {
          "name": "Widget 1",
          "text": "Random text for Widget 1"
        },
        {
          "name": "Widget 2",
          "text": "Random text for Widget 2"
        }
      ]
    },
    {
      "name": "Another Category",
      "widgets": [
        {
          "name": "Widget A",
          "text": "Random text for Widget A"
        }
      ]
    }
  ]
}
```

## Setup and Run Locally

```sh
git clone https://github.com/SainiAditya1/Assignment
cd Assignment
npm install
npm run dev

```
