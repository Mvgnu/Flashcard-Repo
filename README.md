# 📚 OpenAnki Community Deck Repository

This is a template repository for sharing Anki flashcard decks with the OpenAnki community.

## 🚀 Quick Setup

1. **Use this template** - Click "Use this template" to create your own deck repository
2. **Upload your decks** - Drag & drop `.apkg` files into semester/topic folders
3. **Commit** - That's it! The index is auto-generated

## 📁 Structure

```
/
├── semester_1/
│   ├── anatomy.apkg
│   └── biochemistry.apkg
├── semester_2/
│   └── pharmacology.apkg
└── index.json  ← Auto-generated!
```

## 📋 How It Works

1. **You add decks** to folders (create new folders as needed)
2. **GitHub Actions** automatically scans all folders
3. **index.json** is regenerated with the complete file list
4. **OpenAnki users** add your repo and can browse/download decks

## ✨ Best Practices

- Use descriptive folder names (they become category titles)
- Use underscores or hyphens in folder names: `semester_1` or `clinical-medicine`
- Include deck subject in the filename: `anatomy_basics.apkg`
- Keep individual decks under 50MB for fast downloads

## 🔧 Customization

### Custom Category Names

Create a `meta.json` in any folder to customize display:

```json
{
  "display_name": "First Semester - Preclinical",
  "description": "Foundation courses"
}
```

### File Metadata

The GitHub Action can optionally read deck metadata:

```json
{
  "path": "semester_1/anatomy.apkg",
  "name": "Complete Anatomy",
  "size_mb": 12.5
}
```

## 🤝 Contributing

1. Fork this repository
2. Add your decks
3. Submit a pull request

## 📄 License

Decks shared here should respect copyright. Only share:
- Your own original content
- Open-licensed materials
- Materials you have permission to redistribute
