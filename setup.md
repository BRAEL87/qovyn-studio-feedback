# Qovyn Studio Setup Guide

## 1. Download & Install

1. Go to [https://qovyn-studio.vercel.app/](https://qovyn-studio.vercel.app/) and download the setup.
2. Run the installer and follow the installation steps.
3. Approve any security prompts during installation.

---

## 2. Configure AI Providers

1. Launch Qovyn Studio.
2. Click the **Settings** button in the bottom-left corner.
3. Navigate to the **AI Providers** tab.
4. Each provider has a **"Get key"** link to obtain an API key.
5. Add a model ID for each provider to enable model selection.

### Recommended Providers

| Provider | Description |
|----------|-------------|
| Puter JS | Free tier, fast setup |
| Qovyn Router (OpenRouter) | Multiple models via one API |
| Open Code Zen | Code-optimized models |
| Z AI | General purpose AI |
| NVIDIA NIM | NVIDIA-hosted models |
| Mistral | Open-weight models |

---

## 3. Quick Setup: Get a Puter API Key

1. Sign in at [https://puter.com/](https://puter.com/).
2. Navigate to your dashboard — either:
   - Click **Account** → **Settings**, or
   - Open [https://puter.com/dashboard](https://puter.com/dashboard) in a new tab.
3. In the dashboard, click **Account** in the sidebar.
4. Click **Create Token**.
5. Give the token a name and click **Create Token**.
6. Copy the generated token.
7. In Qovyn Studio, paste it into the Puter provider's **API Key** field.
8. Click **Save** and **Verify Token**.
9. Once verified, Puter models will appear in the AI panel model selector.

You can now use any model from the configured provider in the AI panel.

---

## 4. Login for Full Features

For better agent performance (web searches, advanced tools, etc.), log in to the app:

1. Click the **user icon** in the top-right corner to open the login modal.
2. Click **Continue to Web Login**.
3. On the web login page, sign in with your **Google** or **GitHub** account.
4. You will be taken to your dashboard.
5. Click **Launch Qovyn** — the app will log you in automatically.

### If Login Fails

1. Scroll to the bottom of the dashboard page.
2. Click **Copy Session Token**.
3. In the app's login modal, click **"Problem with redirect? Enter manual token"**.
4. Paste the token and click to log in.

---

## 5. Usage & Limits

- **Free tier:** Up to **15 requests per day**.
  - A single request can generate a complete app, website, or project.
- **Unlimited plan:** Upgrade for **$6 / 3500 FCFA per month** via the website's pricing section.

Once logged in and configured, you're ready to start coding.
