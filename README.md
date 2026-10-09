# TheLightPress

**Stories. Ideas. Opinions. Reflections.**

TheLightPress is a digital publishing initiative dedicated to stories, creative writing, opinions, reflections, and ideas worth sharing. It provides a home for individual pieces of writing presented through a clean, carefully designed web experience.

This repository contains standalone HTML publications for TheLightPress. GitHub Pages is used to host these pages, while Blogger can serve as a complementary publishing and discovery platform.

## Purpose

The repository exists to:

- Publish individual stories and written works as independent web pages.
- Give each publication its own shareable URL.
- Support custom page layouts and typography beyond a standard blog post.
- Connect selected publications with TheLightPress content on Blogger.
- Keep published works organised and maintainable as the collection grows.

## How it works

1. **Create:** Write and format a publication in an individual HTML file.
2. **Publish:** Commit the file to the repository and publish it through GitHub Pages.
3. **Share:** Use the resulting page URL in links, Blogger posts, or other suitable channels.
4. **Maintain:** Update the HTML file when the publication needs corrections or improvements.

Each HTML file can be accessed directly using its published URL. A root `index.html` is not required merely to publish individual files, provided GitHub Pages is configured to publish the directory containing them.

## Repository structure

The repository is designed to keep individual publications independent.

```text
TheLightPress/
├── README.md
├── story-title.html
├── opinion-title.html
├── reflection-title.html
└── another-publication.html
```

These filenames are illustrative. Use descriptive, consistent filenames that are easy to identify and share. Supporting assets, such as stylesheets, images, fonts, or scripts, may be organised into separate folders as the project grows.

## Publication guidelines

- Give each publication a clear, descriptive filename.
- Use semantic HTML and accessible page structure.
- Ensure pages work on mobile screens as well as desktop screens.
- Keep styles and scripts organised and avoid unnecessary dependencies.
- Use relative paths for repository assets where practical.
- Test each published URL after changes are deployed.
- Check image rights, quotations, attribution, and permissions before publishing material that belongs to others.
- Avoid placing passwords, API keys, private information, or other secrets in this public repository.

## Blogger integration

Published HTML pages may be linked from Blogger or embedded in a Blogger post where appropriate.

- **Linking** directs readers to the standalone publication.
- **Embedding** displays a hosted page within a Blogger page, subject to browser, platform, and layout limitations.

The HTML page remains a separate document hosted by GitHub Pages. Updating the source file and waiting for deployment updates that hosted page; it does not automatically copy the article into Blogger's native post content.

## Publishing and maintenance

GitHub Pages must be enabled for the repository and configured to publish from the correct branch and folder. After committing changes, allow the deployment to complete and test the exact URL for each publication.

If a page does not load, check the filename, letter case, file location, Pages settings, and deployment status.

## About TheLightPress

TheLightPress is part of the wider **TheLightOdrus** initiative.

Its focus is writing and publishing: sharing stories, exploring perspectives, expressing ideas, and creating work that readers can return to and share.

---

*TheLightPress — A space for stories, ideas, opinions, and reflections.*
