# Simpson's Paradox Visualiser

A standalone interactive visualiser for Simpson's paradox.

## What it shows

Simpson's paradox occurs when a relationship seen inside each subgroup reverses or disappears after the groups are pooled. This visualiser creates grouped data where:

- X has a positive effect inside each group.
- Higher-X groups can nevertheless have lower average Y.
- The pooled association can therefore point in the opposite direction from the within-group associations.

## Controls

The key controls are labelled to make the data-generating structure explicit:

- `Effect of X inside each group`: the within-group relationship.
- `Average X gap between neighbouring groups`: how far apart the groups are horizontally.
- `Average Y drop for each higher-X group`: the confounding pattern that can reverse the pooled association.
- `X variation inside each group`: horizontal spread inside each group.
- `Y noise around each group line`: random variation around each group's line.

## Deployment on GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `README.md`.
3. Commit to the `main` branch.
4. In GitHub, go to `Settings` then `Pages`.
5. Choose `Deploy from a branch`.
6. Select the `main` branch and the root folder.
7. Save.

The visualiser should then be published at a GitHub Pages URL.

## Embedding

You can embed the published page in another website with an iframe:

```html
<iframe
  src="https://your-username.github.io/your-repo-name/"
  width="100%"
  height="980"
  style="border:0; border-radius:16px;"
  loading="lazy">
</iframe>
```
