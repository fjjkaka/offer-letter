# Offer Letter

Built by Harshit, for Tisha. A single static page: plain HTML, CSS and JS, with no build step.

## Deploy on GitHub Pages

1. Open the repo on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Pick branch **main**, folder **/ (root)**, and click **Save**.
4. Wait about a minute. The site goes live at `https://fjjkaka.github.io/offer-letter/`.

## Set up notifications (so you know her answer)

1. Install the free **ntfy** app (iOS App Store or Google Play).
2. Open `https://fjjkaka.github.io/offer-letter/#setup` on your laptop or phone.
3. Copy the **ntfy channel** name shown there. In the ntfy app, tap **+** and subscribe to exactly that name.
4. Tap **Test ping**. A notification should arrive on your phone.

You get a notification when she:
- opens the page (once per visit)
- taps **Yes** or **Okay, maybe**
- confirms her pick of place, day and time

## Make the private link

On the same `#setup` page:
1. Fill in your WhatsApp number with country code (e.g. `91…`). The place and date/time are optional suggestions: Tisha picks where and when herself after saying yes, and your suggestion shows up as "Harshit's idea".
2. Tap **Preview (no pings)** to check it. Previews never send notifications.
3. Tap **Copy link** and send *that* link to her.

The link is short, e.g. `https://fjjkaka.github.io/offer-letter/#k4pz3kw5aq.919876543210` (your channel, then your number). Any suggestion you add rides in the same `#...` part. Browsers never send that part to the server, so none of it is stored in this public repo.

## Local preview

```sh
python3 -m http.server 8000   # then open http://localhost:8000/#setup
```
