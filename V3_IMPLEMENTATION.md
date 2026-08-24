# MJ विकास V3 — AI Conversation Foundation

Added on top of V2:
- MJAIEngine provider abstraction
- Local RuleFallbackAI so conversation works without a network provider
- Conversation history buffer
- Async AI response path using Kotlin coroutines
- V3 UI label
- Secure-backend-ready architecture

Production online AI:
- Do NOT put an API key in the APK.
- Implement a server endpoint that authenticates the user/device and calls the chosen AI provider.
- Replace RuleFallbackAI with a network implementation.
- Add streaming responses and cancellation in the next integration pass.

V3 remains subject to real Android build/device testing.
