# Doctronic

The Doctronic API lets your backend run clinical conversations, book care, and retrieve
consultation documents. Your backend identifies the patient and calls Doctronic. Doctronic runs the
clinical conversation and streams typed events that tell your product what to display.

Start with the [docs](https://docs.doctronic.ai) and the
[quickstart](https://docs.doctronic.ai/docs/quickstart/).

## SDKs

Both SDKs are MIT-licensed and run on your server only. They read the API token Doctronic
provisions from `DOCTRONIC_API_TOKEN`.

| Language | Install | Package | Source |
| --- | --- | --- | --- |
| TypeScript (Node 20+) | `npm install @doctronic-ai/sdk` | [npm](https://www.npmjs.com/package/@doctronic-ai/sdk) | [doctronic-sdk-typescript](https://github.com/doctronic-ai/doctronic-sdk-typescript) |
| Python (3.10+) | `pip install doctronic` | [PyPI](https://pypi.org/project/doctronic/) | [doctronic-sdk-python](https://github.com/doctronic-ai/doctronic-sdk-python) |

To request a staging token, see [get access](https://docs.doctronic.ai/docs/authentication/#get-access).

## Security

Report a vulnerability privately from the **Security** tab of the affected repository. Don't open a
public issue, and don't include patient information or credentials in a report.
