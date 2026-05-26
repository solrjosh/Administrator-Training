# Administrator Training Deck Planning Hub

A browser-based tool for Amazon Business ProServe CSMs to generate customized versions of the Administrator Training deck.

## Requirements
- Modern browser (Chrome, Edge, Firefox, Safari)
- `Administrator Training_December2025.pptx` on your local machine
- `jszip.min.js` in the same folder as `index.html`

## Usage
1. Open `index.html` in your browser
2. Select the source PPTX from your local machine
3. Enter the customer name and configure ingress, features, and toggles
4. Click **Generate Deck** — the customized PPTX downloads automatically

## Files Required
```
admin-training-deck-hub/
├── index.html       ← entire application
├── jszip.min.js     ← JSZip 3.10.1 (download from https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js)
└── README.md
```

## Feature Toggles
| Toggle | Slides Affected |
|--------|----------------|
| BOI | 12–13 |
| BPO (+ sub-toggles: Recurring, Individual Allocation, Approvals) | 14–18 |
| Guided Buying Restricted | 31 |
| Guided Buying Blocked | 32 |
| Guided Buying Preferred | 33 |
| Guided Buying Additional Preferences | 34 |
| Tax Exemptions | 36 |
| Debarment Policies | 37 |
| Certifications | 38 |
| Approvals | 39–43 |
| Business Giving (+ Internal Campaigns sub-toggle) | 44–50 |
| 3-Way Match / Receiving | 51–57 |
| Mobile App | 26, 43 (also auto-removed if Punchout selected) |
