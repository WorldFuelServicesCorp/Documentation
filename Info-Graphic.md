The Info Graphic will be part of the components field that allows multiple paragraphs to be entered in a page at the same time.

## Structure of the parent

| Field Name    | Type            | Required  | Details           |
|:------------- |:---------------:|:---------:|:------------------|
| Title         | Plain Text      |     No    | Rendered as H3    |
| Description   | Long Text       |     No    | With WYSIWYG and characters counting, limit to 200 |
| Style         | Text(list)      |     Yes   | Default Value "Transition", values: Colored, Blak and White, Transition from B/W to Colored |
| InfoGraphic Item| Paragraph reference|Yes   | At least 1 maximum 6|
| Footer        | Plain Text      |     No    |                   |

## Structure of the InfoGraphic Item
| Field Name    | Type            | Required  | Details           |
|:------------- |:---------------:|:---------:|:------------------|
| Image         | Image           |     No    | jpg, jpeg, png, gif|
| Prefix        | Plain Text      |     No    |                   |
| Numbers       | Plain Text      |     No    |                   |
| Suffix        | Plain Text      |     No    |                   |
| Item Description| Plain Text      |     No    |                   |

## Acceptance Criteria
* On load if Style is Transition, as soon as the component get visible into the viewport the items need to change from Black and White to be colored, if any of the other options are selected, follow as specified (black and White or full colored).
* This can hold one item or maximum 6, accordingly they will get centered until 4 that can take all the space of the content.
* The numbers will be animated as a counter from 0 to the value entered.

## Design
![Infographic](./assets/infographic.png)

![Infographic](./assets/infographic1.gif)


