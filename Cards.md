# Cards

Component that allow the creation of content based on an image with a title information visible and a hover effect that shows more information.

## Structure of the parent

| Field Name  |        Type         | Required | Details                                            |
| :---------- | :-----------------: | :------: | :------------------------------------------------- |
| Title       |     Plain Text      |    No    | Rendered as H3                                     |
| Description |      Long Text      |    No    | With WYSIWYG and characters counting, limit to 200 |
| Card Item   | Paragraph reference |    No    | At least 3 to unlimited                            |

## Structure of the Card Item

| Field Name       |    Type    | Required | Details                                       |
| :--------------- | :--------: | :------: | :-------------------------------------------- |
| Image            |   Image    |   Yes    | jpg, jpeg, png, gif, aspect ratio 1:1 380x380 |
| Title            | Plain Text |   Yes    | Rendered as h4                                |
| Item Description | Plain Text |    No    |                                               |
| Link             |    link    |    No    | Allow to edit the Link Title and the target.  |

## 

![Cards](./assets/cards.png)