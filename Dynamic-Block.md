The Dynamic Block allows to reference a _View_ of content it can have filters to search over the content

| Field Name    | Type            | Required  | Details           |
|:------------- |:---------------:|:---------:|:------------------|
| Title         | Plain Text      |     No    | Rendered as H3    |
| Description   | Long Text       |     No    | WYSIWYG|
| Hide filters for this dynamic content	   | Boolean      |     No    | Shows exposed filter flag |
| View   | Viewfield |     Yes    | A reference to a existing view |

## Acceptance Criteria
* The component should allow the editor to hide the filters if the view referenced it has Exposed Filters.
* Title and Description are optional fields.

## Design