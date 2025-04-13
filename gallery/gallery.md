---
layout: single
title: "Gallery"
permalink: /gallery/
---

<style>
.gallery-section {
  margin: 40px 0;
}

.gallery-title {
  font-size: 22px;
  margin: 20px 0 10px;
  font-weight: bold;
  border-left: 5px solid #4a90e2;
  padding-left: 10px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 12px;
  justify-items: center;
}

.gallery img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  object-fit: contain; /* 保留原始比例，不裁剪 */
}

.gallery img:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 12px rgba(0,0,0,0.3);
}

@media screen and (max-width: 1024px) {
  .gallery img {
    flex: 1 1 calc(50% - 10px);
    max-width: calc(50% - 10px);
  }
}

@media screen and (max-width: 600px) {
  .gallery img {
    flex: 1 1 100%;
    max-width: 100%;
  }
}
</style>
---


### <a name="car"></a> My car: CT5-V Blackwing

<div class="gallery-section">
  <div class="gallery">
    <img src="/assets/images/car1.jpg" alt="car1">
    <img src="/assets/images/car_2.jpg" alt="car2">
    <img src="/assets/images/car_3.jpg" alt="car3">
    <img src="/assets/images/car4.jpg" alt="car4">
  </div>
</div>

---

### <a name="japan"></a> Trip in Japan

<div class="gallery-section">

  <div class="gallery">
    <img src="/assets/images/japan1.jpg" alt="japan1">
    <img src="/assets/images/japan2.jpg" alt="japan2">
    <img src="/assets/images/japan3.jpg" alt="japan3">
  </div>
</div>

---

