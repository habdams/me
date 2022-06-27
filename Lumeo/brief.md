If an SCSS variable does not exist, consider creating one!
If a custom CSS color property does not exist, scream at me.

#### styles/variables
  - colors (CSS custom properties)
    - danger.scss
    - primary.scss
    - secondary.scss
    - success.scss
    - ui.scss
    - warning.scss

  - dimensions.scss
  - misc.scss -- border-radius & box-shadows.

  - z-index.scss
  - font.scss


#### Most important styling components

For headlines (or headline styles), use
<Heading level="1|2|3|4" />
The level automatically translates to hierarchy, but sometimes you need to decouple the styling from the hierarchy. For this, use the `useChild` prop.
<Heading level="2" asChild>
  <p>...</p>
</Heading>

I do try to adhere to the hierarchy to make sure the `asChild` prop will be as rare as possible. 


For standalone (non-interactive, e.g. not labels) text, use
<Text />
* prop `type` (info) for deemphasized text
* prop `intent` (danger)
* prop `size` (small, xmall, xxsmall)


models

hooks
api / API object + react-query hooks