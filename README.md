# Wedding Invitation Website — B. Benish & F. Sahaya Runa Asime

A wedding invitation website customized for **B. Benish & F. Sahaya Runa Asime**.

---

## Wedding Schedule & Details

### 1. Engagement Ceremony
- **Date & Day:** 26 December 2026, Saturday
- **Time:** 4:00 PM
- **Venue:** St. Jude's Auditorium, Simon Colony

### 2. Wedding Reception
- **Date & Day:** 26 December 2026, Saturday
- **Time:** 6:00 PM onwards
- **Venue:** St. Jude's Auditorium, Simon Colony
- **Hosted By:**
  - Ms. B. Pratheesha (Physician Associate)
  - Mrs. Baby (Grandmom)
  - Kith and Kin

### 3. Holy Matrimony (Wedding Ceremony)
- **Date & Day:** 28 December 2026, Monday
- **Time:** 10:00 AM
- **Venue:** St. Jude's Church, Simon Colony

---

## Couple & Family Details

- **Groom:** B. Benish, B.E. (Mechanical)
  - **Parents:** Mr. G. Benadict & Mrs. S. Mary Mabel
  - **Address:** Simon Colony
- **Bride:** F. Sahaya Runa Asime, BBA, MBA
  - **Parents:** Mr. P. Franklin & Mrs. Mary Kavitha
  - **Address:** Simon Colony
- **Holy Bible Verse:** *“What God has joined together, let no one separate.”* — Mark 10:9

---

## Quick Start (How to Run Locally)

Since modern browsers block ES modules (`<script type="module">`) over the `file://` protocol due to CORS security policies, this website should be served through a local HTTP server:

### Option 1: Using Python (No setup needed)
Run in terminal:
```bash
python3 -m http.server 3000
```
Then open: [http://localhost:3000](http://localhost:3000)

### Option 2: Using Node.js / npx
```bash
npx serve .
# or
npm run serve
```

---

## File Structure

- [index.html](file:///Users/rameesr/Downloads/%20B.%20Benish%20&%20F.%20Sahaya%20Runa%20Asime%20/index.html) - Main entry page, metadata, and social OpenGraph tags
- `assets/`
  - `index-BLQ10aRV.js` - Main React application bundle with couple details and event schedules
  - `index-DO3rKpzU.css` - Custom styling and typography rules
  - `optimized/backgrounds/` - High-resolution background artwork for desktop and mobile
- `font 4/` / `font%204/` - Custom font (`ELEGANT.otf`)
- `music.mp3` - Background wedding ceremony music
