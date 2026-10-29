# Let's Learn

My notes on data engineering, cloud and system design: concepts explained simply, with diagrams.

## System design
- [How a video gets millions of likes: the mechanism](system-design/how-like-counts-work.md): like records vs counters, event logs, batching, sharded counters, caching and reconciliation
  - ▶️ [Simulation video](system-design/likes-simulation/likes-simulation.mp4) and [interactive simulator](system-design/likes-simulation/index.html): watch a single counter row become a hot key at 10,000 likes/s, and the sharded design handle 50,000/s
- [How ticket sites stop two people booking the same seat](system-design/how-seat-booking-works.md): race conditions, conditional updates, row locks, constraints, seat holds and waiting rooms

## Visual notes
- [AWS services](AWS%20services.gif)
- [Delta tables](Delta%20Tables.png)
