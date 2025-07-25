# Weights API Examples

This directory contains comprehensive user journey guides for the Weights API, demonstrating how to use each major feature of the platform.

## Available Examples

### 1. [Image Generation Journey](./image-generation.mdx)
Learn how to create stunning AI-generated images from text prompts. This guide covers:
- Setting up the Weights SDK
- Creating image generation jobs
- Monitoring job status and retrieving results
- Using custom LoRA models for specific styles
- Best practices for writing effective prompts
- Complete working examples

### 2. [Video Generation Journey](./video-generation.mdx)
Transform static images into dynamic video content. This guide covers:
- Preparing input images for video generation
- Creating video generation jobs with motion prompts
- Monitoring video processing (longer than image generation)
- Different types of motion effects
- Best practices for motion prompts and image selection
- Complete working examples

### 3. [LoRA Model Training Journey](./lora-training.mdx)
Train custom AI models on your own images for consistent styles. This guide covers:
- Preparing training images (5-30 images required)
- Creating and monitoring LoRA training jobs
- Using trained models in image generation
- Searching and using public models
- Best practices for image selection and training
- Complete end-to-end examples

### 4. [RVC Voice Models & Covers Journey](./rvc-voice.mdx)
Create AI voice models and generate voice covers. This guide covers:
- Preparing training audio files (1-50 files, 10+ seconds each)
- Training custom RVC voice models
- Creating voice covers with trained or public models
- Advanced features like pitch shifting and vocal isolation
- Best practices for audio quality and model training
- Complete working examples

### 5. [Song Generation Journey](./song-generation.mdx)
Transform lyrics into complete musical compositions. This guide covers:
- Writing effective lyrics (up to 380 characters)
- Creating songs with different section types (verse, chorus, guitar-stabs, all)
- Monitoring song generation progress
- Best practices for lyrical content and musical style
- Complete working examples

## How These Examples Work Together

These examples are designed to work together to create complete multimedia projects:

1. **Start with Image Generation** - Create visual content for your project
2. **Add Video Generation** - Animate your images for dynamic content
3. **Train LoRA Models** - Create consistent styles for your visual content
4. **Generate Songs** - Create original music for your content
5. **Add Voice Covers** - Apply custom voices to your music or create voiceovers

## Common Workflows

### Content Creator Workflow
1. Generate images for social media posts
2. Animate images for video content
3. Create background music for videos
4. Add voiceovers using RVC models

### Musician Workflow
1. Generate song melodies from lyrics
2. Create album artwork using image generation
3. Train voice models for unique vocal styles
4. Create music videos with video generation

### Developer Workflow
1. Train custom LoRA models for consistent branding
2. Generate images for app interfaces
3. Create voice models for app voiceovers
4. Generate background music for apps

## Getting Started

1. **Install the SDK**: `npm install @weights-ai/sdk`
2. **Get an API Key**: Sign up at [weights.com](https://www.weights.com/weights-api)
3. **Choose Your Journey**: Start with the example that matches your needs
4. **Follow the Steps**: Each guide provides step-by-step instructions
5. **Experiment**: Combine different features for unique results

## Prerequisites

- Weights API account with API key
- Basic knowledge of JavaScript/Node.js
- For LoRA training: 5-30 high-quality images
- For RVC training: 1-50 audio files (10+ seconds each)
- For covers: Audio files uploaded to web-accessible URLs

## Support

- **Documentation**: [docs.weights.com](https://docs.weights.com)
- **API Reference**: See the API Reference section in the docs
- **Support**: [support@weights.com](mailto:support@weights.com)
- **GitHub**: [github.com/weights-ai](https://github.com/weights-ai)

## Next Steps

After completing these examples, explore:
- Advanced API features and parameters
- Integration with other tools and platforms
- Building complete applications with the Weights API
- Contributing to the community and sharing your models 