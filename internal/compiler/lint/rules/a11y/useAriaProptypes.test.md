# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `a11y/useAriaProptypes`

### `0`

```

 lint/a11y/useAriaProptypes/reject/1/file.tsx:1:22 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-checked is not correct.


```

### `0: formatted`

```tsx
<span role="checkbox" aria-checked="test" />;

```

### `1`

```

 lint/a11y/useAriaProptypes/reject/2/file.tsx:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-autocomplete is not correct.

  ℹ The supported values for the aria-autocomplete attribute are: "inline", "list", "both", "none"


```

### `1: formatted`

```tsx
<span aria-autocomplete="test" />;

```

### `2`

```

 lint/a11y/useAriaProptypes/reject/3/file.tsx:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-invalid is not correct.

  ℹ The supported values for the aria-invalid attribute are: "grammar", false, "spelling", true


```

### `2: formatted`

```tsx
<span aria-invalid="foo" />;

```

### `3`

```

 lint/a11y/useAriaProptypes/reject/4/file.tsx:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-errormessage is not correct.


```

### `3: formatted`

```tsx
<span aria-errormessage="" />;

```

### `4`

```

 lint/a11y/useAriaProptypes/reject/5/file.tsx:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-relevant is not correct.

  ℹ The supported values for the aria-relevant attribute are: "additions", "all", "removals",
    "text"


```

### `4: formatted`

```tsx
<span aria-relevant="fancy" />;

```

### `5`

```

 lint/a11y/useAriaProptypes/reject/6/file.tsx:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-labelledby is not correct.


```

### `5: formatted`

```tsx
<span aria-labelledby="" />;

```

### `6`

```

 lint/a11y/useAriaProptypes/reject/7/file.tsx:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-labelledby is not correct.


```

### `6: formatted`

```tsx
<span aria-labelledby={""} />;

```

### `7`

```

 lint/a11y/useAriaProptypes/reject/8/file.tsx:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-details is not correct.


```

### `7: formatted`

```tsx
<span aria-details="" />;

```

### `8`

```

```

### `8: formatted`

```tsx
<span role="checkbox" aria-checked={checked} />;

```

### `9`

```

```

### `9: formatted`

```tsx
<span role="checkbox" aria-checked="true" />;

```

### `10`

```

```

### `10: formatted`

```tsx
<span role="checkbox" aria-checked={true} />;

```

### `11`

```

```

### `11: formatted`

```tsx
<span role="checkbox" aria-checked="false" />;

```

### `12`

```

```

### `12: formatted`

```tsx
<span role="checkbox" aria-checked="mixed" />;

```

### `13`

```

```

### `13: formatted`

```tsx
<span role="checkbox" aria-autocomplete="both" />;

```

### `14`

```

```

### `14: formatted`

```tsx
<span role="checkbox" aria-autocomplete="inline" />;

```

### `15`

```

```

### `15: formatted`

```tsx
<span role="checkbox" aria-autocomplete="list" />;

```

### `16`

```

```

### `16: formatted`

```tsx
<span role="checkbox" aria-autocomplete="none" />;

```

### `17`

```

```

### `17: formatted`

```tsx
<span aria-invalid="true" />;

```

### `18`

```

```

### `18: formatted`

```tsx
<span aria-invalid="grammar" />;

```

### `19`

```

```

### `19: formatted`

```tsx
<span aria-invalid="false" />;

```

### `20`

```

```

### `20: formatted`

```tsx
<span aria-invalid={false} />;

```

### `21`

```

```

### `21: formatted`

```tsx
<span role="checkbox" aria-errormessage="someid" />;

```

### `22`

```

```

### `22: formatted`

```tsx
<span role="checkbox" aria-relevant="additions" />;

```

### `23`

```

```

### `23: formatted`

```tsx
<span role="checkbox" aria-relevant="additions all" />;

```

### `24`

```

```

### `24: formatted`

```tsx
<span aria-labelledby="id" />;

```

### `25`

```

```

### `25: formatted`

```tsx
<span aria-labelledby="fooId barId" />;

```

### `26`

```

```

### `26: formatted`

```tsx
<span aria-details="someid" />;

```

