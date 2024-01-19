---
PromptInfo:
	id:brainstormChildren
	name: brainstorm ideas about children notes
	description:
	tags:
	version: 0.0.1
---
context:
{{#each children}}
{{this.content}}
{{/each}}

prompt:
brainstorm ideas about context
Ideas:
*
