<template>
  <h1>Curiculum Vitae</h1>
  <div class="cv justify-content-center">
    <div class="profile">
      <img src="../assets/cv1.png"   style="border-radius: 50%; width: 150px;" />
      <h2 class="name"><b>Dewi Pulung Sari</b></h2>
      <hr>
      <p>GENDER: Perempuan</p>
      <p>AGAMA: Islam</p>
      <p>TTL: 15 Mei 2007,Kab.semarang</p>
      <p>UMUR: 15 Tahun</p>
      <p>ALAMAT: Jatijajar Kec.bergas Kab.semarang</p>
      <p>NO HP: 083838890628</p>
      <p>EMAIL: sardewi461@gmail.com</p>
      <br>
      <h6>CONTACT ME</h6>
      <hr>
      <div class="contact">
        <i class="bi bi-twitter">  Twitter: dewipsari15</i>&nbsp; <br>
        <i class="bi bi-instagram">  Instagram: dewipsari15</i>&nbsp; <br>
        <i class="bi bi-facebook">  Facebook: dewipsari15</i>&nbsp; <br>
        <i class="bi bi-tiktok">  Tiktok: dewipsari15</i>&nbsp; <br>
        <i class="bi bi-telegram">  Telegram: +62 83838890628</i>
      </div>
    </div>
    <div class="about">
      <div class="school">
        <i class="bi bi-mortarboard-fill fs-3"> EDUCATION</i>
        <hr>
        <ul>
          <li>RA H.M Subandi</li>
          <li>SDIP H.M Subandi</li>
          <li>MTs H.M Subandi</li>
          <li>SMK Bina Nusantara</li>
        </ul>
      </div>
      <i class="bi bi-balloon-fill fs-3"> FAVORIT</i>
      <hr>
      <ul>
        <li>bercerita</li>
        <li>membaca Puisi</li>
        <li>taekwondo</li>
      </ul>
      <i class="bi bi-flower2 fs-2">  SKILLS</i>
      <hr>
      <div class="progress">
        <div
          class="progress-bar"
          role="progressbar"
          aria-label="Example with label"
          style="width: 75%"
          aria-valuenow="25"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          HTML
        </div>
      </div>
      <br>
      <div class="progress">
        <div
          class="progress-bar"
          role="progressbar"
          aria-label="Example with label"
          style="width: 60%"
          aria-valuenow="25"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          CSS
        </div>
      </div>
      <br>
      <div class="progress">
        <div
          class="progress-bar"
          role="progressbar"
          aria-label="Example with label"
          style="width: 45%"
          aria-valuenow="25"
          aria-valuemin="0"
          aria-valuemax="100"
        >
          Java Script
        </div>
      </div>
      <br>
      <div class="certification">
        <i class="bi bi-trophy-fill fs-3">  CERTIFICATION</i>
        <hr>
        <ul>
          <li>Sertifikat keanggotaan pramuka, pada tahun 2021.</li>
          <li>Sertifikat keanggotaan taekwondo, pada tahun 2021.</li>
          <li>Sertifikat lomba baca tulis puisi tingkat kabupaten, pada tahun 2020.</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CvDewi",
};
</script>

<style>
body {
  background-color: whitesmoke;
}

h1 {
  text-align: center;
  background-color: indianred;
}

hr{
  color: black;
}

.cv {
  display: flex;
}

.name {
  font-family: Georgia, "Times New Roman", Times, serif;
}

.about {
  padding: 20px;
  /* border: 1px solid black; */
  background-color: white;
}

.profile {
  padding: 20px;
  /* border: 1px solid black; */
  background-color: lightgrey;
}

/* .contact{
  margin: 3px;
} */
</style>
