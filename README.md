# Mangal Manav Bharti Trust Website

This repository contains the official website of **Mangal Manav Bharti Trust**, a public charitable institution based in Jaipur, India.

🌐 Website: https://mangalmanavbharti.org

---

## About the Trust

Mangal Manav Bharti Trust is a public charitable institution dedicated to advancing knowledge, education, and intellectual engagement for the benefit of society.

The Trust works towards building inclusive platforms for learning, dialogue, and creative expression, with a focus on long-term societal and intellectual development.

---

## Core Areas of Work

- Promotion of education and research  
- Development of intellectual and dialogue platforms  
- Encouragement of literary and creative expression  
- Establishment of physical and digital knowledge institutions  
- Expanding access to knowledge across diverse sections of society  

---

## Key Initiative

### Literary and Creative Publication Initiative

The Trust undertakes initiatives to collect and publish literary, reflective, and creative writings from individuals, including armed forces veterans and other contributors.

These works are curated and published in book form to preserve expression, memory, and intellectual contribution as a lasting legacy for families, communities, and future generations.

---

## Repository Structure

    mmbtrust-www/
    ├── index.md
    ├── _config.yml
    ├── _layouts/
    ├── _includes/
    ├── _people/
    ├── pages/
    ├── assets/
    └── Gemfile

---

## Local Development

### Requirements

- Ruby (2.7 or higher)  
- Bundler  

### Setup

    git clone https://github.com/mangalmanavbharti/mmbtrust-www.git
    cd mmbtrust-www

    bundle install
    bundle exec jekyll serve

Visit: http://localhost:4000

---

## Deployment

The site is deployed via GitHub Pages.

    git add .
    git commit -m "Update website"
    git push origin main

---

## Content Management

### Adding a Page

- Create a file in `pages/`
- Add frontmatter:

    ---
    layout: page
    title: Page Title
    permalink: /page-url/
    ---

### Adding a Member

- Add a file in `_people/`
- Use consistent slug naming
- Maintain bilingual consistency (`/` and `/en/` routes)

---

## Troubleshooting

### Site not updating after push

- Ensure GitHub Pages is enabled (Settings → Pages → main branch)
- Wait 1–2 minutes for rebuild
- Check Actions tab for build errors

### Local build issues

    rm -rf .jekyll-cache _site
    bundle install --redownload
    bundle exec jekyll serve

### Styling not applying

- Clear browser cache  
- Ensure `assets/css/style.scss` compiles  
- Check browser dev tools for errors  

---

## Contributing

Contributions are welcome for improving content, structure, and accuracy.

1. Fork the repository  
2. Create a branch: `git checkout -b feature/update`  
3. Make changes and test locally  
4. Submit a Pull Request  

---

## Contact

📧 contact@mangalmanavbharti.org  
📍 Jaipur, Rajasthan, India  

---

## Resources

- https://jekyllrb.com/docs/  
- https://pages.github.com/  
- https://commonmark.org/help/  

---

## Notes

This repository represents the official digital presence of the Trust and reflects its institutional, intellectual, and public-oriented mission.

---

**Last Updated:** 2026
