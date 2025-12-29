# EvalLearn

An AI-assisted learning and evaluation platform with human-in-the-loop feedback.

## Architecture
- **Frontend**: Next.js (App Router) with Tailwind CSS.
- **Backend**: NestJS (Fastify) with RESTful APIs.
- **Monorepo**: Separated into `/apps/web` and `/apps/api`.

## Design System
- **Visual Identity**: Cosmic neon educational interface.
- **Colors**: Neon Cyan, Neon Purple, Neon Yellow, Cosmic Dark.
- **Features**: Text glow, hover tilts, and neubrutal shadows.

## AI Integration
- Integrated with Google Gemini (simulated fallback included).
- Generates multiple response variants (Simple, Technical, Analogy) for each prompt.

## AI Alignment Features
- **Multi-Criteria Evaluation**: Score responses on Correctness, Relevance, Clarity, Safety, and Conciseness.
- **Preference Ranking**: Rank multiple AI responses to generate preference data.
- **Dataset Export**: Export SFT (Supervised Fine-Tuning) and RLHF (Reinforcement Learning from Human Feedback) datasets in JSON format.

## Workflow
1. **Learn**: Submit a concept to learn.
2. **Responses**: View multiple AI-generated explanations.
3. **Evaluate**: Score and provide rationale for responses (simulating RLHF).
4. **Metrics**: Analyze alignment and quality data.

## Setup
- Backend runs on port 3001.
- Frontend runs on port 3000.
