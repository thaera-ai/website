# Website guidance

This is a static public landing page: index.html contains markup/styles; CNAME
declares thaera.ai. There is no package/build/test pipeline. Preserve responsive
layout, accessibility, reduced-motion behavior and the existing palette. Preview
changes at desktop/mobile widths and run `git diff --check`.

For cross-repo context read sibling `thaera-cli/docs/project-context.md` when
available. CLI/catalog repos are private: do not copy private state or internal
findings into this public repo. Hosting/deployment settings and product positioning
must be verified separately; a CNAME file does not prove live deployment.
