# Bad Website Blocklist

This is a blocklist that intends to remove garbage websites from search results, such as AI-generated articles, low-effort spam sites, and thinly-veiled advertisements acting as information.

<div align="center">
  <b>Comparison with the blocklist vs without</b> 
  
  (AI & SEO spam are removed to make room for good articles)
  
  <img src="https://files.catbox.moe/tyecc6.avif" type="image/avif" alt="Animated AVIF showing a comparison of the blocklist on with the blocklist off." width="75%" />
</div>

Another big goal of this repo is to try to be as organized as possible, [every website that gets blocked has an issue](https://github.com/popcar2/BadWebsiteBlocklist/issues?q=is%3Aissue+is%3Aclosed) explaining why it was added to the list for future reference.

## How to use

1. Install the [uBlacklist extension](https://ublacklist.github.io/docs)
2. Click on the extension in the browser toolbar, then click on "Options"
3. Click on "SERPINFO" and enable search engines you use
4. Scroll down to subscriptions and click "Add a subscription"
5. Give it a name & add this as the URL: https://raw.githubusercontent.com/popcar2/BadWebsiteBlocklist/refs/heads/main/uBlacklist.txt

And that's it. The websites in the list should no longer appear on when searching! The subscription means the blocklist will always stay up to date as well.

## Contributing

If you'd like to add a website to the list, [create an issue](https://github.com/popcar2/BadWebsiteBlocklist/issues/new/choose). For more info, check out [the contributing guide](https://github.com/popcar2/BadWebsiteBlocklist/blob/main/CONTRIBUTING.md). Thanks.

---

This was inspired by the great effort of [the huge AI blocklist](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist) and my boiling hatred to bad tech support articles.
