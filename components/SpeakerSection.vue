<template>
  <div class="section section-dark text-center landing-section">
      <div class="container">
        <h2 class="title">Speakers</h2>
        <div class="row mt-4">
          <div class="col-md-12">
            <div class="card card-profile card-plain">
              <div class="card-avatar">
                <a href="#avatar"><img src="https://avatars.githubusercontent.com/u/71115937?v=4" alt="Vantol Bennett"></a>
              </div>
              <div class="card-body">
                <a href="#paper-kit">
                  <div class="author">
                    <h4 class="card-title">{{name}}</h4>
                    <h6 class="card-category text-muted">{{jobDescription}}</h6>
                  </div>
                </a>
                <p class="card-description text-center">
                  {{description}}
                </p>
              </div>
              <div class="card-footer text-center">
                <a href="https://twitter.com/VantolBennett" class="btn btn-link btn-just-icon btn-twitter"><i class="fa fa-twitter"></i></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>
<script>
export default {
  props:{
    name: {type: String, default: "Name"},
    jobDescription: {type: String, default: "Job Description"},
     description: {type: String, default: "Description"},
     }
}
</script>

