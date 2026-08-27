# FamilyWall Recipe Site

This static site was generated from the Recipe Keeper export.

- Recipes: 122
- Recipe pages: one HTML file per recipe
- Images: preserved from Recipe Keeper
- Structured data: Schema.org `Recipe` JSON-LD on every recipe page
- Search/filter index: `index.html`

## Important

FamilyWall's "import from web" feature needs a publicly reachable web URL.
Opening these HTML files directly from your computer or phone is useful for
previewing, but FamilyWall generally needs an HTTPS URL it can fetch.

## Easy hosting options

### GitHub Pages
1. Create a new GitHub repository.
2. Upload the contents of this folder, not the outer ZIP.
3. In repository Settings > Pages, deploy from the main branch/root.
4. GitHub will provide an HTTPS site address.
5. Open a recipe on the deployed site and paste that recipe's URL into
   FamilyWall's web-recipe import.

### Netlify
Drag the unzipped site folder into Netlify Drop and use the HTTPS address it
creates.

## Testing

Start with one simple recipe. Verify that FamilyWall recognizes:
- title
- ingredients
- directions
- photo
- servings
- prep/cook times

If a specific FamilyWall parser behaves differently, the pages can be adjusted
without changing the original Recipe Keeper export.
