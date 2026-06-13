# SoundHound

SoundHound AI is a voice AI and audio intelligence platform. This repository contains an APIs.json 0.19 profile cataloging SoundHound's public developer APIs, including the Houndify conversational voice assistant API and the Music Fingerprint Identification API.

## APIs

### Houndify Voice AI API

The Houndify platform provides HTTP and WebSocket APIs that accept text or audio queries and return structured JSON responses. It is built on SoundHound's proprietary Speech-to-Meaning and Deep Meaning Understanding technologies and supports:

- Voice queries (audio input via streaming or batch)
- Text queries (natural language text input)
- Conversation state management across multi-turn dialogues
- Real-time partial transcripts
- 100+ languages with edge and cloud deployment options
- SDKs for Android, iOS, JavaScript, React Native, Java, Go, C++, C#, and Python

**Developer signup:** https://www.houndify.com/signup  
**Documentation:** https://www.soundhound.com/voice-ai-products/developer/  
**GitHub SDKs:** https://github.com/soundhound  
**Terms of Service:** https://www.houndify.com/terms

### SoundHound Music Fingerprint Identification API

A high-accuracy music recognition API capable of identifying music from as little as 2 to 10 seconds of audio with sub-second latency. Designed for enterprise integration.

**Contact:** https://www.soundhound.com/contact/

## Authentication

Houndify uses a Client ID and Client Key authentication model. Credentials are obtained by registering an application at https://www.houndify.com and can be passed via environment variables (`HOUNDIFY_CLIENT_ID`, `HOUNDIFY_CLIENT_KEY`) or configured directly in SDK clients.

## Repository Structure

```
apis.yml                          # APIs.json 0.19 root manifest
plans/
  houndify-voice-ai.yml           # Houndify Voice AI pricing plans
  music-id.yml                    # Music ID API pricing plans
rate-limits/
  houndify-voice-ai.yml           # Houndify Voice AI rate limit policies
  music-id.yml                    # Music ID API rate limit policies
finops/
  soundhound.yml                  # FinOps guidance for cost management
```

## Links

- Website: https://www.soundhound.com
- Developer Platform: https://www.soundhound.com/voice-ai-products/developer/
- Blog: https://www.soundhound.com/voice-ai-resources/
- Newsroom: https://www.soundhound.com/newsroom/press-releases/
- GitHub: https://github.com/soundhound
- Investor Relations: https://investors.soundhound.com/news-releases
