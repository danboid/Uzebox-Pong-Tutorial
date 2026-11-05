# Converting markdown (.md) to PDF

I converted the markdown assembly guide into a PDF under Debian using these commands:

```
sudo apt install pandoc weasyprint
pandoc README.md -o Uzebox-Pong-Tutorial.pdf --pdf-engine=weasyprint --css=style.css
```

