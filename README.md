# 🐦 Switter - A Twitter Mimic Project

## **✨ Live Preview:** [**Twitter Mimic**](https://titter-mimic.netlify.app/) ✨

---

This project is a front-end implementation replicating the core visual structure and layout of the Twitter (now X) desktop interface, affectionately named "Switter". It's built primarily using HTML and CSS, with a strong focus on layout using Flexbox.

### Key Features Implemented:

*   🧭 **Left Sidebar Navigation (`<header>`):**
    *   Fixed vertical navigation panel.
    *   Includes main navigation links (Home, Explore, Notifications, Messages, etc.) with Material Icons and text labels.
    *   Prominent "Sweet" (Tweet) action button.
    *   User account section at the bottom displaying profile picture, name, handle, and options icon.
    *   Hover effects for interactivity on links and the account section.
*   📰 **Main Feed Section (`<section class="main-feed">`):**
    *   Central column for displaying tweets.
    *   Sticky "Home" title bar at the top.
    *   "What's happening?" input area to compose a new "Sweet", including:
        *   User profile picture.
        *   Text input field.
        *   Action icons (image, GIF, poll, emoji, schedule).
        *   "Sweet" submit button.
    *   Displays a timeline of "Sweets" (`<figure class="feed-tweet">`), each showing:
        *   Tweeter's profile picture.
        *   Tweeter's name, handle, and timestamp.
        *   The text content of the "Sweet".
        *   Action icons (💬 Reply, 🔄 Retweet, ❤️ Like, 📤 Share).
*   ✨ **Right Sidebar Feed (`<section class="side-feed">`):**
    *   Right-hand column for auxiliary information.
    *   🔍 Sticky search bar.
    *   📊 "What's happening?" card displaying trending topics with category, topic name, and volume (placeholder count).
    *   👤 "Who to follow?" card suggesting profiles with picture, name, handle, and a "Follow" button.
    *   "Show more" links for both trending and follow sections.
*   💪 **Layout & Styling:**
    *   Built using a three-column layout (Left Nav, Main Feed, Right Feed).
    *   Heavily utilizes **CSS Flexbox** for arranging components both horizontally and vertically (`hor-container`, `ver-container` helpers).
    *   Dark theme implementation.
    *   Basic responsiveness included via Media Queries (`queries.css`) primarily adjusting the left sidebar for narrower screens.

### Using:

*   🧱 **HTML5:** For the structure and semantic content.
*   🎨 **CSS3:** For styling, layout, and responsiveness.
    *   **Flexbox:** The primary layout mechanism.
    *   **CSS Variables:** For defining reusable values (though minimally used here).
    *   **Google Fonts (Poppins) & Material Icons:** For typography and iconography.

---
