<template>
    <section class="login-content">
        <form class="form login-form">
            <h1 class="login-title">Sent! Check your email</h1>
            <div class="form-message form-message-sent">
                <span class="icon">
                    <svg width="27" height="26" xmlns="http://www.w3.org/2000/svg">
                        <defs>
                            <linearGradient x1="0%" y1="1.566%" x2="99.215%" y2="98.434%" id="a">
                                <stop stop-color="#7093FF" offset="0%"/>
                                <stop stop-color="#3D5AFE" offset="100%"/>
                            </linearGradient>
                        </defs>
                        <path d="M26.417 74c7.295 0 13.209 5.82 13.209 13s-5.914 13-13.209 13S13.21 94.18 13.21 87s5.913-13 13.208-13zm0 2c-6.172 0-11.176 4.925-11.176 11s5.004 11 11.176 11c6.173 0 11.177-4.925 11.177-11S32.59 76 26.417 76zm4.664 6l1.432 1.42-8.128 8-4.064-4 1.432-1.41 2.632 2.58L31.081 82z" transform="translate(-13 -74)" fill="url(#a)" fill-rule="evenodd"/>
                    </svg>
                </span>
                We emailed you a password reset link
            </div>
        </form>
    </section>
</template>

<script>
export default {
    name: "Sent"
}
</script>
