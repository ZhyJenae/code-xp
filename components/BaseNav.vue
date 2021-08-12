<template>
  <nav class="navbar navbar-expand-lg navbar-absolute navbar-white nav-down">
    <div class="container">
      <div class="navbar-translate">
        <div class="navbar-brand" rel="tooltip" title="Zhyjenae" data-placement="bottom" target="_blank">
          <NuxtLink to="/">
            <img src="/ZHY.png" alt="Zhyjenae"/>
          </NuxtLink>
        </div>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navigation" aria-controls="navigation-index" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-bar bar1"></span>
          <span class="navbar-toggler-bar bar2"></span>
          <span class="navbar-toggler-bar bar3"></span>
        </button>
      </div>
      <div class="collapse navbar-collapse" data-nav-image="../assets/img/blurred-image-1.jpg" data-color="orange">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <NuxtLink to="/about" class="nav-link" data-toggle="dropdown" aria-expanded="false">
              About </NuxtLink>
          </li>
          <li class="nav-item">
            <NuxtLink to="/blog" class="nav-link">
              Blog </NuxtLink>
          </li>


          <!-- <li class="nav-item">
					<a class="nav-link" rel="tooltip" title="Follow us on Twitter" data-placement="bottom" href="https://twitter.com/CreativeTim" target="_blank">
						<i class="fab fa-twitter"></i>
						<p class="hidden-lg-up">Twitter</p>
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" rel="tooltip" title="Like us on Facebook" data-placement="bottom" href="https://www.facebook.com/CreativeTim" target="_blank">
						<i class="fab fa-facebook-square"></i>
						<p class="hidden-lg-up">Facebook</p>
					</a>
				</li>
				<li class="nav-item">
					<a class="nav-link" rel="tooltip" title="Follow us on Instagram" data-placement="bottom" href="https://www.instagram.com/CreativeTimOfficial" target="_blank">
						<i class="fab fa-instagram"></i>
						<p class="hidden-lg-up">Instagram</p>
					</a>
				</li> -->
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
// TODO: Fix all link to complete web application
export default{

}
</script>
