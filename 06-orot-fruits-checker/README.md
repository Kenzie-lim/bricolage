# orot-fruits-checker (오롯 과일 입고 체커)

Inventory checker for a Korean fruit shop (*오롯*, an unmanned fruit store). Upload a photo of the daily delivery list → Claude Vision API extracts product names and quantities → tap each item to check off as stocked. Designed for glove-friendly use: tap for +1, long-press for −1, with haptic feedback.

Requires a user-provided Anthropic API key (stored in localStorage at runtime).

Stack: React 18 (CDN), Claude Vision API, PWA.
