# chad

An open-source, privacy-first chat platform inspired by modern messaging apps.

## Core goals

- End-to-end encrypted 1:1 and group messaging
- Status updates (text/media with optional expiry)
- User-created groups called **Circles**
- Open APIs and self-hostable architecture

## MVP feature scope

1. **Accounts & Identity**
   - Username-based identity
   - Device/session management

2. **Encrypted Chat**
   - E2EE direct messaging
   - E2EE Circle messaging
   - Delivery/read receipts metadata controls

3. **Status**
   - Post status updates
   - View contacts' statuses
   - Expiring status lifecycle

4. **Circles (Groups)**
   - Create/manage circles
   - Member roles (owner/admin/member)
   - Invite and remove members

## Non-functional requirements

- Security-first defaults and encrypted transport
- Scalable service boundaries for chat, status, and presence
- Auditable open-source codebase and protocols