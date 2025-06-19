<div align="center">
  <img src="https://storage.googleapis.com/hume-public-logos/hume/hume-banner.png">
  <h1>Emotion-Aware Product Review System (with Hume EVI + LLaMA 3)</h1>
</div>

![preview.png](preview.png)

## Overview

This project is a full-stack, real-time feedback system that leverages advanced AI to extract emotional insights from user reviews. Originally developed at Cal Hacks, it represents a next-generation interface for understanding user sentiment beyond surface-level feedback.

It integrates:

- [Hume's Empathic Voice Interface (EVI)](https://hume.docs.buildwithfern.com/docs/empathic-voice-interface-evi/overview) for multi-modal emotional sentiment analysis
- A responsive chat interface built with Next.js (App Router) and React
- Real-time data streaming with Apache Kafka and WebSockets
- Domain-specific fine-tuned LLaMA 3.1–8B model using LoRA for nuanced language interpretation

## Key Features

- Real-time emotional enrichment of user reviews using Hume EVI
- Live feedback pipeline with Kafka and WebSocket for sub-500ms latency
- Contextual interpretation of user input using fine-tuned LLaMA 3.1–8B
- Secure Kafka message consumption over SSH
- Clean and responsive front-end with dynamic UI updates

## Technologies Used

- **Frontend**: Next.js 14 (App Router), React, Tailwind CSS
- **Backend**: Kafka, Node.js, LLaMA 3.1 (LoRA), SSH
- **AI/ML**: Hume EVI API (real-time emotional analysis), OpenAI (optional)
- **Security**: SSH encryption, OAuth (optional)
- **Deployment**: Vercel

## Project Deployment

Click the button below to deploy this project using Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fhumeai%2Fhume-evi-next-js-starter&env=HUME_API_KEY,HUME_CLIENT_SECRET)

### Deployment Instructions

1. Clone or fork this repository.
2. Deploy via the Vercel button above or manually configure deployment on [vercel.com](https://vercel.com).
3. Set your environment variables: `HUME_API_KEY` and `HUME_CLIENT_SECRET`. You can find these on the [Hume Developer Portal](https://beta.hume.ai/settings/keys).
4. The application will be automatically deployed and ready to use.

## Acknowledgments

- Hume AI for the Empathic Voice Interface and SDK
- Meta for providing open access to LLaMA 3 model weights
- Cal Hacks for supporting this initiative

---

> This system introduces emotional intelligence into product review workflows, enabling a deeper understanding of user experience and sentiment.
