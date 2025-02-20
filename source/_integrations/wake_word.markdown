---
title: Wake-word-detection
description: Detect a wake word in streaming audio.
ha_category:
  - Voice
ha_release: '2023.9'
ha_codeowners:
  - '@balloob'
  - '@synesthesiam'
ha_domain: wake_word
ha_integration_type: entity
---

A wake-word-detection entity allows other integrations or applications to detect wake words in streaming audio.

The wake-word-detection entities cannot be implemented manually, but can be provided by integrations such as [Wyoming](/integrations/wyoming). The API in [Assist Pipelines](https://developers.home-assistant.io/docs/voice/pipelines/) enables wake-word-detection as part of [Assist](/voice_control/).



{% include integrations/building_block_integration.md %}
