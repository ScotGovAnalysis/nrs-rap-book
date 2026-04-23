# NRS RAP Book

## Book development

This book is currently in draft. We plan to build some basic documentation to
share with statisticians in NRS. The book will then be a live work in progress.

## Repo structure

The book is split into 4 sections:

-   RAP in NRS
-   Guidance
-   Training
-   Blog

Content for each section is organised into its own folder in this repo, and has
its own home page. For example, see `rap-in-nrs/index.qmd`. Additional pages for
each section should be stored in these sub-folders. For example, see
`rap-in-nrs/why-rap.qmd`.

## Adding content

The `main` branch is protected, so to add new content, create a new branch and
when ready, open a pull request for review and approval to merge to `main`.

To add a new content page:

1.  Create a new `.qmd` file in the relevant section folder.

2.  Add a YAML header to specify the title of the page; this is what will be
    used as the visual header when the page is rendered. For example:

    ```         
    ---
    title: "RAP in NRS"
    ---
    ```

3.  Add the new page to `_quarto.yml` to ensure it's listed in the sidebar/
    navbar. Follow the existing pattern to do this.
    
To preview the website during development, use `quarto::quarto_preview()`.
