<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <nuxt-link class="navbar-brand" to="/">
        <i class="fas fa-home"></i>
      </nuxt-link>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <nuxt-link class="nav-link active" aria-current="page" to="/"
              >Home</nuxt-link
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>