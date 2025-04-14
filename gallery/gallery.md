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

[🚗 My Car](#car) | [🇺🇸 USA](#usa) | [🇨🇳 China](#china) | [🇯🇵 Japan](#japan)


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

### <a name="usa"></a> USA

<div class="gallery-section">
  <div class="gallery">
    <img src="/assets/images/usa1.JPG" alt="usa1">
    <img src="/assets/images/usa2.JPG" alt="usa2">
    <img src="/assets/images/usa3.JPG" alt="usa3">
    <img src="/assets/images/usa4.JPG" alt="usa4">
    <img src="/assets/images/usa5.JPG" alt="usa5">
    <img src="/assets/images/usa6.JPG" alt="usa6">
    <img src="/assets/images/usa7.JPG" alt="usa7">
    <img src="/assets/images/usa8.JPG" alt="usa8">
    <img src="/assets/images/usa9.JPG" alt="usa9">
  </div>
</div>


---

### <a name="china"></a> China

<div class="gallery-section">
  <div class="gallery">
    <img src="/assets/images/china1.JPG" alt="china1">
    <img src="/assets/images/china2.JPG" alt="china2">
    <img src="/assets/images/china3.JPG" alt="china3">
    <img src="/assets/images/china4.JPG" alt="china4">
    <img src="/assets/images/china5.JPG" alt="china5">
    <img src="/assets/images/china6.JPG" alt="china6">
    <img src="/assets/images/china7.JPG" alt="china7">
  </div>
</div>

---

### <a name="japan"></a> Japan

### <a name="japan"></a> Japan

<div class="gallery-section">
  <div class="gallery">
    <img src="/assets/images/japan1.JPG" alt="japan1">
    <img src="/assets/images/japan2.JPG" alt="japan2">
    <img src="/assets/images/japan3.JPG" alt="japan3">
    <img src="/assets/images/japan4.JPG" alt="japan4">
    <img src="/assets/images/japan5.JPG" alt="japan5">
    <img src="/assets/images/japan6.JPG" alt="japan6">
  </div>
</div>


---

