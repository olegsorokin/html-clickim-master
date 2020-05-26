<template>
  <div class="login">
    <section class="login-section">
      <div class="login-slider">
        <ul>
          <li>Slide 1</li>
        </ul>
        <ul class="slider-pagination">
          <li>
            <a href="#" class="slider-link">
              <span class="icon">icon</span>
            </a>
          </li>
        </ul>
      </div>
    </section>
    <section class="login-content">
      <header class="login-top">
        Don’t have an account? <a href="#" class="link">Get started</a>
      </header>
      <h1 class="login-title">Sign in to Testim</h1>
      <p>
        Sign in with <a href="#" class="link">Google</a> or <a href="#" class="link">Github</a>
      </p>
      <span class="login-or">OR</span>
      <form class="form login-form">
        <div class="form-info"></div>
        <div class="form-row">
          <label for="email" class="form-label">Work email</label>
          <input id="email" type="text" placeholder="you@yourcompany.com" class="form-control">
          <span class="form-error">Please enter a valid email address</span>
        </div>
        <div class="form-row">
          <label for="password" class="form-label">Work email</label>
          <a href="#" class="link link-gray">Forgot your password?</a>
          <div class="form-control-wrap">
            <input id="password" type="text" placeholder="Enter your password" class="form-control">
            <button class="form-control-icon">
              <span class="icon">show</span>
            </button>
          </div>
        </div>
        <button class="button">Sign in</button>
      </form>
      <div class="login-back">
        <a href="#" class="link link-underline link-gray">Back</a>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'SignIn'
}
</script>
