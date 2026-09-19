KARJOKROM — CodeCanyon Asset Pack
=================================

REQUIRED CODECANYON UPLOADS
---------------------------
karjokrom-thumbnail-80x80.png            80 x 80     Item thumbnail          [NEEDS REBUILD - still old green brand]
karjokrom-inline-preview-590x300.png     590 x 300   Inline preview image
  (.jpg version included if a smaller file is preferred)
karjokrom-description.png               1180 x 12903 Item description image
  karjokrom-description.jpg              same, ~1.5 MB — use this if PNG is too large

EXTRAS
------
karjokrom-preview-large-1770x900.png     Full-resolution hero              [NEEDS REBUILD - still old green brand]
screenshots/                             16 UI screens                     [NEEDS REBUILD - hand-drawn mockups, not the real app]
logo/                                    Brand mark                        [NEEDS REBUILD - still old green K]

BRAND
-----
Two deliberate brands run side by side:

  MARKETING / LANDING PAGE (karjokrom.com) — used for these asset wrappers
  Brand / POS   #2F44E0      Sales Suite  #DC4B78      HRM  #E0930B
  Success       #12946A      Ink  #0F1222 / #454C61 / #79809A
  Line  #E8EAF3             Soft #F7F8FD             Dark #101425
  Typeface      Inter + Inter Display (Noto Sans Bengali for Bangla)

  TENANT + LANDLORD ADMIN — what you see inside every screenshot
  Primary green #0F9D76 family, as shipped in the app.

The description and inline images use the indigo marketing brand for the
wrapper and show the green admin UI unretouched inside the browser frames.

WHAT THE DESCRIPTION IMAGE SHOWS
--------------------------------
Real screenshots captured from the running app on 19 Sep 2026 — no mockups.

  Billing / plans      Module pricing, coupon codes, cancel subscription
  POS (Sell)           Product grid, order panel, split payment
  Thermal receipt      58mm output, cropped from the live print preview
  Products             Catalogue with categories / brands / attributes tabs
  Purchase             Three-step entry with live totals
  Sales Book           Sales + sales return, damage and due per invoice
  Contact List         Customers and suppliers with invoice history
  Due Book             Sale due, return refundable, advance balance
  Ledger Details       Running balance per person
  Barcodes             Generation and bulk label print
  Stock Transfers      Register + line-level transfer detail
  Profit Loss Report   Per-product revenue, cost and margin

VERIFIED CLAIMS (checked against the codebase, Sep 2026)
--------------------------------------------------------
  3 billable modules    POS ৳1,000 · HRM ৳800 · Sales Suite ৳600 per month
  Core                  Always free (users, roles, settings, dashboard, media)
  4 couriers            Steadfast, Pathao, RedX, BD Courier (app/Services/Courier)
  2 gateways            bKash, SSLCommerz
  24 reports            18 POS + 3 HRM + 3 platform (router route count)
  186 routes            19 app + 107 tenant + 34 HRM + 26 platform
  490 Vue components    resources/js/src/views
  2 languages           lang/bn, lang/en
  Stack                 Laravel 11, PHP 8.2+, Vue 3.5, Vite 6, Pinia,
                        Chart.js 4, Laravel Echo + Pusher, Sanctum,
                        Spatie MediaLibrary, DomPDF, Maatwebsite Excel,
                        Milon Barcode, Twilio SDK, FullCalendar

  NOT claimed: RTL support — there is none in the codebase. The previous
  version of this pack advertised "RTL-ready", which was incorrect.

KNOWN GAPS — STILL TO DO
------------------------
  1. No HRM screenshots yet. Employees, Attendance, Leave, Payroll, Assets
     and Performance are sold as a ৳800/month module but are not pictured.
  2. No Sales Suite screenshots yet. Telesales, Order Confirm and the courier
     booking screens are the ৳600/month module and are not pictured.
  3. No Wallet screenshot. The bKash / SSLCommerz top-up flow is the core
     billing differentiator and deserves a section.
  4. No Dashboard screenshot. The seeded demo data shows a net loss of
     ৳-2,66,238 (purchases ৳2,72,000 against sales ৳5,762), so the Daily
     Summary and Dashboard screens were left out rather than advertise it.
     Reseed with balanced demo data and both can be added.
  5. Landlord / platform owner back office is not pictured at all.
  6. Pricing copy conflict: the Billing screen says "Save up to 20% with
     yearly billing", but ৳10,000/yr against ৳1,000/mo is 16.7% (2 months
     free). The landing page says "2 months free". Pick one.

REBUILD
-------
Source HTML and the render script live outside this folder; ask Claude to
regenerate after dropping new screenshots in. Both images are rendered at
2x and downsampled with Lanczos, so text stays crisp at CodeCanyon's
590px display width.
