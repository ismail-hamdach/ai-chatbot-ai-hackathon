# ContenGenie

ContenGenie is an AI-powered content generation tool designed to help African businesses create engaging, personalized, and culturally relevant content efficiently. The platform leverages advanced AI models to generate text, images, and videos, providing a comprehensive solution for content creation.

<p align="center">
  <img src="https://github.com/ismail-hamdach/ai-chatbot-ai-hackathon/blob/main/public/apple-touch-icon.png" width="350" title="hover text">
  <img src="https://github.com/ismail-hamdach/ai-chatbot-ai-hackathon/blob/main/public/apple-touch-icon.png" width="350" alt="accessibility text">
</p>

## Project Overview

### Problem Statement
Businesses in Africa often struggle to create content that resonates with their target audience, leading to reduced customer engagement and limited reach. Traditional content creation methods are time-consuming and may lack cultural relevance.

### Solution
ContenGenie addresses this problem by using state-of-the-art AI technologies to generate high-quality, personalized content. The platform supports multilingual content creation, ensuring cultural sensitivity and relevance. Users can generate social media posts, blog articles, marketing copy, custom images, and videos, all tailored to their brand and audience.

## Technical Stack

### Programming Languages
- **JavaScript**: For front-end development using React.
- **Python**: For backend services, handling AI models, and APIs.

### AI Models
- **Gemini LLMs**: For advanced internet search capabilities.
- **Preplexity**: For text analysis and content generation.
- **DALL-E 3**: For generating custom images.
- **Llama**: For video generation.

### Front-End Frameworks/Libraries
- **React**: For building the user interface.

### Back-End Frameworks/Libraries
- **Node.js**: For backend server-side logic.
- **Express.js**: For routing and middleware in Node.js.
- **Flask**: For managing AI model APIs and interactions in Python.

### Tools
- **Git**: For version control.
- **Jupyter Notebook**: For developing and testing AI models.
- **PostgreSQL**: For database management.
- **Docker**: For containerization.
- **Kubernetes**: For container orchestration.
- **Azure/GCP**: For cloud computing and deployment services.
- **Terraform**: For infrastructure as code.
- **CI/CD Pipelines**: For continuous integration and deployment.

## Features

- **Content Generation**: Create high-quality social media posts, blog articles, and marketing copy.
- **Multilingual Support**: Generate content in multiple languages and dialects.
- **Cultural Sensitivity**: Ensure content is culturally relevant and resonates with local audiences.
- **Content Customization**: Advanced customization options for brand-specific content.
- **Analytics and Reporting**: Detailed analytics on content performance and optimization recommendations.
- **Content Library**: Pre-generated templates and content ideas.

## How It Works

1. **User Interaction**: Users interact with the React-based frontend to access features and input preferences.
2. **Backend Processing**: Node.js server handles requests and communicates with Python backend services.
3. **Content Generation**:
   - Gemini LLMs for internet search.
   - Preplexity for text analysis and generation.
   - DALL-E 3 for image generation.
   - Llama for video generation.
4. **Output Delivery**: Generated content is sent back to the React frontend for user review and finalization.
5. **Analytics and Reporting**: Advanced analytics on user interactions and content performance.

## Getting Started

### Prerequisites

- Node.js
- Python
- Docker
- PostgreSQL
- Azure/GCP account for cloud services


## Running locally

You will need to use the environment variables [defined in `.env.example`](.env.example) to run Next.js AI Chatbot. It's recommended you use [Vercel Environment Variables](https://vercel.com/docs/projects/environment-variables) for this, but a `.env` file is all that is necessary.

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control access to your various OpenAI and authentication provider accounts.

1. Install Vercel CLI: `npm i -g vercel`
2. Link local instance with Vercel and GitHub accounts (creates `.vercel` directory): `vercel link`
3. Download your environment variables: `vercel env pull`

```bash
pnpm install
pnpm dev
```

Your app template should now be running on [localhost:3000](http://localhost:3000/).

## Authors

This library is created by [Vercel](https://vercel.com) and [Next.js](https://nextjs.org) team members, with contributions from:

- Jared Palmer ([@jaredpalmer](https://twitter.com/jaredpalmer)) - [Vercel](https://vercel.com)
- Shu Ding ([@shuding\_](https://twitter.com/shuding_)) - [Vercel](https://vercel.com)
- shadcn ([@shadcn](https://twitter.com/shadcn)) - [Vercel](https://vercel.com)
