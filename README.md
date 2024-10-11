# Image Search Data

This repository contains a JSON file that provides structured data for image categories, subcategories, related phrases, and popular searches. This data can be used to enhance image search functionalities in applications, websites, or other projects.

## JSON Structure

The JSON file `image_search_data.json` includes the following fields:

- **categories**: An array of categories, each containing:
  - **name**: The name of the category.
  - **subcategories**: An array of subcategories related to the category.
  - **phrases**: An array of descriptive phrases related to the category.
  - **related_tags**: An array of tags that are associated with the category.
  - **popular_searches**: An array of commonly searched terms related to the category.

### Example Structure

```json
{
  "categories": [
    {
      "name": "Nature",
      "subcategories": ["Landscapes", "Wildlife", "Plants"],
      "phrases": ["beautiful landscapes", "majestic mountains"],
      "related_tags": ["outdoor", "natural beauty"],
      "popular_searches": ["national parks", "endangered species"]
    }
  ]
}
```
