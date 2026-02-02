# PDF Notes

Drop PDFs here and they'll automatically convert to Markdown.

## How It Works

1. **Push a PDF** to this repo
2. **GitHub Action** automatically converts it to Markdown
3. **Pull** to get the markdown + extracted images

## Folder Structure

```
notes/
  ├── lecture.pdf           ← You upload this
  ├── lecture.md            ← Auto-generated
  └── lecture_images/       ← Extracted drawings/images
      ├── lecture_p1_img0.png
      └── ...
```

## Using with Obsidian

Clone this repo into your Obsidian vault:

```bash
cd ~/Obsidian/MyVault
git clone https://github.com/DEVLlN/pdf-notes.git notes
```

Then whenever you want new notes:
```bash
cd notes && git pull
```

## Manual Upload

You can also drag & drop PDFs directly on GitHub:
1. Go to the repo on github.com
2. Click "Add file" → "Upload files"
3. Drop your PDFs
4. Commit — conversion happens automatically!

---

Powered by [pdf2md](https://github.com/DEVLlN/pdf2md)
