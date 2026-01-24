# Project Overview: ZAI

ZAI serves as a blueprint for high-quality AI chat applications. It bridges the gap between raw API capabilities and a polished user-facing product.

## Key Objectives
1. **Performance**: Achieve sub-100ms time-to-first-token.
2. **Reliability**: Ensure 100% uptime for chat persistence using MongoDB.
3. **Design**: Implement a sleek, distraction-free UI using the latest CSS standards.

## Technical Decisions
- **NestJS**: Chosen for its robust dependency injection and modularity, making the AI integration points easy to test and maintain.
- **Next.js**: Selected for its excellent SSR/Static generation capabilities and seamless React 19 support.
- **Mongoose**: Provided the necessary abstraction over MongoDB for consistent data modeling.
