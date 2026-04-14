# @koehler8/cms-theme-neon — Neon Gradient

- **Slug**: `neon`
- **Version**: 1.0.0
- **Author**: koehler8

## Install

```bash
npm install @koehler8/cms-theme-neon
```

```js
// vite.config.js
import cms from '@koehler8/cms/vite';

export default {
  plugins: cms({ siteDir: './site', themes: ['@koehler8/cms-theme-neon'] }),
};
```

Set `site.theme` to `"neon"` in your site config. The CSS rewrites WalletConnect/AppKit chrome. If you cannot reach Google Fonts, self-host the families and update the `@import`.

## Visual Direction
- High-energy dark canvas with magenta–violet–cyan gradients, kinetic glow pulses, and animated CTA shimmers (prefers-reduced-motion is respected).
- Body backgrounds layer drifting radials; CTA rows and hero/promo shells pick up neon highlights and narrower container widths for focus.
- Designed for nightlife/gaming drops or high-intensity presales where motion cues reinforce urgency.

## Token Highlights
- CTA/chip/outline tokens bias toward saturated accents; focus rings and field chrome inherit electric-blue highlights.
- Dedicated modal/backdrop tokens ensure AppKit and in-app dialogs match the neon palette without extra overrides.
- Countdown/status/chart tokens use electric blue for digits and gradients for headline ribbons to stay legible on dark cards.

## Compatibility Notes
- Motion-heavy: shimmer/glow animations are enabled when users allow motion; ensure brand approvals for animated CTAs.
- Theme CSS touches legacy sections (legal cards, sticky CTAs, status metrics, curiosity teasers). Keep any additional overrides inside this folder so other themes remain unaffected.
