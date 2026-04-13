# Gutenberg Starter Templates

Gutenberg single page templates, and blocks library to import into your website easily.

## External Services

This library connects to the following external services:

### Brainstorm Force Support Server

- **Service URL:** https://support.brainstormforce.com/
- **Purpose:** License activation, validation, and product update checks via the BSF API.
- **When data is sent:** When a user activates a license key or when the plugin checks for updates.
- **Data transmitted:** License key, product ID, site URL.
- **Privacy Policy:** https://developer.brainstormforce.com/privacy-policy/
- **Terms of Use:** https://developer.brainstormforce.com/terms-of-use/

### Website Demos

- **Service URL:** https://websitedemos.net/
- **Purpose:** Template library and AI content APIs. Provides the block patterns, page templates, wireframes, and site kits available for import.
- **When data is sent:** When browsing or importing templates, and when using AI content generation features.
- **Data transmitted:** Template/block identifiers, site configuration, AI content prompts.

### ZipWP API

- **Service URL:** https://api.zipwp.com/
- **Purpose:** Business category search and language data for AI-powered features.
- **When data is sent:** When using AI features that require business category or language data.
- **Data transmitted:** Search queries, language preferences.
- **Privacy Policy:** https://zipwp.com/privacy-policy/

### ZipWP OAuth

- **Service URL:** https://app.zipwp.com/
- **Purpose:** OAuth authentication for AI features.
- **When data is sent:** When a user authenticates to use AI features.
- **Data transmitted:** Authentication tokens, site URL.

### Starter Templates Credits

- **Service URL:** https://credits.startertemplates.com/
- **Purpose:** AI credit tracking and balance checking.
- **When data is sent:** When using AI content generation features.
- **Data transmitted:** Authentication tokens, credit usage data.

### ipinfo.io

- **Service URL:** https://ipinfo.io/
- **Purpose:** Determines the server's country code based on its public IP address for geolocation-based feature availability.
- **When data is sent:** On first load when the `ipinfo` provider is selected (result is cached via WordPress transient).
- **Data transmitted:** Server's public IP address.
- **Privacy Policy:** https://ipinfo.io/privacy-policy
- **Terms of Use:** https://ipinfo.io/terms-of-service

### ipify

- **Service URL:** https://api.ipify.org
- **Purpose:** Retrieves the server's public IP address for geolocation detection.
- **When data is sent:** On first load (result is cached via WordPress transient).
- **Data transmitted:** Standard HTTP request (no personal data).
