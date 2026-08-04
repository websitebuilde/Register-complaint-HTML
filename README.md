# Register Complaint HTML

A static consumer-complaint website prototype. It provides a landing page explaining the service, a complaint-reporting form, complaint tracking, FAQ content, and responsive layouts for desktop and mobile screens.

## Pages

- `index.html` — landing page and consumer-rights information
- `registeracomplainthtml.html` — complaint form and tracking-number interface
- `track-your-complaint.html` — tracking page
- `404.html` — not-found page
- `components/` — reusable FAQ, contact-form, and call-to-action sections
- `public/` — images and other public assets

## Run locally

This is a static site and can be previewed with any local HTTP server:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000` in a browser. The project also includes a Parcel dependency for bundling experiments.

## Notes

The complaint form is connected to a Microsoft Forms embed. Replace the embed URL and connect a production backend before using this as a real complaint-management service. No sensitive complaint data should be submitted to an unreviewed deployment.
