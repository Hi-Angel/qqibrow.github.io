---
layout: post
title: Record Replay Live Stream
---
Recording live steam data is useful from several aspects:

1. Debug exceptions when using external api. Most of the time we redo the same call several times to debug. Instead, u could record once and analysis the underlying data.

2. Build an end-to-end test block. Every time the same dataset is playing, the underlying result should also be consistent. This test block will be very helpful within the continuous delivery system.

3. Performance testing. Replaying data way fast than in production and test what the limitation of your system