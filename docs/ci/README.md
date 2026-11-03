# Optional collection check

`checks.yml` is a template for auditing the catalog's publication files. It is not an active workflow. A maintainer with workflow permissions can place it under `.github/workflows/` to enable GitHub Actions.

Application tests and setup instructions live in the individual project repositories. The collection does not install or run all four tools together.

To run the catalog check locally:

```sh
python scripts/audit_public.py
```
