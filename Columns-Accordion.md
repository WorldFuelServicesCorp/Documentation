# Columns Accordion

Allow to have columns with a full width background with internal content per columns showed on the hover effect on the column.

## Structure of the parent

| Field Name  |        Type         | Required | Details                                                      |
| :---------- | :-----------------: | :------: | :----------------------------------------------------------- |
| Title       |     Plain Text      |    No    | Rendered as H3                                               |
| Description |      Long Text      |    No    | With WYSIWYG and characters counting, limit to 200           |
| Image       |        Image        |    No    | jpg, jpeg, png, gif                                          |
| Overlay     |        Color        |   Yes    | RGBA value (color + opacity), defaulted to `rgba(0, 0, 0, 0)` |
| Column Item | Paragraph reference |   Yes    | At least 1 maximum 6                                         |

## Structure of the Column Item

| Field Name       |    Type    | Required | Details |
| :--------------- | :--------: | :------: | :------ |
| Title            | Plain Text |   Yes    |         |
| Item Description | Long Text  |    No    |         |
| Link             |    Link    |    No    |         |

## 

![Columns Accordion](./assets/col_accordion.png) 