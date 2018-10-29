The Auto Scroller will contain multiple Items that provide the effect of an item being highlighted over the others.

## Structure of the parent

| Field Name       |        Type         | Required | Details               |
| :--------------- | :-----------------: | :------: | :-------------------- |
| Title            |     Plain Text      |    No    | Rendered as H3        |
| Description      |      Long Text      |    No    | With WYSIWYG and characters counting, limit to 200 |
| Style            |     Text(list)      |   Yes    | Default Value "B/W to Color", values: Black and White to Color, Colored to Blak and White |
| Scroller Item    | Paragraph reference |   Yes    | At least 3 maximum 5  |
| Footer           |     Plain Text      |    No    |                       |

## Structure of the InfoGraphic Item

| Field Name       |    Type    | Required | Details             |
| :--------------- | :--------: | :------: | :------------------ |
| Image            |   Image    |    No    | jpg, jpeg, png, gif |
| Title            | Plain Text |    Yes   |                     |
| Item Description | Long Text  |    No    |                     |
| Link             | Plain Text |    No    |                     |


## Acceptance Criteria

- On load, if Style is B/W to Color, as soon as the component get visible into the viewport the items will be shown in a Gray Scale using CSS, once the user mouse over one of them the image get colored, expanded and show the rest of the content.
- This can hold 3 items or maximum 5.
- The text content inside each item needs to be taken into consideration in order to always keep the text visible.

## Design

![Infographic](./assets/autoscroller.gif)

