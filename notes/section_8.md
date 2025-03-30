# The CSS Box Model

## 80. The Display Property

- Display: block vs inline vs inline-block:

  `block`: element takes up the full width of its container; all box model properties are respected (width, height, padding, border, and margin)

  `inline`: element takes up only as much space as needed; box model properties are not respect (except border)

  `inline-block`: element only takes up only as much space as needed; all box model properties are respected (width, height, padding, border, and margin)

## 90. CSS Units: ems

- `em`:

  relative to parent's font size when used for the font-size property and to element's own font size when used for anything else;

  especially used for defining properties of an object (e.g. a button) that is reusable and expected to respectively scale depending on why it is place.

## 91. CSS Units: rems

- `rem`:

  relative to root element's (`<html>`) font size; Creates consistency throughout a project.

  especially used when using the em unit creates a cascading effect where nested elements can inherit and compound font sizes unexpectedly (as in the case of nested lists)
