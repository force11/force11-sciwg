## CodeMeta Task Force

### Aligning schema.org with CodeMeta vocabulary

The CodeMeta community has created a vocabulary adapted to describe software and specifically research software, by including a codemeta.json file in the root directory of your repository.

The vocabulary is a subset of schema.org (see [issue 161](https://github.com/codemeta/codemeta/issues/161)).

The following terms are not part of schema.org:
- softwareSuggestions
- maintainer
- contIntegration
- buildInstructions
- developmentStatus
- embargoDate
- funding
- issueTracker
- referencePublication
- readme

To easily work on the properties propositions, it would be best to use 
the detailed table with the following columns for each item:

status of each term:

- term
- type
- description
- lead
- status
- proposal text
- issue on CodeMeta
- issue on schema.org
- similar terms
- similar proposals
- Wikidata term
- Notes

#### Dashboard: [Google spreadsheet](https://docs.google.com/spreadsheets/d/1VmUBdgaC7mtj7gDNqTBzPUdosux1R26Cyp7qA7WHkNA/edit?usp=sharing)



### The steps for the adoption workflow

For each step you do, *update* in the Dashboard the status of the proposal with the step number and notes relative to the proposal

1. [done for all] *Choose* a property and note you are the lead for its preparation.
2. *Check* if there has been a proposal for this property on schema.org repository with or without label:&quot;schema.org vocab&quot;  ([all issues](https://github.com/schemaorg/schemaorg/issues?utf8=%E2%9C%93&amp;q=is%3Aissue+is%3Aopen+))
3. *Check* if the property exists on schema.org in other classes for a different domain (consider that the property may exist but its label may be a synonym of the property identified in Codemeta)
4. *Check* if the property exist on Wikidata ([https://www.wikidata.org/wiki/Q7397](https://www.wikidata.org/wiki/Q7397)) which will help in community consensus (see [Wikidata issue on schema.org](https://github.com/schemaorg/schemaorg/issues/280))
5. *Prepare* a proposition text.

Here are a couple of examples:

- [https://github.com/schemaorg/schemaorg/issues/809](https://github.com/schemaorg/schemaorg/issues/809)
- [https://github.com/schemaorg/schemaorg/issues/148](https://github.com/schemaorg/schemaorg/issues/148)
- [https://github.com/schemaorg/schemaorg/issues/2300](https://github.com/schemaorg/schemaorg/issues/2300)
- Add interesting examples here

6. *Post* issue on the CodeMeta repository with the proposal to get feedback from the CodeMeta community and improve proposal and fix proposal submission date on schema.org: [https://github.com/codemeta/codemeta/issues/160](https://github.com/codemeta/codemeta/issues/160)
7. *Post* issue on schema.org with one or more labels:

  - [org vocab](https://github.com/schemaorg/schemaorg/labels/schema.org%20vocab)
  - [type:exact proposal](https://github.com/schemaorg/schemaorg/labels/type%3Aexact%20proposal)
  - [type:small proposal](https://github.com/schemaorg/schemaorg/labels/type%3Asmall%20proposal)
