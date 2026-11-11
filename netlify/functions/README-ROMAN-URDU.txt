CRYPTO WEB3 WEBSITE — SETUP GUIDE

Is ZIP mein website ka source code hai:
- index.html, styles.css, app.js
- Netlify function: netlify/functions/tokens.mjs
- netlify.toml aur package.json

DEPLOY KARNE KA TAREEQA
1. Netlify par login karein.
2. Is ZIP ko extract karke project folder ko GitHub repository mein upload karein, ya Netlify CLI se deploy karein.
3. Netlify site ke Environment Variables mein ADMIN_PASSWORD naam ka variable banayein aur apna strong password set karein.
4. Site deploy karein. Netlify Functions aur Netlify Blobs enabled hon.
5. Website ke footer mein "Admin settings" khol kar password enter karein.

TOKEN CONTROL
- Default token ATSHEE ka Solana CA hai.
- Admin settings se aur Solana token CAs add kar sakte hain.
- Dropdown se token select karke "Set selected as primary" kar sakte hain.
- Live price, market cap, liquidity, 24h volume aur 24h change DexScreener public API se aate hain.
- Chart DexScreener embed se load hota hai.
- Multiple token save karne ke liye Netlify Blobs function istemal hota hai.

IMPORTANT
- Admin password ko kisi ke saath share na karein.
- Yeh website khud payment collect nahi karti. Promotion buttons aapke Telegram bot @AtsheeVipPaymentBot par le jaate hain.
- Payment automation/webhook is package mein configure nahi hai; uske liye payment provider credentials aur webhook setup alag se chahiye.
- Market data provider ki availability, trading pair aur network par depend karta hai. Figures investment advice nahi hain.
- Jo SEPPUKU sample metrics share hue thay unhein kisi token se attach nahi kiya gaya, kyunki unki token identity confirm nahi hui.
