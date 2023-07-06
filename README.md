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

## MIT License

Copyright (c) 2023 Guilherme Zeus Dantas e Moura

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
