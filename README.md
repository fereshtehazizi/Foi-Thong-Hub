# Foi Thong Hub

A restaurant website for Foi Thong (Bangkok dining) built with HTML, CSS, and Bootstrap.

## Project Structure

```
Foi-Thong-Hub/
├── index.html                  # Home page
├── foi-thong.html              # Menu / order page
├── README.md
└── assets/
    ├── css/
    │   └── Foodie.css          # Main stylesheet (shared by both pages)
    └── images/
        ├── logos/              # Brand icons (hamburger logo, favicon)
        ├── hero/               # Large hero / carousel images
        ├── restaurants/        # Restaurant photos
        ├── chefs/              # Chef portraits
        ├── menu/               # Menu item photos
        ├── team/               # Team member photos
        ├── customers/          # Customer review avatars
        └── services/           # Service card GIFs
```

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Home — hero carousel, about, team, services, customer reviews, contact |
| `foi-thong.html` | Foi Thong menu, table booking, and online order forms |

## Image Reference Map

Old name → New location (for reference after the reorganization):

| Old file (root) | New path |
|-----------------|----------|
| `Foodie.css` | `assets/css/Foodie.css` |
| `hamburger.png` | `assets/images/logos/hamburger.png` |
| `burger.png` | `assets/images/logos/burger.png` |
| `bangkok.jpg` | `assets/images/hero/bangkok.jpg` |
| `rest 2.jpg` | `assets/images/hero/rest-2.jpg` |
| `food-02.jpg` | `assets/images/hero/food-02.jpg` |
| `top-view-cooked-tur-meat-with-asparagus-tasty-sauce.png` | `assets/images/hero/…` (unchanged name) |
| `Gaa res.jpg` | `assets/images/restaurants/gaa-res.jpg` |
| `le du res'.jpg` | `assets/images/restaurants/le-du-res.jpg` |
| `neham res.jpg` | `assets/images/restaurants/nahm-res.jpg` |
| `suhring res.webp` | `assets/images/restaurants/suhring-res.webp` |
| `gaa-chef.jpg` | `assets/images/chefs/gaa-chef.jpg` |
| `suhring-chef.jpg` | `assets/images/chefs/suhring-chef.jpg` |
| `Le-Du-Kaan_Chef-Ton-01-scaled.jpg` | `assets/images/chefs/le-du-kaan-chef-ton.jpg` |
| `nahm-chef.jpeg` | `assets/images/chefs/nahm-chef.jpeg` |
| `menu1.jpg` | `assets/images/menu/menu-1.jpg` |
| `menu-2.jpg` … `menu-8.jpg` | `assets/images/menu/menu-2.jpg` … `menu-8.jpg` |
| `team1.jpeg`, `team2.jpeg` | `assets/images/team/team-1.jpeg`, `team-2.jpeg` |
| `customer-pro1.jpeg` … `customer-pro5.jpeg` | `assets/images/customers/customer-pro-1.jpeg` … `-5.jpeg` |
| `8 steps to becoming a successful chef.gif` | `assets/images/services/chef-steps.gif` |
| `a strange restaurant.gif` | `assets/images/services/strange-restaurant.gif` |
| `Scooter Courier.gif` | `assets/images/services/scooter-courier.gif` |
| `Meeting.gif` | `assets/images/services/meeting.gif` |
| `421Hand from under table.gif` | `assets/images/services/hand-from-under-table.gif` *(currently unused)* |

## Notes

- Filenames were normalized to lowercase kebab-case (no spaces or special characters).
- `assets/images/services/hand-from-under-table.gif` is not referenced by any page — it was kept in case it's needed later.
- All local paths in the HTML use relative paths from the page location, so the site works when opened directly or served statically (e.g., GitHub Pages).
