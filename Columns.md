# Colums

Columns allow to embbed other paragraphs inside, giving the editor the ability to set different layouts to the content using the same paragraphs that usually can be added independently

## Structure

| Field Name  |        Type         | Required | Details                                                      |
| :---------- | :-----------------: | :------: | :----------------------------------------------------------- |
| Layout      |      Text list      |   Yes    | Values: 2, 3, 4, 5, 6. Based on this selection the Col # fields are showed. |
| Style       | Text (list)         |    No    | Values: Dark (blue), light (same as CTA), None |
| Title       |        Text         |    No    |                                                              |
| Description |      Long Text      |    No    | With WYSIWYG and characters counting, limit to 200           |
| Col 1       | Paragraph reference |   Yes    |                                                              |
| Col 2       | Paragraph reference |   Yes    |                                                              |
| Col 3       | Paragraph reference |    No    | Hide this field unless "Layout" field has been set to 3      |
| Col 4       | Paragraph reference |    No    | Hide this field unless "Layout" field has been set to 4      |
| Col 5       | Paragraph reference |    No    | Hide this field unless "Layout" field has been set to 5      |
| Col 6       | Paragraph reference |    No    | Hide this field unless "Layout" field has been set to 6      |

