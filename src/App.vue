<template>
  <div id="app">
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    />
    <nav class="navbar navbar-expand-lg bg-primary" data-bs-theme="dark">
      <div class="container-fluid">
        <a class="navbar-brand" href="#" style="color: white">Navbar</a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarColor01"
          aria-controls="navbarColor01"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarColor01">
          <ul class="navbar-nav me-auto">
            <li class="nav-item">
              <router-link class="nav-link" to="/" style="color: white"
                >Home</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/blog" style="color: white"
                >Blog</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/about" style="color: white"
                >About</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/gallery" style="color: white"
                >Gallery</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/contact" style="color: white"
                >Contact</router-link
              >
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                data-bs-toggle="dropdown"
                href="#"
                role="button"
                aria-haspopup="true"
                aria-expanded="false"
                style="color: white"
                >Dropdown</a
              >
              <div class="dropdown-menu">
                <a class="dropdown-item" href="#" style="color: white"
                  >Action</a
                >
                <a class="dropdown-item" href="#" style="color: white"
                  >Another action</a
                >
                <a class="dropdown-item" href="#" style="color: white"
                  >Something else here</a
                >
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#" style="color: white"
                  >Separated link</a
                >
              </div>
            </li>
          </ul>
          <form class="d-flex">
            <input
              class="form-control me-sm-2"
              type="search"
              placeholder="Search"
            />
            <button class="btn btn-secondary my-2 my-sm-0" type="submit">
              Search
            </button>
          </form>
        </div>
      </div>
    </nav>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
