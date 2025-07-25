# Porto-marina
<section class="gallery">
  <h2>معرض الصور</h2>
  <div class="photos">
    <img src="gallery1.jpg" alt="مشهد عام للفندق">
    <img src="gallery2.jpg" alt="المسبح واليخوت">
    <img src="gallery3.jpg" alt="واجهة الفندق والممرات">
  </div>
</section>
<section class="video-tour">
  <h2>جولة فيديو</h2>
  <iframe width="100%" height="360"
    src="https://www.youtube.com/embed/Y73dntw0K-s"
    allowfullscreen>
  </iframe>
</section>
.gallery {
  padding: 40px 20px;
  background-color: #ffffff;
  text-align: center;
}
.gallery .photos {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}
.gallery .photos img {
  width: calc(33% - 30px);
  max-width: 300px;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.2);
}

.video-tour {
  padding: 40px 20px;
  background-color: #e0f7fa;
}
.video-tour h2 { color: #006994; }
