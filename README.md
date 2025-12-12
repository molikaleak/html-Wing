📦 Wing Add-On UI (HTML/CSS)

A simple, responsive UI for displaying Wing "Pack & Add-On" cards using only HTML & CSS.
Clean layout, flexbox grid, and image-based addon cards.

🚀 Features

Responsive addon card grid

Clean modern design

Easy to customize

Pure HTML + CSS (no frameworks)

Supports images for each addon

📁 Project Structure
html-Wing/
│── index.html
│── style.css
│── assets/
│     ├── data-plus.avif
│     ├── rescue.avif
│     └── learn.avif
└── README.md

🖼 Add-On Cards Preview

Each card supports an image + title, like:

<div class="addon-card">
  <img src="./assets/data-plus.avif" alt="Data+" />
  <p>Data+</p>
</div>

🧩 HTML Example
<section id="addons" class="container addons">
  <h2 class="section-title">Pack & Add-On</h2>

  <div class="addon-grid">
    <div class="addon-card">
      <img src="./assets/data-plus.avif" alt="Data+" />
      <p>Data+</p>
    </div>

    <div class="addon-card">
      <img src="./assets/rescue.avif" alt="Rescue Pack" />
      <p>Data Rescue Add-on</p>
    </div>

    <div class="addon-card">
      <img src="./assets/learn.avif" alt="Learn Add-On" />
      <p>Learn Add-On</p>
    </div>
  </div>
</section>

🎨 CSS Example
.addon-grid {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 20px;
}

.addon-card {
  background: #fff;
  padding: 15px;
  width: 300px;
  border-radius: 15px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  text-align: center;
}

.addon-card img {
  width: 100%;
  border-radius: 12px;
}

.addon-card p {
  margin-top: 12px;
  font-size: 20px;
  font-weight: 600;
}

🛠 How to Run

Just open the index.html file in your browser:

open index.html

👤 Author

Molika Leak

GitHub → https://github.com/molikaleak
