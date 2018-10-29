# Featured Block



The Featured Block will be part of the components field that allows multiple paragraphs to be entered in a page at the same time.

## Structure of the parent

| Field Name          |        Type         | Required | Details                                                      |
| :------------------ | :-----------------: | :------: | :----------------------------------------------------------- |
| Title               |     Plain Text      |    No    | Rendered as H3                                               |
| Description         |      Long Text      |    No    | With WYSIWYG and characters counting, limit to 200           |
| Overlay             |        Color        |   Yes    | RGBA value (color + opacity), defaulted to `rgba(0, 0, 0, 0)` |
| Featured Block Item | Paragraph reference |   Yes    | At least 1                                                   |
| Footer              |     Plain Text      |    No    |                                                              |

## Structure of the InfoGraphic Item

| Field Name       |    Type    | Required | Details                      |
| :--------------- | :--------: | :------: | :--------------------------- |
| Full width?      |  boolean   |   yes    | (checkbox default value off) |
| Image            |   Image    |   yes    | 460pxX340                    |
| Title            | Plain Text |    No    |                              |
| Item Description | Plain Text |    No    |                              |
| Link             |    link    |    No    |                              |

## Acceptance Criteria

- On load if Style is Transition, as soon as the component get visible into the viewport the items need to change from Black and White to be colored, if any of the other options are selected, follow as specified (black and White or full colored).
- This can hold one item or maximum 6, accordingly they will get centered until 4 that can take all the space of the content.
- The numbers will be animated as a counter from 0 to the value entered.

## Design

![Infographic](/Users/kendall/Sites/WFSCorp_Doc/assets/infographic.png)

![Infographic](/Users/kendall/Sites/WFSCorp_Doc/assets/infographic1.gif)