### `27`

```

 lint/a11y/useAriaProptypes/reject/1/file.html:1:22 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-checked is not correct.


```

### `27: formatted`

```html
<span role="checkbox" aria-checked="test">
</span>

```

### `28`

```

 lint/a11y/useAriaProptypes/reject/2/file.html:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-autocomplete is not correct.

    <span aria-autocomplete="test" ></span>
          ^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ The supported values for the aria-autocomplete attribute are: "inline", "list", "both", "none"


```

### `28: formatted`

```html
<span aria-autocomplete="test">
</span>

```

### `29`

```

 lint/a11y/useAriaProptypes/reject/3/file.html:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-invalid is not correct.

    <span aria-invalid="foo"></span>
          ^^^^^^^^^^^^^^^^^^

  ℹ The supported values for the aria-invalid attribute are: "grammar", false, "spelling", true


```

### `29: formatted`

```html
<span aria-invalid="foo">
</span>

```

### `30`

```

 lint/a11y/useAriaProptypes/reject/4/file.html:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-errormessage is not correct.

    <span aria-errormessage="" ></span>
          ^^^^^^^^^^^^^^^^^^^^


```

### `30: formatted`

```html
<span aria-errormessage="">
</span>

```

### `31`

```

 lint/a11y/useAriaProptypes/reject/5/file.html:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-relevant is not correct.

    <span aria-relevant="fancy" ></span>
          ^^^^^^^^^^^^^^^^^^^^^

  ℹ The supported values for the aria-relevant attribute are: "additions", "all", "removals",
    "text"


```

### `31: formatted`

```html
<span aria-relevant="fancy">
</span>

```

### `32`

```

 lint/a11y/useAriaProptypes/reject/6/file.html:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-labelledby is not correct.

    <span aria-labelledby="" ></span>
          ^^^^^^^^^^^^^^^^^^


```

### `32: formatted`

```html
<span aria-labelledby="">
</span>

```

### `33`

```

 lint/a11y/useAriaProptypes/reject/7/file.html:1:6 lint/a11y/useAriaProptypes ━━━━━━━━━━━━━━━━━━━━━━

  ✖ The value of the ARIA attribute aria-details is not correct.

    <span aria-details="" ></span>
          ^^^^^^^^^^^^^^^


```

### `33: formatted`

```html
<span aria-details="">
</span>

```

### `34`

```

```

### `34: formatted`

```html
<span role="checkbox" aria-checked="true">
</span>

```

### `35`

```

```

### `35: formatted`

```html
<span role="checkbox" aria-checked="false">
</span>

```

### `36`

```

```

### `36: formatted`

```html
<span role="checkbox" aria-checked="mixed">
</span>

```

### `37`

```

```

### `37: formatted`

```html
<span role="checkbox" aria-autocomplete="both">
</span>

```

### `38`

```

```

### `38: formatted`

```html
<span role="checkbox" aria-autocomplete="inline">
</span>

```

### `39`

```

```

### `39: formatted`

```html
<span role="checkbox" aria-autocomplete="list">
</span>

```

### `40`

```

```

### `40: formatted`

```html
<span role="checkbox" aria-autocomplete="none">
</span>

```

### `41`

```

```

### `41: formatted`

```html
<span aria-invalid="true">
</span>

```

### `42`

```

```

### `42: formatted`

```html
<span aria-invalid="grammar">
</span>

```

### `43`

```

```

### `43: formatted`

```html
<span aria-invalid="false">
</span>

```

### `44`

```

```

### `44: formatted`

```html
<span role="checkbox" aria-errormessage="someid">
</span>

```

### `45`

```

```

### `45: formatted`

```html
<span role="checkbox" aria-relevant="additions">
</span>

```

### `46`

```

```

### `46: formatted`

```html
<span role="checkbox" aria-relevant="additions all">
</span>

```

### `47`

```

```

### `47: formatted`

```html
<span aria-labelledby="id">
</span>

```

### `48`

```

```

### `48: formatted`

```html
<span aria-labelledby="fooId barId">
</span>

```

### `49`

```

```

### `49: formatted`

```html
<span aria-details="someid">
</span>

```
