# AI-powered-social-media-content-machine-n8n-automation
Built a fully automated AI content pipeline for a beauty brand that transforms a single image into a complete, publish-ready social media package across Instagram, TikTok, Facebook, Pinterest, and YouTube Shorts — triggered automatically every 12 hours with zero manual input.

The system uses computer vision to analyze each image, then generates platform-specific captions, viral dialogue scripts with cinematic performance directions, 63 categorized hashtags, and YouTube metadata — all in one workflow run. A custom JavaScript quality gate scores every output, enforces a locked brand CTA on every run, and logs all results to Google Sheets for review.

Key challenge solved: the client needed a consistent brand voice and a specific closing line on every piece of content. I built a two-layer enforcement system — the AI prompt teaches the pattern, and a JS fallback regex corrects it automatically if the model deviates — guaranteeing zero brand drift across hundreds of runs.
