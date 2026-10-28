# Festeryga Law: spatial refinement preview (client design review)

Review-only staging for Edward Festeryga. Publishes branch `spatial-refinement-oct27` of
[MozwellStudios/festeryga-site](https://github.com/MozwellStudios/festeryga-site) to
https://mozwellstudios.github.io/festeryga-spatial-preview/ .

- Deploys only when run by hand (Actions > Deploy spatial preview > Run workflow). No automatic triggers.
- Every page is `noindex, nofollow`; `robots.txt` disallows all crawling. The deploy fails if any page lacks noindex.
- The design prototypes (`prototypes/`) are not published. The contact form is a demo: nothing is sent.
- Version A (festeryga-site `main`, GitHub Pages) and Option B (festeryga-option-b) are separate and untouched.
