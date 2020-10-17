# Ruby Recipes

An app, written in Ruby, for management of recipes, shopping lists, meal planning and nutritional info.

## Planned Features:

### General
- Connect with supermarket APIs to check prices, store stock, etc
  - Woolworths: https://developer.woolworths.com.au/
  - Coles: ?
- Sync across multiple devices
  - CLI
  - Web
  - Mobile
      - Android
      - iOS
  - Desktop apps
    - Mac
    - Windows
- Calculate approx cost per meal, week, etc
- Nutritional info
  - easily sub in which version / brand of a product is being used
  - easily adjust portion size
  - track for an individual
  - sync data to fitness tracking apps
- Keep track of how much of a product has been used, and suggest when likely to need to buy more
- suggest best store to buy from, with easy override

### Recipes
- Create
  - manually
  - import from web
  - fork from others who use this app
  - create from
    - recipes view
    - meal plan view
  - auto-conversion of units (e.g. pounds to kgs)
- Read
  - recipes list and grid view
  - recipe details view
  - search
    - name
    - category
    - tags
    - ingredients
    - based on ingredients in house
- Update
  - version-controlled editing
- Delete
  - archive

### Meal Planning
- Create
  - using existing recipes
  - add new recipes in the process
  - include plans to order in / eat out
- Read
  - view a daily / weekly / fortnightly / monthly overview
  - easily click through to a particular recipe
- Update
  - edit meal plan
  - version controlled
  - undo functionality
- Delete
  - archive

### Shopping Lists
- Create
  - add items based on meal plan & recipes
    - select which days / meals to add from
    - suggest when you probably already have some and don't need to buy it
  - manually add items
  - handle non-recipes items
    - keep track, suggest when more might be needed
- Read
  - list items
    - categorise by isle, dependant on store
    - tag urgent items
      - "get it now" view for small mid-week shops
    - cross items off list while shopping
- Update
  - version controlled
  - stays syced with cloud
- Delete
  - archive


### Nutritional Info
- Create
  - manually
  - by scanning a barcode
  - based on recipe ingredients
    - confirm which version / brand of a product is in use (when it matters)
    - edit portion sizes
    - combine from multiple recipes, based on meal plan
      - e.g. multi-course dinner, and/or dessert
- Read
  - filter to just the bits you care about (e.g. just carbs and cals)
  - for:
    - an item
    - an ingredient
    - a meal
    - a multi-course meal
    - a portion
      - person-specific portion sizing
- Update
  - version controlled
  - choose retrospective updates or forward-only
- Delete
  - archive

