# GHAKANYUY FABRICE BONGBARAH — Portfolio Website

A responsive, multi-page portfolio built with HTML, CSS and vanilla JavaScript. It is designed to be edited in Spyder and run locally with Python's built-in HTTP server.

## Pages
- `index.html` — homepage and selected work
- `about.html` — biography, skills, education, experience and training
- `projects.html` — five detailed project case studies
- `contact.html` — email, phone and LinkedIn contact details

## Run locally in Spyder (Windows)
Open the Spyder IPython console and run:

```python
import os
os.chdir(r"C:\path\to\ghakanyuy_fabrice_portfolio")
!python -m http.server 8000
```

Then open http://localhost:8000 in your browser. Stop the server with Ctrl+C in the console.

## Personalise before publishing
- Check the CV PDF in `assets/documents/` and replace it whenever your CV changes.
- The LinkedIn profile is linked. Add your GitHub profile/repository URLs when ready; no GitHub URL was included in the information available for this build.
- Check the displayed phone number and email before making the site public.
- Review project descriptions and update each status as projects progress.

## Publish
This is a static website and can be deployed to GitHub Pages, Netlify or another static hosting provider. No Python backend or database is required.


## GitHub

Portfolio owner: https://github.com/bongbarah

Public repositories currently linked from the project case studies:
- AI Data Analysis Agent: https://github.com/bongbarah/ai-data-analysis-agent
- Credit Risk Intelligence Platform: https://github.com/bongbarah/credit-risk-intelligence
