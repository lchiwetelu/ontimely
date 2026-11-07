# Ontimely

Booking, Scheduling, events and video meetings for professionals

## How it's organized

- `api/` - Node (TypeScript). Everything people see: accounts, bookings, payments, emails.
- `engine/` - Go. Precise background work: the slot engine and calendar sync.
- `proto/` - The shared contract between Node and Go,
- `db/migrations/` - Database table changes, in order

## Current stage

 Stage 0: Foundations
