# tristatian.github.io

Source of the personal site at https://tristatian.github.io. Static HTML and
CSS, no framework, no build step, no analytics.

- `index.html` — home page and project list
- `projects/` — one page per project
- `resume/` — resume page; `resume/ZiyaoTian.pdf` is the published PDF
- `style.css` — the one stylesheet

Every number on a project page comes from `resume_pipeline/profile/master_profile.md`
in the private project that generates the resumes. Do not edit a number here
without updating that file first.

The Clean Chat page at https://tristatian.github.io/clean-chat/ is served from
the separate `clean-chat` repository (GitHub Pages on its `main` branch). Do not
add a `clean-chat/` folder to this repository: it would shadow that page.
