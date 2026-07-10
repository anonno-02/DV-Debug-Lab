# Daily Upload Checklist

Use this after creating a new topic package.

## Files to add

- [ ] Add article under the correct `docs/` category
- [ ] Add example folder under `examples/`
- [ ] Add images/diagrams under `docs/assets/`
- [ ] Update `mkdocs.yml` navigation
- [ ] Update `docs/topics.md`
- [ ] Update category index page if needed

## Local validation

```bash
mkdocs serve
```

Check:

- [ ] Page opens
- [ ] Navigation link works
- [ ] Code blocks render correctly
- [ ] Checklist renders correctly
- [ ] Internal links work
- [ ] No broken headings
- [ ] No company-confidential information

## Publish

```bash
git add .
git commit -m "Add topic: short topic name"
git push
```
