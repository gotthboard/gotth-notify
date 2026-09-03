# gotth-notify

Reserved for reusable notification delivery mechanics shared by GOTTH
applications.

## Intended boundary

This project may eventually own channel-neutral delivery envelopes,
idempotency keys, retry classification, bounded backoff, provider adapters,
delivery receipts, and failure-safe redaction. Consumers retain subscription
policy, recipient authorization, message meaning, template content, digest
scheduling, and the decision to disclose an event.

The first real consumer is expected to come from GOTTH Board's version 2
notification/digest work. Email verification performed by Authentik is not
part of this project.

## Non-goals

- User preferences, forum watches, mentions, or access policy.
- An SMTP server, marketing platform, or general job queue.
- Sending anything merely because an application emitted an event.

## Status

Placeholder only. There is no implementation, API, release, tag, compatibility
promise, or dependency to pin.
