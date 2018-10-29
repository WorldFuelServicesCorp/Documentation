Text content will allow the editor to create a block of copy text using the WYSIWYG tool, having a specific field for the title and an optional field for a footer.

| Field Name    | Type            | Required  | Details           |
|:------------- |:---------------:|:---------:|:------------------|
| Title         | Plain Text      |     No    | Rendered as H3    |
| Description   | Long Text       |     No    | WYSIWYG and counter enabled|
| Footer Note   | Plain Text      |     No    | No                |
| Style         | Text (list)     |     No    | Values: Dark (blue), light (same as CTA), None |

## Acceptance Criteria
* The component should allow the editor to overwrite the default CSS using the WYSIWYG tool.
* If any of the fields is fill the component should present an error that says: "Empty paragraph should not use. Please fill it with data or take it out".

## Design
![Infographic](./assets/TextBlock.png)