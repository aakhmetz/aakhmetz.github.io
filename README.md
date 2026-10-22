# aakhmetz.github.io

Personal and group website of **Andrei R. Akhmetzhanov (吳亞克)**, Associate Professor at the [Global Health Program](https://ghp.ntu.edu.tw/) and the [Institute of Epidemiology and Preventive Medicine](https://epm.ntu.edu.tw/web/index/index.jsp), College of Public Health, National Taiwan University, Taipei, Taiwan.

🌐 **Live site:** https://aakhmetz.github.io

## Editing the site

The site is built with Jekyll (academicpages template) by GitHub Pages from the `master` branch.

- `index.md` – home page and news
- `_pages/` – Research, CV, Group, Opportunities, Talks and Publications pages
- `_data/publications.yml` – publication list (one entry per paper; the Publications page groups them by year)
- `_data/members.yml` – group members and alumni (photos go in `images/members/`, square, about 600x600 px). Adding `bio`, `hobbies`, `favorite_food` or `favorite_quote` to a member turns the card into a clickable popup (markup in `_includes/group-members.html`)
- `_data/group_photos.yml` – photo gallery at the bottom of the Group page (files in `images/group/`, about 1600 px wide; the section is hidden while the list is empty)
- `_data/navigation.yml` – top menu
- `_config.yml` – site title, sidebar profile and links

To preview locally with Docker: `docker compose up` and open http://localhost:4000. Without Docker: install Ruby 3, then `bundle install` and `bundle exec jekyll serve`.
