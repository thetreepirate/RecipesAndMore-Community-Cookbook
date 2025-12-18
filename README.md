# RecipesAndMore Community Cookbook

**A FREE, open-source collection of delicious recipes for the RecipesAndMore app.**

Browse, download, and contribute recipes directly from the app. All recipes are community-tested and vetted for quality.

---

## 🍳 What's Inside

- **4 Starter Recipes** across breakfast, dinner, desserts, and snacks
- **JSON-based** for easy parsing and integration
- **Image support** for beautiful recipe presentation
- **Metadata system** for fast browsing and discovery

---

## 📖 Recipe Categories

- **Breakfast** - Start your day right
- **Lunch** - Quick and satisfying midday meals
- **Dinner** - Hearty evening dishes
- **Desserts** - Sweet treats and baked goods
- **Snacks** - Quick bites and appetizers

---

## 🚀 For Users

Download the **RecipesAndMore app** to browse and save these recipes to your collection!

All recipes include:
- ✅ Complete ingredient lists
- ✅ Step-by-step instructions
- ✅ Prep, cook, and total time
- ✅ Difficulty ratings
- ✅ Nutrition information
- ✅ Pro tips and variations

---

## 🤝 Contributing

Want to share your favorite recipe with the community?

1. **Fork** this repository
2. **Add** your recipe JSON to the appropriate category folder
3. **Include** a compressed image (<150KB) in the images folder
4. **Update** `metadata/index.json` with your recipe
5. **Submit** a pull request

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 📊 Stats

- **Total Recipes**: 4 (and growing!)
- **Categories**: 5
- **Contributors**: Community-driven
- **Cost**: FREE forever (GitHub hosting)

---

## 🏗️ Repository Structure

```
recipes/
├── breakfast/
│   └── fluffy-pancakes.json
├── lunch/
├── dinner/
│   └── pad-thai.json
├── desserts/
│   └── chocolate-chip-cookies.json
└── snacks/
    └── classic-hummus.json

images/
├── breakfast/
├── lunch/
├── dinner/
├── desserts/
└── snacks/

metadata/
└── index.json          # Fast recipe browsing index

contributors/
└── index.json          # Contributor profiles
```

---

## 📱 App Integration

Recipes are fetched via GitHub's CDN for fast, reliable delivery:

```
https://raw.githubusercontent.com/YOUR_USERNAME/RecipesAndMore-Community-Cookbook/main/recipes/[category]/[recipe-id].json
```

---

## 🎯 Vision

Building the world's best open-source recipe collection:
- **Quality**: Every recipe tested and rated
- **Accessibility**: Free forever, no ads, no paywalls
- **Community**: Built by home cooks, for home cooks
- **Modern**: JSON-based, API-ready, mobile-first

---

## 📄 License

All recipes are contributed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**

You are free to:
- ✅ Share — copy and redistribute
- ✅ Adapt — remix, transform, and build upon

With attribution to the original contributor.

---

## 🙏 Credits

Built with ❤️ by the RecipesAndMore community.

Special thanks to all contributors who share their culinary knowledge!

---

**Start exploring recipes:** [Browse the collection →](recipes/)

**Join the community:** [Star this repo](../../stargazers) • [Fork it](../../fork) • [Contribute](CONTRIBUTING.md)
