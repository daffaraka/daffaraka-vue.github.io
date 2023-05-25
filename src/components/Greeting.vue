<template>
    <section class="container-fluid banner">
        <div class="container" id="myprofile">
            <div class="row" id="greeting">
                <div class="col-lg-8 col-md-6 col-sm-12">
                    <h5>Hello</h5>
                    <h1 class="fw-bold">Nama saya <span id="profile-hightlight">Daffa Raka Mahendra</span> </h1> <br>
                    <h6>Saya seorang backend developer</h6>
                    <div class="d-flex justify-content-start mt-3">
                        <a href="#informasi" class="btn btn-purple">About Me</a>
                        <a href="#myproject" class="btn btn-dark-orange ms-2">My Project</a>
                    </div>
                    <div class="d-flex justify-content-start mt-4">
                        <a href="https://www.facebook.com/daffa.rakamahendra" class="me-4 link-purple">
                            <i class="fa-brands fa-facebook fa-2x "></i>
                        </a>
                        <a href="https://github.com/daffaraka" class="me-4 link-purple">
                            <i class="fa-brands fa-github fa-2x "></i>
                        </a>
                        <a href="https://instagram.com/daffaraka" class="me-4 link-purple">
                            <i class="fa-brands fa-instagram fa-2x "></i>
                        </a>
                        <a href="https://www.linkedin.com/in/daffa-raka-mahendra-b6481b249/" class="me-4 link-purple">
                            <i class="fa-brands fa-linkedin fa-2x "></i>
                        </a>
                     
                    </div>
                </div>
              
                <div class="col-lg-4 col-md-6 col-sm-12">
                    <div class="profile-pic">
                        <img src="@/assets/images/saya-2.jpg">
                    </div>
                </div>
            </div>
         
        </div>
    </section>
      <section class="container-fluid quote" id="informasi">
        <div class="quote-informasi">
            <h1 class="text-dark-orange text-uppercase fw-bolder mb-4">About Me</h1>
            <p class="h5">
                Nama saya adalah Daffa Raka Mahendra , saya seorang mahasiswa aktif Universitas Brawijaya di program studi Teknologi Informasi Fakultas Ilmu Komputer.
                Saya mempunyai ketertarikan dalam dunia Backend Developer. Selain menempuh kuliah , saya juga menjadi <span class="text-dark-orange">freelance sekaligus menyediakan jasa pembuatan aplikasi berbasis website, pembuatan UML, perbaikan website dan sebagainya. </span> 
            </p>
        </div>
        
    </section>
</template>