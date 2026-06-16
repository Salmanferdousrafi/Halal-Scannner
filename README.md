#  HalalScan (Enterprise Edition)

HalalScan is a modern, mobile-first web and cross-platform ecosystem designed to help Muslims worldwide make informed, trustworthy dietary choices. The platform allows users to instantly scan product barcodes, extract raw text ingredient labels via on-device computer vision (OCR), look up additive regulatory listings (E-numbers), and explore a global culinary recipe index backed by a localized dynamic Islamic ruling algorithm.

---

##  Key Features

*   **Multi-Platform Mobile-First UI:** Built with a premium Islamic-themed aesthetic using an elegant emerald green and cream color palette, featuring fluid UI layouts.
*   **Dual-Scanner Engine:** Features an online/offline fallback barcode processing pipeline paired with an on-device Optical Character Recognition (OCR) text analyzer to scan raw ingredient labels.
*   **The Multi-Madhab Trust Algorithm:** Dynamically adjusts ingredient status verdicts (Halal, Haram, Makruh, Unknown) on the fly based on the user's chosen school of thought (Hanafi, Shafi'i, Maliki, Hanbali).
*   **Global Recipe Archive:** Integrates an international culinary indexing system that screens recipes for compliance, complete with a native, context-linked YouTube streaming video player.
*   **Programmatic SEO Architecture:** Next.js server-side structures render individual optimization routes with automated JSON-LD schemas for high ranking on search engines.
*   **Secure Cloud Infrastructure:** Robust Postgres design managed by Supabase, locked down with iron-clad Row-Level Security (RLS) layers to preserve platform data integrity.

---

##  Project Directory Structure

```text
halalscan-app/
├── README.md                     # Documentation Guide
├── supabase/
│   └── schema.sql                # Relational Database Schema & RLS Security Policies
├── src/
│   ├── components/
│   │   ├── OCRScanner.jsx        # Smart Camera UI Component for Ingredient Text Extraction
│   │   └── RecipeCard.jsx        # Modular UI Recipe Card Component with Visual Health Flags
│   └── utils/
│       ├── halalEngine.js        # Multi-Madhab Jurisprudential Sorting & Offline Caching Vector
│       ├── textParser.js         # OCR String Normalization Token Matcher 
│       └── youtubeService.js     # Automatic Privacy-Safe YouTube Stream Linking Core
└── app/
    ├── ingredient/
    │   └── [slug]/
    │       └── page.jsx          # Dynamic SEO Indexing Route for Additives & E-Numbers
    ├── product/
    │   └── [barcode]/
    │       └── page.jsx          # Dynamic SEO Scanning Results Hub + Structured JSON-LD Data
    └── recipes/
        ├── page.jsx              # Unified Global Search Bar & Recipe Library Portal
        └── [id]/
            └── page.jsx          # Individual Recipe View Layout with Embedded Video Tutorials

 **Initialize Database:**
    *   Log in to Supabase.
    *   Paste the contents of `supabase/schema.sql` into the SQL Editor and run it.
3.  **Deploy to Web:**
    *   Connect your GitHub repository to Vercel.
    *   Add your Supabase URL and API Key as Environment Variables.
    *   Deploy! Your app is now live at `your-app.vercel.app`.

---

##  Trust & Security

HalalScan is built on the principle of **Amanah (Trust)**. 
*   **Data Integrity:** Product statuses can only be modified by verified administrators and scholars.
*   **Privacy:** Scan history is encrypted and accessible only to the account owner.
*   **Offline-First:** Critical ingredient data is cached locally to work even in grocery stores with poor signal.

---

##  Contributing
We welcome contributions from developers, designers, and scholars! Please read our `CONTRIBUTING.md` (coming soon) to see how you can help.

##  License
This project is licensed under the **MIT License** – feel free to use and adapt it for the benefit of the Ummah.

---

### **Launch the App**
[Scan a Barcode] | [Browse Recipes] | [Learn More]

---

### 💡Pro Tip for GitHub
When you upload this to your repository, GitHub will automatically format the text with headers, bolding, and links. It also helps Google find your project through the "SEO" and "Mission Statement" sections included above!

<FollowUp label="Ready to add the CONTRIBUTING.md file for your community?" query="Create a CONTRIBUTING.md file for the HalalScan project explaining how developers and scholars can help."/>
