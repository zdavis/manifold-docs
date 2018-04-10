---
layout: page
title: Metadata
menu:
  reference:
    weight: 2
---

The following metadata fields are made available through Manifold. The three columns—`Project`, `Text`, and `Resource`—denote where the fields apply.

`Project`-level metadata describes a project in its entirety, whereas `Text`- and `Resource`-level metadata describes specific materials within a project.

| Metadata Field           | [Project][1] | [Text][2] | [Resource][3] |
|--------------------------|:------------:|:---------:|:-------------:|
| Alt Text                 |              |           |       x       |
| Caption                  |              |           |       x       |
| Container Title          |       x      |           |       x       |
| Copyright Status         |              |           |       x       |
| Creator                  |              |           |       x       |
| Credit                   |              |           |       x       |
| Description              |       x      |     x     |       x       |
| DOI                      |       x      |           |       x       |
| Edition                  |       x      |           |       x       |
| ISBN                     |       x      |           |       x       |
| ISSN                     |       x      |           |       x       |
| Issue                    |       x      |           |       x       |
| Original Publisher       |       x      |           |       x       |
| Original Publisher Place |       x      |           |       x       |
| Original Title           |       x      |           |       x       |
| Publication Date         |       x      |     x     |               |
| Publisher                |       x      |           |       x       |
| Publisher Place          |       x      |           |       x       |
| Restrictions             |       x      |           |       x       |
| Rights                   |       x      |           |       x       |
| Rights Holder            |       x      |           |       x       |
| Rights Territory         |       x      |           |       x       |
| Series Number            |       x      |           |       x       |
| Series Title             |       x      |           |       x       |
| Subtitle                 |       x      |           |               |
| Tags                     |              |           |       x       |
| Title                    |       x      |     x     |       x       |
| Version                  |       x      |           |       x       |
| Volume                   |       x      |           |       x       |

## Metadata Field Descriptions

This section groups all the metadata fields available in Manifold by general category with descriptions on how to approach them, depending on the kinds of materials they are referring.

### Copyright

**Creator**. Person or entity credited with creation of the media (as opposed to the creator of the file).
Resource Only

**Rights**. The copyright line and licensing details.
Resource Only

**Rights Holder**. Name of the institution, agency, or individual granting authority to reproduce the material; may be same as source or creator.

**Rights Territory**. The geographic scope of where the rights to this material extend.

**Restrictions**. Describe any restrictions the grantor has placed on use of the material.

**Credit**. The official language the rights grantor has requested to be associated with the resource.

### Identity

**ISBN**. The International Standard Book Number you've assigned to your project as a whole, including the version of record and all the texts and resources associated with it. This field accepts only one entry but can display ISBNs of either the ISBN-10 or ISBN-13 format.

If you have a resource that has been assigned an ISBN, it can be included in the [Resource metadata](/docs/projects/customizing/resources.html) section.

**ISSN**. The International Standard Serial Number you've assigned to your project as a whole, including the version of record and all the texts and resources associated with it.

If you have a resource that has been assigned an ISSN, it can be included in the [Resource metadata](/docs/projects/customizing/resources.html) section.

**DOI**. A digital object identifier can be entered for projects, generally, and all resources associated with it.

### Publisher

**Publisher**. The name of the press or unit guiding and disseminating the material.

**Publisher Place**. The geographical location of the publisher

**Original Publisher**. If the material is being reprinted or translated, this field provides a means to name its original publisher.

**Original Publisher Place**. For reprinted or translated materials, the geographical location of the original publisher.

### Bibliographic

**Title**. The material's title.

**Subtitle**. The material's subtitle.

**Container Title**. When the material in question is part of a larger whole, that larger whole can be thought of as the container. An example would be an individual chapter in a contributed volume or one piece of art in an exhibition.

**Version**. This is number specific to the publisher in describing the unique state of the material in question.

**Series Title**. For material that is part of a series, any title associated with that group can be documented here.

**Series Number**. For material that is part of a series, the number describing where it is oriented in that series can be documented here.

**Edition**. This field corresponds with the the name of the materials edition as provided by the publisher (e.g., 2nd ed., Director's Cut)

**Issue**. If the material in question is published serially, you can denote its issue number in that series here.

**Volume**. If the material in question is published serially, you can denote its volume number in that series here.

**Original Title**. If the material is being reprinted or translated, this field provides a means to describe its original title.

**Publication Date**. This is the date the material in question was initially published.

### Accessibility

**Alt Text**. Assistive technologies will use this field to describe the nature of the media in question. When crafting your copy, consider what it would be like if the media were absent. Avoiding redundancy with a caption (if present), briefly describe what a replacement for the media would be.

**Caption**. This is the scholarly information or context that answers of the media, `What does this mean?` or `What is of interest about this?` This would mirror what would appear below the media if it were to appear in print.

**Description**. For projects and texts, this field is a means to orient the reader as to its nature and intent.

For resources, the `Description` is an opportunity to translate the visual to the textual—a means to re-create the media in the mind's eye by way of a written description. What are the important elements of what is shown in the media?

### Other

**Copyright Status**. A means to describe where this material falls in the copyright landscape (e.g., Public Domain, Fair Use, In Copyright, Unknown)

**Tags**. Tags group and relate media to one another and can server as a mean to navigate among like materials.

[1]: /docs/projects/customizing/metadata.html
[2]: /docs/projects/customizing/texts.html#managing-texts
[3]: /docs/projects/customizing/resources.html