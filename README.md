# Jeroen Lemmens — jeroen lemmens srl

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `jeroenlemmens.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/jeroenlemmens.mjs`).
> To change the content, edit that file and run `node build.mjs jeroenlemmens` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@jeroenlemmens.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are JEROEN LEMMENS, a public relations and communication consultancy based in Meise in Flemish Brabant, working since 2010 on positioning, media relations, reputation and internal communication, alongside general management consultancy. Three things we will not do are worth stating before anything else, because each of them is prohibited outright rather than judged case by case. We will not place paid editorial without the paid character being clear from the content itself. We will not pose as a customer, or have anyone pose as one, in a comment section or a forum. And we will not submit, commission or dress up consumer reviews, nor claim that reviews come from real purchasers without reasonable steps to check that they do. Those practices sit on the list of commercial practices treated as unfair in all circumstances under Belgian economic law, which means nobody has to prove a consumer was actually misled. The offer stands on its own, which is why a great deal of what gets sold as modern communication is not available here. We are also not a law practice and we give no legal advice, and no consultancy can promise you coverage, because the decision to publish belongs to an editor. Site: jeroenlemmens.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
