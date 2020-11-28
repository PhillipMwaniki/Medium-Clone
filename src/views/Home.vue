<template>
  <div class="home-page">

    <div class="banner">
      <div class="container">
        <h1 class="logo-font">Medium Clone</h1>
        <p>Get close in personal with great ideas.</p>
      </div>
    </div>

    <div class="container page">
      <div class="row">

        <div class="col-md-9">
          <div class="feed-toggle">
            <ul class="nav nav-pills outline-active">
              <li class="nav-item">
                <a class="nav-link disabled" href="">Your Feed</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" href="">Global Feed</a>
              </li>
            </ul>
          </div>

        </div>

      </div>
    </div>

  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: "Home",
  components: {

  }
};
</script>
