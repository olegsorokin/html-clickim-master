<template>
  <div class="login">
    <section class="login-section">
      <div class="login-slider slider">
        <ul class="slider-list">
          <li class="slider-item"> </li>
        </ul>
<!--        <ul class="slider-pagination">-->
<!--          <li>-->
<!--            <a href="#" class="slider-link">-->
<!--              <span class="icon">icon</span>-->
<!--            </a>-->
<!--          </li>-->
<!--        </ul>-->
      </div>
    </section>

    <section class="login-content">
      <div class="login-top">
        Don’t have an account? <a href="#" class="link">Get started</a>
      </div>

      <form class="form login-form">
        <h1 class="login-title">Sign in to Testim</h1>
        <p>
          Sign in with <a href="#" class="link">Google</a> or <a href="#" class="link">Github</a>
        </p>
        <span class="login-or">OR</span>

        <div class="form-info"></div>

        <div class="form-row">
          <label for="email" class="form-label">Work email</label>
          <input id="email" type="text" placeholder="you@yourcompany.com" class="form-control form-color-error">
          <span class="form-error">Please enter a valid email address</span>
        </div>
        <div class="form-row">
          <label for="password" class="form-label">Password</label>
          <div class="form-control-wrap">
            <input id="password" type="text" placeholder="Enter your password" class="form-control">
            <a href="#" class="form-control-icon">
              <span class="icon">
                <svg width="22" height="19" xmlns="http://www.w3.org/2000/svg"><path d="M11.005 4a5.003 5.003 0 015.002 5c0 .65-.13 1.26-.36 1.83l2.921 2.92A11.817 11.817 0 0022 9c-1.73-4.39-6.003-7.5-11.005-7.5-1.4 0-2.741.25-3.982.7l2.161 2.16c.57-.23 1.18-.36 1.831-.36zM1 1.27l2.281 2.28.46.46A11.805 11.805 0 000 9c1.73 4.39 6.003 7.5 11.005 7.5 1.55 0 3.031-.3 4.382-.84l.42.42L18.74 19l1.27-1.27L2.271 0l-1.27 1.27zM6.533 6.8l1.55 1.55c-.05.21-.08.43-.08.65 0 1.66 1.341 3 3.002 3 .22 0 .44-.03.65-.08l1.551 1.55c-.67.33-1.41.53-2.201.53a5.003 5.003 0 01-5.002-5c0-.79.2-1.53.53-2.2zm4.312-.78l3.151 3.15.02-.16c0-1.66-1.34-3-3.001-3l-.17.01z" fill="#7A838E" fill-rule="nonzero"/></svg>
              </span>
            </a>
            <a href="#" class="form-control-link link link-gray">Forgot your password?</a>
          </div>
        </div>
        <div class="form-row">
          <button class="button button-block" disabled>Sign in</button>
        </div>

        <div class="login-back">
          <a href="#" class="link link-underline link-gray">Back</a>
        </div>
      </form>
    </section>
  </div>
</template>

<script>
export default {
  name: 'SignIn'
}
</script>
