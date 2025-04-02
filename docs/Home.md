# Wiki Sync PoC

## Pros

1. Documentation is synchronised between `.md` files and the wiki.
2. The workflow can be extended to trigger pull requests on wiki page edits.

## Cons

1. Links to files either work locally in `.md` files *or* on the wiki, but not both.
2. The wiki interface is primitive.
3. Templating is primitive (only sidebar and footer templates exist).

## Conclusion

The repository should be the single source of truth for engineering documentation. Markdown files 
should be prioritised, however for increased visibility and ease of access (i.e. quick linking) 
it is probably worth implementing this synchronisation workflow, with the workflow only being 
triggered on pull requests which include the `documentation` label.
