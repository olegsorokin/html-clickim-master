<template>
    <section class="login-content">
        <form class="form login-form">
            <h1 class="login-title">this link is no longer valid</h1>
            <div class="form-message form-message-error">Sorry, your password reset link has expired</div>

            <div class="login-form-content">
                <div class="form-row">
                    <label for="email" class="form-label">Work email</label>
                    <input id="email"
                           type="email"
                           placeholder="you@yourcompany.com"
                           class="form-control">
                    <div class="form-validation">
                        <span class="form-validation-error">Please enter a valid email address</span>
                    </div>
                </div>

                <div class="form-row">
                    <button class="button button-block">
                        Resend link
                    </button>
                </div>
            </div>

            <div class="login-back">
                <a href="#" class="link link-underline link-gray">Back</a>
            </div>
        </form>
    </section>
</template>

<script>
    export default {
        name: "Restore"
    }
</script>
