# SuperLiveTimer Web Flasher

Flash SuperLiveTimer firmware onto NHSCC timing devices straight from the browser:

**https://nhsccpgh.github.io/slt-flasher/**

Needs Chrome or Edge on a computer. Supports the handheld receivers (Heltec WiFi LoRa 32 V3, Vision Master T190, Wireless Paper, ThinkNode M2), the sender and the base receiver, and can restore a Heltec board's LoRa license after a flash erase.

This repo only holds the published page and firmware images. They're built from the SuperLiveTimer source repo with `make firmware` and published here with `make publish-flasher` — don't edit files here directly.
