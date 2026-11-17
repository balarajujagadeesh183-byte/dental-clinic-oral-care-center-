# SmileCare Dental Clinic - deployment checklist

Before going live, search the whole folder (Ctrl+Shift+F in VS Code) and replace:

| Find                       | Replace with                                   |
|----------------------------|------------------------------------------------|
| +91 98765 43210 / tel:+919876543210 | your real clinic phone number         |
| support@smilecare.com, info@smilecare.com | your real email                 |
| YOUR_FORM_ID (contact.html)| your Formspree form ID (https://formspree.io)  |
| [DATE], [CLINIC EMAIL], [CLINIC ADDRESS], [CLINIC PHONE] (privacy.html, terms.html) | your real details |
| href="#" on social icons   | your Facebook / Instagram / WhatsApp / YouTube URLs |

Also: replace Unsplash stock photos and randomuser.me avatars with real clinic photos.

## Not production-ready yet
- login.html / dashboard.html are DEMOS only (no real authentication, data is not saved).
  Either hide the "Dashboard" nav link before launch, or build a real backend
  (Firebase/Supabase/Node). Both pages are marked noindex.
- Appointment form inside dashboard.html is a demo and does not send anything.

## Deploy
Drag this folder onto Netlify Drop (https://app.netlify.com/drop), or use GitHub Pages / Vercel.
