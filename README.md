# Block Unwanted Referers and Anchors 🚫🔗

**Block Unwanted Referers and Anchors** is a simple yet powerful WordPress plugin designed to help site owners take control over unwanted traffic, malicious anchors, and protect their SEO from harmful inbound link equity. Whether you need to block specific referers, anchors, or prevent 301 redirects from passing SEO value, this plugin has you covered!

## ✨ Features
- **Block Unwanted Referers:** 🛑 Say goodbye to unwanted referers! Block domains from sending traffic to your site and prevent them from passing link equity (SEO juice) through 301 redirects.
- **Prevent Anchor Manipulation:** ⛔ Block specific anchor texts or non-alphanumeric anchors to ensure malicious anchor text links don’t affect your site.
- **Disable Link Equity for Specific Domains:** 🚫 Add a `noindex, nofollow` tag for requests coming from blocked referers. This prevents search engines from indexing pages and following links triggered by unwanted sources.
- **Disable Copy & Right-Click:** 🔒 Prevent users from copying content by disabling right-clicks and keyboard shortcuts like Ctrl+C and Ctrl+U.
- **Iframe Embedding Protection:** 🔒 Stop your site from being embedded inside iframes, protecting your content from external manipulation.

## 🚀 Getting Started

### Installation
1. Download the plugin or clone the repository.
2. Upload the plugin files to your WordPress site's `/wp-content/plugins/block-unwanted-referers` directory, or install the plugin through the WordPress plugins screen.
3. Activate the plugin through the 'Plugins' screen in WordPress.

### Usage

1. Navigate to the **Blocked Referers** page under the **Settings** menu in your WordPress dashboard.
2. Input the domains you wish to block (comma-separated), such as `example.com, anotherexample.com`.
3. Add specific anchor texts to block if needed.
4. Configure additional settings like **disabling copy and right-click** and **blocking iframe embedding**.
5. Save your settings and let the plugin do the work! 🛠️

### Example Configuration

- Block incoming traffic from `dt-covid.com`, `istanbulescortbayan.com`, `fujikong.cc`, and `onbet88vns.com`.
- Prevent anchor links containing non-alphanumeric characters from passing link equity.
- Ensure the blocked referers can't pass link equity by automatically adding a `noindex, nofollow` meta tag when traffic is detected from them.

## 🔧 Options and Customization
You can configure several powerful settings through the plugin’s dashboard:
- **Blocked Referers:** Easily input domains that you wish to block from sending referral traffic to your site.
- **Blocked Anchors:** Block specific anchor text patterns that might be harmful to your SEO.
- **Disable Copy and Iframe Embedding:** Stop users from right-clicking, copying your content, or embedding your site in iframes.

## 🛠️ Developer Features
This plugin is developer-friendly, offering hooks and actions that you can extend or modify to your liking:
- `add_action('init', 'bur_block_unwanted_referers_and_anchors');`
- `add_action('wp_head', 'disable_right_click_and_copy');`
- Easily extend the functionality by adding more conditions for blocking unwanted behavior.

## 🎨 Screenshots

1. **Settings Page:** Manage blocked referers, anchors, and content protection.
   ![Settings Screenshot](assets/settings.png)

2. **Content Protection:** Seamlessly block right-clicking and content copying.
   ![Right-click Disabled Screenshot](assets/rightclick-disabled.png)

## 👨‍💻 Contributing

We welcome contributions to improve the plugin! Feel free to open issues, submit pull requests, or suggest new features. Let’s work together to make the internet a cleaner, safer place for all.

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🚀 Changelog

### v1.8 (Current Version)
- Introduced the ability to block link equity from incoming 301 redirects by adding a `noindex, nofollow` meta tag for blocked referers.
- Improved admin settings page for better user experience.
- Bug fixes and performance improvements.

### v1.6
- Initial release with options to block referers, anchors, disable copy, and iframe embedding.

---

Take control of your site’s traffic today with **Block Unwanted Referers and Anchors**! ✨🎉
