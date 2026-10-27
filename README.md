# helenchang68.github.io

Personal portfolio: applied AI projects and case studies. Plain HTML + one CSS file, no build step.

## Structure

```
index.html            Home: positioning + selected projects
about.html            Background and what I'm looking for
projects/index.html   All projects (case studies + in progress)
projects/speakup.html First case study
projects/TEMPLATE.html Copy this for every new project
writing/index.html    Links to LinkedIn posts / notes
assets/css/style.css  All styling (colours at the top)
assets/img/           Screenshots for case studies
```

## Add a new project

1. Copy `projects/TEMPLATE.html` to `projects/<project-name>.html` and fill in the `[ ... ]` parts.
2. Add a card for it in `projects/index.html` (copy an existing `<a class="card">` block).
3. If it's a highlight, add the same card to `index.html`.
4. Commit and push. The site updates in about a minute.

## Still to fill in

- Replace `YOUR-LINKEDIN-HANDLE` in every page (search the repo for it).
- SpeakUp: demo URL, cost numbers, test results (yellow TODO boxes on the page).
- Writing: replace the placeholder card with your best 3 to 5 posts.
