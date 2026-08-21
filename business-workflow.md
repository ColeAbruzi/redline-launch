# RedLineLaunch — Client Website Workflow

This is the standard process web agencies use to go from "client says yes" to "client owns a live website." It's the same basic model whether you're a two-person shop or a big agency — just scaled down.

The big mental shift from SiteGround: on SiteGround, you build **your own** site, in **your own** account, and it never leaves. For clients, you build **in a workspace you control**, then **hand off ownership** at the end. That handoff step is the part that trips people up, so it gets its own section below.

---

## The 6-Stage Workflow

### 1. Discovery (Before any building)
Figure out what the client actually needs before touching AI or code.
- What does the business do, who are their customers?
- What pages do they need (usually: Home, Services, About, Contact)?
- Do they have a logo, photos, brand colors already, or do you need to help create a look?
- What's the goal of the site — phone calls? Contact form leads? Just looking legit online?

**Output:** A short list of content/pages, written down, that both you and the client agree on. This becomes your AI prompt input in the next step.

### 2. Build (This is where AI comes in)
Use your `landing-page-template` repo as the starting skeleton, then use AI to generate/customize the actual content and code for that client — write the headline copy, generate section text, adjust the layout, help troubleshoot code.

- Create a new repo from your template for this client
- This lives under **your** GitHub org (`redlinelaunch`) — not the client's account yet
- Deploy it to a **staging URL** first: `redlinelaunch.github.io/client-name-site` — this is your working draft, not the final address

This is your private workspace. Nothing is "live" for the public yet in a way the client would share around.

### 3. Client Review
Send the client the staging link. This is normal industry practice — nobody ships straight to a final domain without approval first.
- Client gives feedback ("change this photo," "fix this phone number")
- You revise in the same repo
- Repeat until they say "looks good"

**Rule of thumb:** build on a branch, not directly on `main`, so a mid-review change never breaks what the client is currently looking at.

### 4. Domain & Launch
This is where the site gets its real, permanent address. Two common models — pick one per client:

**Model A: Client owns the domain (most common, most professional)**
- Client buys their own domain (or you buy it *for* them, they pay you back — either way, ownership sits in *their* name/account)
- You just tell them what DNS records to add (the A records / CNAME pointing to your GitHub Pages site — from the earlier conversation)
- Add the `CNAME` file to the repo with their domain
- **Why this matters:** if the client ever leaves you for another web person, or you graduate and shut down RedLineLaunch, they keep their domain. This is the standard, trustworthy way agencies operate — you never want to be the one holding a client's domain hostage.

**Model B: You manage the domain for them (subscription model)**
- You buy and renew the domain on their behalf as part of an ongoing support/hosting fee
- More recurring revenue for you, but more responsibility (you must renew on time or their site disappears)
- Common for clients who don't want to deal with any of the technical side at all

Most professional agencies default to **Model A** for the domain, even if they charge for setup help.

### 5. Repo Transfer (the "who owns the code" question)
Separate from the domain question — who owns the actual website code?

- **Keep it in your org:** Client's site stays in a repo under `redlinelaunch` on GitHub. You maintain full control; if they want changes later, they come to you. This is effectively how most small agencies operate — you keep the "workshop," they get the finished product live on their domain.
- **Transfer the repo to them:** GitHub lets you transfer repo ownership to another GitHub account for free (Settings → Transfer Ownership). Full independence for the client, but means you lose easy access for future updates unless they re-add you as a collaborator.

**Industry norm:** most agencies keep the repo, and offer a support retainer for changes — this is Model A for domains + repo stays with you. It's the standard "we build it, you own the site, we maintain the code" arrangement, and it's also your ongoing revenue.

### 6. Support & Maintenance
This is the actual business model, not just the build:
- **One-time build fee** — what you charge to design/build the initial site
- **Optional monthly/annual support fee** — for future edits, adding new content, fixing bugs, keeping things updated. This is standard in the industry and where a lot of agencies make recurring money instead of one-off payments.

---

## Quick Summary for Cole

| Stage | What happens | Where |
|---|---|---|
| 1. Discovery | Learn what client needs | Conversation/notes |
| 2. Build | AI + template → real site | Your GitHub org, staging URL |
| 3. Review | Client approves | Same repo, staging URL |
| 4. Launch | Real domain connected | Client's domain (their account) |
| 5. Ownership | Decide who keeps the code | Usually stays in your org |
| 6. Support | Ongoing fixes/updates | Retainer or per-request |

The short version to explain to a client: **"We build it and host the code, you own your domain, and we're here for updates after launch."** That's the exact same pitch nearly every small web agency uses.
