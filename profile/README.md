<h1 align="center">
  <a href="https://oatschema.org"><img src="https://oatschema.org/_static/img/oats-mark.svg" alt="" height="32" align="top"></a>
  OATS: Open Annotation Task Schemas
</h1>

Strict, versioned JSON Schemas for model outputs and annotation tasks, with validators for Python and JavaScript and the schemas bundled for Rust.

A record says which task it answers (transcription, classification, document extraction, …) and which schema version it follows. Any tool can then check it, store it and read it, whatever model or person produced it. A released version's schemas never change.

**Schemas:** `audio-transcription`, `classification`, `document-extraction`, `embedding`, `entity-extraction`, `generic`, `geolocation`, `llm-output`, `object-detection`, `ranking`, `regression`, `temporal-segmentation`. Browse them, read the docs, or validate a record in your browser at [oatschema.org](https://oatschema.org).

| Repo | Package | |
|---|---|---|
| [`oats`](https://github.com/oatschema/oats) | | The schemas, examples and changelog |
| [`oatschema-py`](https://github.com/oatschema/oatschema-py) | `pip install 'oatschema[validate]'` | Python: bundled schemas and a validator |
| [`oatschema-js`](https://github.com/oatschema/oatschema-js) | `npm install oatschema` | JavaScript and TypeScript: precompiled validators, browser-safe |
| [`oatschema-rs`](https://github.com/oatschema/oatschema-rs) | `cargo add oatschema` | Rust: bundled schemas |
| [`oatschema-adapters-py`](https://github.com/oatschema/oatschema-adapters-py) | `pip install oatschema-adapters` | Convert records to and from formats such as SRT, WebVTT, TSV, hOCR, HTML and Markdown |

Everything is Apache-2.0. Contributions are welcome under the DCO: see each repo's `CONTRIBUTING.md`.
