<template>
  <div>
    <NavBar/>
    <section class="first-section">
      <div class="container py-4">
        <div class="p-5 mb-4">
          <div class="container-fluid py-5">
            <h3 class="display-5 fw-bold">SOMOS ESPECIALISTAS EN</h3>
            <p class="col-md-8 fs-4">ESTRATEGIA LEGAL</p>
            <button class="btn btn-primary btn-lg" type="button">Conócenos</button>
          </div>
        </div>
      </div>
    </section>
    <section class="page-section">
      <div class="container-fluid container-border h-100" id="mapa">
        <div class="row d-flex align-items-center">
          <div class="col-lg-6 col-md-6 text-left py-3 px-5">
            <h4>Ubicación</h4>
            <p>
              Teatro Oriente -
              Av. Pedro de Valdivia 99,
              Providencia, Región Metropolitana
            </p>
          </div>
        </div>
      </div> 
    </section>
    <section class="contact-section">
      <div class="container-fluid container-border h-100" id="mapa">
        <div class="row d-flex align-items-center">
          <div class="col-lg-6 col-md-6 text-left py-3 px-5">
            <h4>Ubicación</h4>
            <p>
              Teatro Oriente -
              Av. Pedro de Valdivia 99,
              Providencia, Región Metropolitana
            </p>
          </div>
          <div class="col-lg-6 d-flex align-items-center col-md-6 text-center padding">
            <div class="ratio ratio-16x9 map">
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3330.744246759795!2d-70.5876858!3d-33.403836!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x9662cf8d22525c71%3A0xefa804e0f4ca75c8!2sAlonso%20de%20C%C3%B3rdova%204355%2C%207560801%20Vitacura%2C%20Regi%C3%B3n%20Metropolitana!5e0!3m2!1ses-419!2scl!4v1678680591021!5m2!1ses-419!2scl" width="800" height="600" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
          </div>
        </div>
      </div> 
    </section>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
