# Google Gmail API

The Gmail API lets you view and manage Gmail mailbox data like threads, messages, and labels. It provides RESTful access to Gmail mailboxes, supporting message sending, drafting, organizing with labels, managing settings, and push notifications for mailbox changes. The API uses OAuth 2.0 for authorization and supports both user and service account authentication for Google Workspace domains.

## Base URL

```
https://gmail.googleapis.com
```

## Resources

The Gmail API v1 provides the following resources:

- **Messages** - Read, send, modify, trash, untrash, and delete email messages
- **Threads** - View and manage conversation threads
- **Labels** - Create, update, and delete labels for organizing messages
- **Drafts** - Create, update, send, and delete email drafts
- **History** - Track changes to the mailbox over time
- **Settings** - Manage auto-forwarding, IMAP, POP, filters, delegates, and send-as aliases
- **Attachments** - Retrieve message attachments

## Artifacts

| Artifact | Path |
|----------|------|
| APIs.yml | [apis.yml](apis.yml) |
| OpenAPI 3.1.0 | [openapi/openapi.yml](openapi/openapi.yml) |
| JSON Schema (Draft 2020-12) | [json-schema/json-schema.yml](json-schema/json-schema.yml) |
| JSON-LD Context | [json-ld/json-ld.jsonld](json-ld/json-ld.jsonld) |

## Documentation

- [Gmail API Guide](https://developers.google.com/workspace/gmail/api/guides)
- [REST API Reference](https://developers.google.com/workspace/gmail/api/reference/rest)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
