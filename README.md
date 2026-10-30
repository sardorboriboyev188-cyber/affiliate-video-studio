Build a complete, production-ready AI marketing agent
application called NOVA AGENT.

IMPORTANT:
Do not create just a landing page or static UI.
Build a functional full-stack application with a real
backend, database, authentication, AI agent architecture,
connector integrations, and Android APK support.

==================================================
1. DESIGN AND USER INTERFACE
==================================================

Create a premium, modern AI application inspired by
Claude's clean interface.

Design:
- Main background: deep black (#080D17).
- Primary color: soft light blue (#69BDFF).
- Secondary accent: elegant violet (#A78BFA).
- Modern rounded cards.
- Smooth animations.
- Responsive mobile-first interface.
- Professional dark theme.
- Excellent Android mobile experience.

Application name: NOVA AGENT.

Main navigation:
1. Dashboard
2. AI Agent
3. Connectors
4. Content Studio
5. Marketing Strategy
6. Analytics
7. Shopify Manager
8. Automation
9. Settings

==================================================
2. AI AGENT
==================================================

Build an intelligent AI agent that can understand
natural language instructions.

The agent must:
- Understand complex tasks.
- Create multi-step plans.
- Execute approved actions.
- Use connected services.
- Report its progress.
- Detect errors.
- Explain errors and suggest solutions.
- Retry failed tasks safely.
- Maintain task history.
- Ask the user when permissions are needed.

Provide a Claude-like chat interface.

The agent must not pretend a task succeeded
unless the connected service confirms success.

==================================================
3. CONNECTORS
==================================================

Create a dedicated Connectors page.

Required connectors:

A. SHOPIFY
- OAuth connection.
- Read products.
- Analyze product information.
- Read orders and sales statistics.
- Manage product descriptions with permission.
- Monitor order notifications.
- Track product performance.

B. INSTAGRAM
- Official Meta OAuth integration.
- Connect professional Instagram accounts.
- Read available account insights.
- Prepare Instagram Reels.
- Prepare captions and hashtags.
- Publish approved content using supported APIs.
- Track available engagement statistics.

C. YOUTUBE
- Google OAuth.
- Connect YouTube channel.
- Upload approved videos.
- Publish Shorts-compatible videos.
- Prepare titles and descriptions.
- Read available analytics.

D. CHROME / BROWSER
- Browser automation using Playwright.
- Open websites.
- Navigate pages.
- Extract permitted public product information.
- Fill forms when authorized.
- Detect errors.
- Ask the user before sensitive actions.

E. GITHUB
- GitHub OAuth.
- Connect repositories.
- Read project files.
- Create and edit code.
- Create branches and commits.
- Manage project changes with permission.

Every connector must have:
- Connect button.
- Connected status.
- Disconnect button.
- Permission management.
- Error messages.
- Secure OAuth authentication.

Never store user passwords directly.

==================================================
4. AUTONOMOUS SHOPIFY MARKETING AGENT
==================================================

This is one of the most important features.

The user can tell the agent:

"Start marketing my Shopify products."

The agent should:

1. Analyze available Shopify products.
2. Identify products with promising demand.
3. Compare product popularity and available data.
4. Evaluate product usefulness and target audience.
5. Select suitable products for promotion.
6. Explain why each product was selected.

Never invent sales, demand, popularity, or profit data.

==================================================
5. INTELLIGENT CONTENT STRATEGY
==================================================

The agent must independently select a content niche
that matches the selected product.

Example:

If the product is a car accessory, select a useful
automotive education and tips niche.

Create content that:
- Educates viewers.
- Solves real problems.
- Provides useful information.
- Naturally introduces relevant products.
- Avoids misleading advertising.

Analyze available audience insights and previous
content performance.

Create a weekly content calendar.

==================================================
6. AI VIDEO GENERATION
==================================================

Create a Video Studio.

The agent should:
- Generate video ideas.
- Write scripts.
- Create video generation prompts.
- Generate captions.
- Generate subtitles.
- Prepare vertical 9:16 videos.
- Prepare Instagram Reels.
- Prepare YouTube Shorts.

Use a configurable video generation provider API.

Do not pretend video generation is available
when no provider is connected.

Allow the user to preview and edit videos.

==================================================
7. INTELLIGENT POSTING SCHEDULE
==================================================

Analyze available audience activity data.

Estimate suitable publishing times based on:
- Audience activity.
- Previous video performance.
- Engagement.
- Platform analytics.

Schedule posts for suitable times.

Do not promise viral results.

The initial growth target can be 10,000 followers
within seven days, but clearly explain that this
is a target, not a guaranteed result.

Never use fake followers, spam, bots, or artificial
engagement.

==================================================
8. CONTENT APPROVAL SYSTEM
==================================================

Before publishing any new video:

Show:
- Video preview.
- Selected platform.
- Caption.
- Hashtags.
- Product link.
- Planned publishing time.

Provide buttons:

APPROVE AND PUBLISH
EDIT VIDEO
REJECT

Default behavior:
The agent MUST wait for user approval.

Allow the user to enable automatic publishing
for future posts after explicitly granting permission.

Never publish rejected content.

==================================================
9. ANALYTICS DASHBOARD
==================================================

Display real available statistics:

- Instagram followers.
- YouTube subscribers.
- Video views.
- Engagement.
- Link clicks.
- Product conversions.
- Shopify orders.
- Pending commissions.
- Approved commissions.
- Rejected commissions.
- Actual payouts.

Never fabricate earnings or sales.

Separate estimated revenue from verified revenue.

==================================================
10. NOTIFICATIONS
==================================================

Create an in-app notification center.

Notify the user about:
- New Shopify orders.
- Successful payments.
- Failed tasks.
- Video generation completion.
- Content awaiting approval.
- Published posts.
- Connector errors.
- Important marketing results.

Use Shopify webhooks where available.

Support push notifications when configured.

==================================================
11. AUTOMATION ENGINE
==================================================

Create an automation system.

Example workflow:

Shopify product analysis
       ↓
Product selection
       ↓
Audience research
       ↓
Content niche selection
       ↓
Video script generation
       ↓
Video generation
       ↓
User approval
       ↓
Publishing schedule
       ↓
Instagram / YouTube publishing
       ↓
Analytics monitoring
       ↓
Strategy improvement

Allow users to pause, resume, and stop automations.

==================================================
12. SECURITY
==================================================

Implement:
- Secure authentication.
- Encrypted secret storage.
- OAuth token management.
- Server-side API calls.
- Role-based permissions.
- Secure database access.
- Input validation.
- Rate limiting.
- Audit logs.

Never expose API keys in frontend code.

Never request Shopify or social media passwords.

Require explicit approval before:
- Publishing content by default.
- Spending advertising money.
- Changing payment settings.
- Making purchases.
- Performing irreversible actions.

==================================================
13. TECHNICAL ARCHITECTURE
==================================================

Build using a suitable modern stack.

Suggested:
- Frontend: React + TypeScript.
- Backend: Node.js.
- Database: PostgreSQL.
- Authentication: secure session/OAuth.
- AI: configurable LLM provider.
- Browser automation: Playwright.
- Video generation: provider adapter.
- Background jobs: queue system.
- Mobile: Capacitor Android.

Use environment variables for API credentials.

Create:
- README.md
- .env.example
- Database schema.
- API documentation.
- Installation instructions.
- Android build instructions.
- GitHub repository structure.

==================================================
14. ANDROID APK
==================================================

The application must be mobile-first.

Configure Capacitor so the project can be built
as an Android application.

Provide:
- Android project files.
- App icon placeholder.
- Splash screen.
- Responsive layouts.
- Android build instructions.
- Debug APK build steps.

==================================================
15. FINAL REQUIREMENTS
==================================================

Do not build a fake demonstration of integrations.

If an API requires credentials, create the real
integration structure and clearly explain which
credentials are needed.

Build the application in stages.

First complete the core application.
Then implement connectors.
Then implement the autonomous agent.
Then implement marketing automation.
Finally prepare the Android build.

Create a clean GitHub-ready project.

Do not claim features are functional until they
have been tested successfully.# affiliate-video-studio