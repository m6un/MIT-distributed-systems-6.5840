# Lecture 1

## Intro

- Examples we'll be going through - P2P file sharing, storage for large websites etc.
- If you can solve your problem in a single computer -- that's the best way.
- Reasons:

  - Parallelism - Performance
  - Fault tolerance
  - physical reasons - systems where individual elements are physically distributed.
  - Security - to achieve this isolate the individual components.
- Things that make DS hard:

  - Concurrent programming
  - Multiple pieces plus a network. The network is also a component.
  - Partial failures

## Infrastructure

- Storage systems
- Communication systems
- Computation systems

Abstractions over this infrastructure ( implementations ):

1. RPC - Remote Procedure calls - Whose goal is to mask the fact that we're communicating through an unreliable network
2. Threads - A programming network that allows us to harness multple comps. Threads are a way to structure concurrent operations in a way that simplifies the programmer's view of those operations.
3. Concurrency controls ( Locks )

## Performance

- Goal of a ds - scalable speedup - If the problem you're trying to solve a problem with one computer, getting 2 helps solve it in half time.

## Fault tolerance

1. Availability
2. Recoverability
3. Non-volatile storage
4. Replication
