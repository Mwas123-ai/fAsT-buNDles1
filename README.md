# Fast Bundles Platform

This is a lightweight web platform that lets customers submit their MPESA payment and automatically get matched with a bundle.

---

## 💼 What’s Inside

- `index.html`: A simple form where users enter:
  - MPESA number
  - Amount sent
  - Bundle category (Data / SMS / Minutes)
- `script.gs`: Google Apps Script to log each submission into a Google Sheet and mark it for auto-processing
- `README.md`: This file

---

## 🚀 How to Use

### 1. Host the Site on GitHub Pages
1. Upload `index.html` to your GitHub repo
2. Go to **Settings → Pages**
3. Set:
   - Branch: `main`
   - Folder: `/ (root)`
4. GitHub gives you a live link:  
   `https://yourusername.github.io/fast-bundles`

### 2. Connect to Google Sheet
1. Create a Google Sheet and open **Extensions → Apps Script**
2. Paste the contents of `script.gs`
3. Click **Deploy → New Deployment**
4. Choose **Web App**
   - Execute as: Me
   - Access: Anyone
5. Copy the Web App URL (replace in `index.html` if needed)

---

## 💸 MPESA Details

- Receiver: **0798853748** (via Send Money or Pochi)
- System will match the amount to:
  - 📶 Data bundles
  - 📩 SMS packages
  - 📞 Minutes offers

---

## 📲 Example Confirmation Message

> ✔️ Your 1.5GB bundle (valid 3 hrs) for Ksh 50 has been delivered.  
> Thanks for choosing Fast Bundles.

---

## 🔧 Next Integrations
- SMS automation via SMSLeopard
- WhatsApp alerts for new payments
- Bingwa/Safdata delivery API

---

Built with ❤️ by Emmanuel Mwangi for Fast Bundles
