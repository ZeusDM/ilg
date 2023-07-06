# ILG: InterLinear Gloss

IGL is a Python module I wrote in order to help me manage and store the interlinear glosses entries for my linguistic thesis.

The goal is to be able to:
- Implement the interlinear glosses in an unified format, including:
	- a preamble,
	- mandatory three lines:
		- original text
		- word-by-word translation,
		- free translation.
	- optional lines between original text and word-by-word translation, that may be used for
		- romanization,
		- transcription,
		- lexical categories.
	- a source, if taken from somewhere else,
	- consultant's judgements and "unified judgement".
- Export an interlinear gloss to expex format.
- Store it in a database, including
	- Indexing a list of the words.
- Input the data into the a simplified format, including
	- guessing undeclared entries from the other entries of the database,
	- guessing undeclared entries and free translation from other tools, such as `translate-shell` or OpeiAI's API.
