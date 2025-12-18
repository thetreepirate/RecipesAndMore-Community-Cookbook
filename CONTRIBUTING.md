# Contributing to Community Cookbook

Thank you for wanting to share your recipes! 🎉

---

## Quick Start

1. **Fork** this repository
2. **Clone** your fork locally
3. **Create** a new branch for your recipe
4. **Add** your recipe files
5. **Submit** a pull request

---

## Recipe Requirements

### JSON Format

Each recipe must follow this structure:

```json
{
  "id": "recipe-slug",
  "version": 1,
  "metadata": {
    "created_at": "2025-12-17T10:00:00Z",
    "updated_at": "2025-12-17T10:00:00Z",
    "contributor": {
      "id": "your-github-username",
      "name": "Your Display Name",
      "profile_url": "https://github.com/your-username"
    },
    "downloads": 0,
    "ratings": {
      "average": 0,
      "count": 0
    }
  },
  "recipe": {
    "name": "Recipe Title",
    "description": "Brief description",
    "cuisine": "Italian",
    "category": "Dinner",
    "tags": ["Tag1", "Tag2"],
    "servings": 4,
    "prep_time": "15m",
    "cook_time": "30m",
    "total_time": "45m",
    "difficulty": "Easy",
    "ingredients": ["Item 1", "Item 2"],
    "instructions": "Step-by-step instructions...",
    "equipment": ["Tool 1", "Tool 2"],
    "notes": "Tips and variations",
    "source": "Original",
    "image_url": "",
    "nutrition": {}
  }
}
```

### Required Fields

- ✅ **name** - Clear, descriptive title
- ✅ **category** - breakfast, lunch, dinner, desserts, or snacks
- ✅ **ingredients** - Complete list with quantities
- ✅ **instructions** - Clear, numbered steps
- ✅ **servings** - Number of servings
- ✅ **difficulty** - Easy, Medium, or Hard

### Optional Fields

- 📸 **image_url** - Recipe photo (compressed to <150KB)
- ⏱️ **prep_time, cook_time, total_time** - e.g., "30m", "1h 30m"
- 🍽️ **equipment** - Required kitchen tools
- 📝 **notes** - Tips, substitutions, variations
- 🏷️ **tags** - Searchable keywords
- 🥗 **nutrition** - Calories, protein, carbs, etc.

---

## Image Guidelines

If including an image:

1. **Format**: JPEG (.jpg)
2. **Size**: Maximum 150KB
3. **Dimensions**: 800x600px (4:3 aspect ratio)
4. **Quality**: 85% compression
5. **Content**: Appetizing, well-lit food photo
6. **Rights**: You must own the image or have permission

### Compression

**macOS:**
```bash
sips -Z 800 -s format jpeg -s formatOptions 85 input.jpg --out output.jpg
```

**Online:** Use TinyJPG.com or Squoosh.app

---

## Recipe Quality Standards

### Instructions Must Be:
- ✅ Clear and easy to follow
- ✅ Numbered step-by-step
- ✅ Include cooking times and temperatures
- ✅ Tested and verified by you

### Ingredients Must:
- ✅ Include specific quantities
- ✅ Be listed in order of use
- ✅ Specify preparation (diced, minced, etc.)

### Times Must:
- ✅ Be realistic and accurate
- ✅ Include prep, cook, and total time
- ✅ Account for resting/cooling if needed

---

## Submission Checklist

Before submitting your pull request:

- [ ] Recipe JSON validates at [jsonlint.com](https://jsonlint.com)
- [ ] Recipe follows the standard schema
- [ ] All required fields are filled
- [ ] Instructions are clear and tested
- [ ] Image is compressed to <150KB (if included)
- [ ] Added recipe to `metadata/index.json`
- [ ] Recipe ID is unique (no duplicates)
- [ ] Proper category selected
- [ ] No copyright violations
- [ ] No promotional content or external links

---

## How to Add Your Recipe

### 1. Create Recipe File

Save as: `recipes/[category]/[recipe-slug].json`

Example: `recipes/dinner/chicken-tikka-masala.json`

### 2. Add Image (Optional)

Save as: `images/[category]/[recipe-slug].jpg`

Example: `images/dinner/chicken-tikka-masala.jpg`

### 3. Update Index

Add your recipe to `metadata/index.json`:

```json
{
  "id": "chicken-tikka-masala",
  "name": "Chicken Tikka Masala",
  "category": "dinner",
  "cuisine": "Indian",
  "tags": ["Indian", "Curry", "Chicken"],
  "difficulty": "Medium",
  "total_time": "1h",
  "servings": 4,
  "downloads": 0,
  "rating": 0,
  "rating_count": 0,
  "contributor": "your-username",
  "url": "https://raw.githubusercontent.com/.../recipes/dinner/chicken-tikka-masala.json",
  "image_url": "https://raw.githubusercontent.com/.../images/dinner/chicken-tikka-masala.jpg"
}
```

### 4. Submit Pull Request

```bash
git checkout -b add-chicken-tikka-masala
git add recipes/dinner/chicken-tikka-masala.json
git add images/dinner/chicken-tikka-masala.jpg
git add metadata/index.json
git commit -m "Add Chicken Tikka Masala recipe"
git push origin add-chicken-tikka-masala
```

Then open a pull request on GitHub!

---

## Recipe Categories

- **breakfast** - Morning meals (pancakes, eggs, oatmeal)
- **lunch** - Midday meals (salads, sandwiches, soups)
- **dinner** - Evening meals (pasta, meat, fish, vegetarian)
- **desserts** - Sweet treats (cakes, cookies, ice cream)
- **snacks** - Quick bites (dips, appetizers, finger foods)

---

## Cuisine Types

Italian, Mexican, Chinese, Japanese, Thai, Indian, French, Mediterranean, Greek, American, Korean, Vietnamese, Middle Eastern, Caribbean, Spanish, German, British, etc.

---

## Tags to Use

**Type**: Soup, Salad, Pasta, Stir-Fry, Baked, Grilled, Slow Cooker, Instant Pot

**Dietary**: Vegetarian, Vegan, Gluten-Free, Dairy-Free, Nut-Free, Low-Carb, Keto, Paleo

**Occasion**: Quick, Easy, Family-Friendly, Date Night, Party, Holiday, Comfort Food

**Time**: 15-Minute Meals, 30-Minute Meals, Make-Ahead, Freezer-Friendly

---

## Review Process

1. **Automated checks** - JSON validation, image size
2. **Manual review** - Recipe quality, clarity, completeness
3. **Testing** - We may test your recipe ourselves
4. **Approval** - Merged into main repository
5. **Featured** - Great recipes get highlighted!

---

## Code of Conduct

- ✅ Be respectful and inclusive
- ✅ Give credit where credit is due
- ✅ Accept constructive feedback graciously
- ✅ Help others learn and improve

❌ No spam, promotional content, or plagiarism
❌ No offensive, hateful, or inappropriate content
❌ No copyright violations

---

## Questions?

- **General questions**: Open an [issue](../../issues)
- **Recipe help**: Check existing recipes for examples
- **Technical issues**: See [README](README.md)

---

## License

By contributing, you agree to license your recipe under **CC BY 4.0** (Creative Commons Attribution).

This means others can use your recipe with proper attribution.

---

## Thank You! 🙏

Every recipe you contribute helps build a better, more diverse collection for the entire community. We appreciate your time and expertise!

Happy cooking! 👨‍🍳👩‍🍳
