<a href="https://qrGPT.io">
  <img alt="QrGPT – Generate beautiful AI QR Codes in seconds." src="/public/og-image.png">
  <h1 align="center">qrGPT</h1>
</a>
<p align="center">
  Generate beautiful AI QR Codes in seconds. Built with modern web technologies and AI.
</p>
<p align="center">
  <a href="#about"><strong>About</strong></a> ·
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#deployment"><strong>Deployment</strong></a> ·
  <a href="#setup"><strong>Setup</strong></a> ·
  <a href="#acknowledgments"><strong>Acknowledgments</strong></a>
</p>
<br/>

## About

qrGPT is an innovative web application that transforms ordinary QR codes into visually stunning, AI-generated artworks. This project demonstrates the power of combining traditional QR code functionality with cutting-edge artificial intelligence to create codes that are not only functional but also aesthetically pleasing.

The application leverages advanced AI models to generate unique, artistic QR codes while maintaining their scannability and functionality. Users can input any URL or text content and receive a beautifully designed QR code that stands out from conventional black-and-white patterns.

## Features

- **AI-Powered Generation**: Creates artistic QR codes using advanced machine learning models
- **Instant Results**: Generate beautiful QR codes in seconds
- **Fully Functional**: All generated codes maintain perfect scannability
- **Modern UI**: Clean, intuitive interface built with contemporary design principles
- **High Performance**: Optimized for speed and reliability
- **Scalable Architecture**: Built to handle high traffic and concurrent users

## Tech Stack

- **Next.js** [App Router](https://nextjs.org/docs/app) - React framework for production-grade applications
- **Replicate** - AI model hosting and inference platform
- **Vercel Blob** - Scalable image storage solution
- **Vercel KV** - Redis-compatible database for caching and rate limiting
- **Shadcn UI** - Modern, accessible component library
- **TypeScript** - Type-safe development experience

## Deployment

This application is deployed using Vercel's edge network for optimal performance and global accessibility. The deployment showcases modern web development practices including:

- Edge computing for reduced latency
- Automatic scaling based on demand
- CDN integration for fast asset delivery
- Environment-based configuration management

You can deploy your own instance using the button below:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.fyi/qrGPT)

## Setup

To run this project locally or deploy your own instance, you'll need to configure:

1. **Replicate Account**: Set up API access for AI model inference
2. **Vercel KV**: Configure Redis storage for session management and rate limiting
3. **Vercel Blob**: Set up scalable image storage for generated QR codes
4. **Environment Variables**: Configure all necessary API keys and connection strings

## Acknowledgments

This project builds upon excellent foundational work and leverages powerful tools:

- **Development Tools**: [Codeium](https://codeium.com) and [v0](https://v0.dev/) for enhanced development workflow
- **Code Patterns**: [Spirals](https://spirals.vercel.app/) for architectural guidance and best practices
- **AI Model**: [Lim Zi Yang](https://github.com/ZYLIM0702) for the core AI model implementation
- **Original Implementation**: Hassan El Mghari ([@nutlope](https://twitter.com/nutlope)) and Kevin Hou ([@kevinhou22](https://twitter.com/kevinhou22)) for the foundational codebase

---

*This project demonstrates the intersection of traditional web technologies with modern AI capabilities, showcasing how artificial intelligence can enhance everyday digital tools.*
