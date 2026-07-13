# AI Coloring Book & Image Generation Telegram Bot

A production-ready Telegram bot that allows users to generate custom artwork and transform real photos into coloring pages using generative AI models.

### 🚀 Key Features:
- **Text-to-Image Generation:** Users can type any prompt (e.g., "dragon in the forest") or choose from predefined theme buttons (Dinosaurs, Space, Unicorns, etc.).
- **Photo-to-Coloring Page (Image-to-Image):** Converts user-uploaded photos into clean line-art coloring pages.
- **Interactive UI:** Inline keyboard navigation for seamless user experience ("Try again", "Make a coloring page").
- **Target Audience:** Russian-speaking market.

### 🛠️ Technical Overview & Scaling Goals:
- **Current Stack:** Python / Telegram Bot API.
- **The Problem:** Processing complex image-to-image (coloring page) transformations requires high-performance GPUs, causing bottleneck issues during peak traffic.
- **The Solution:** Migrating the inference backend to **Beam Cloud** to utilize serverless GPU infrastructure, autoscaling, and low-latency webhooks.
