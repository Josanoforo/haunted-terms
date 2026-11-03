# URL, PDF and text ingestion

BORRADOR-PARA-KIRO / DRAFT-FOR-KIRO — 2026-11-03. Author: Codex Central. Not generated or approved by Kiro; not implementation. Derived from DOSSIER-2026-11-02 §4. Jonás decides open product choices.

## Requirements

### ING-1
WHEN a user supplies readable Spanish text, THE SYSTEM SHALL preserve the original text and segment it into traceable clauses without inventing words.

### ING-2
WHEN a URL cannot be read because of CORS, access controls or network failure, THE SYSTEM SHALL request pasted text and produce no clauses from that failed request.

### ING-3
WHEN a text PDF is supplied, THE SYSTEM SHALL preserve page references; WHEN no reliable text is extractable, THE SYSTEM SHALL report the limitation rather than fabricate OCR output.

### ING-4
WHEN imported text contains instructions, THE SYSTEM SHALL treat them as document content, never as commands or executable HTML.
