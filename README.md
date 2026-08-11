# Nuduo Proposals

Client proposal documents, archived by job code.

Each engagement lives under its own folder named with an obfuscated job
code (e.g. `NU-XXXXXX`) rather than the client's name, since this repo is
public. The mapping from job code to client is kept outside this repo.

## Structure

```
<JOB-CODE>/
  README.md           context for the engagement (scope, status, dates)
  proposal-*.html      self-contained proposal document(s)
```

Proposal HTML files are self-contained (fonts and images inlined as data
URIs) so each one can be opened directly in a browser with no build step
and no external dependencies.
