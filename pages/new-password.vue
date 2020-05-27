<template>
    <section class="login-content">
        <form class="form login-form">
            <h1 class="login-title">Enter your new password</h1>

            <div class="form-row">
                <label for="password" class="form-label">Password</label>
                <div class="form-control-wrap">
                    <input id="password"
                           type="password"
                           placeholder="8 characters minimum"
                           class="form-control">
                    <a href="#" class="form-control-icon">
                    <span class="icon">
                        <svg width="22" height="19" xmlns="http://www.w3.org/2000/svg">
                            <path d="M11.005 4a5.003 5.003 0 015.002 5c0 .65-.13 1.26-.36 1.83l2.921 2.92A11.817 11.817 0 0022 9c-1.73-4.39-6.003-7.5-11.005-7.5-1.4 0-2.741.25-3.982.7l2.161 2.16c.57-.23 1.18-.36 1.831-.36zM1 1.27l2.281 2.28.46.46A11.805 11.805 0 000 9c1.73 4.39 6.003 7.5 11.005 7.5 1.55 0 3.031-.3 4.382-.84l.42.42L18.74 19l1.27-1.27L2.271 0l-1.27 1.27zM6.533 6.8l1.55 1.55c-.05.21-.08.43-.08.65 0 1.66 1.341 3 3.002 3 .22 0 .44-.03.65-.08l1.551 1.55c-.67.33-1.41.53-2.201.53a5.003 5.003 0 01-5.002-5c0-.79.2-1.53.53-2.2zm4.312-.78l3.151 3.15.02-.16c0-1.66-1.34-3-3.001-3l-.17.01z"
                                  fill="#7A838E"
                                  fill-rule="nonzero"/>
                        </svg>
                    </span>
                    </a>
                </div>
                <span class="form-validation-warning">8 characters with a mix of letters, numbers & symbols</span>
                <div class="form-validation">
                    <ul class="form-validation-list">
                        <li class="form-validation-item form-validation-success">
                        <span class="icon">
                            <svg width="11" height="10" xmlns="http://www.w3.org/2000/svg"><path d="M5.08 0c2.806 0 5.08 2.239 5.08 5s-2.274 5-5.08 5S0 7.761 0 5s2.274-5 5.08-5zm0 .77C2.706.77.782 2.662.782 5c0 2.337 1.924 4.23 4.298 4.23S9.38 7.338 9.38 5C9.379 2.663 7.454.77 5.08.77zm1.794 2.307l.55.546L4.3 6.7 2.736 5.162l.55-.543 1.013.993 2.575-2.535z" fill="#5CB91B" fill-rule="evenodd"/></svg>
                        </span>Mix of letters
                        </li>
                        <li class="form-validation-item form-validation-success">
                        <span class="icon">
                            <svg width="11" height="10" xmlns="http://www.w3.org/2000/svg"><path d="M5.08 0c2.806 0 5.08 2.239 5.08 5s-2.274 5-5.08 5S0 7.761 0 5s2.274-5 5.08-5zm0 .77C2.706.77.782 2.662.782 5c0 2.337 1.924 4.23 4.298 4.23S9.38 7.338 9.38 5C9.379 2.663 7.454.77 5.08.77zm1.794 2.307l.55.546L4.3 6.7 2.736 5.162l.55-.543 1.013.993 2.575-2.535z" fill="#5CB91B" fill-rule="evenodd"/></svg>
                        </span>8 characters with a mix of letters
                        </li>
                        <li class="form-validation-item form-validation-error">
                        <span class="icon">
                            <svg width="10" height="10" xmlns="http://www.w3.org/2000/svg"><g fill="#EC5461" fill-rule="evenodd"><path d="M5 0a5 5 0 110 10A5 5 0 015 0zm0 .77a4.23 4.23 0 100 8.46A4.23 4.23 0 005 .77z"/><path fill-rule="nonzero" d="M7 3.403L6.597 3 5 4.597 3.403 3 3 3.403 4.597 5 3 6.597 3.403 7 5 5.403 6.597 7 7 6.597 5.403 5z"/></g></svg>
                        </span>Numbers & symbols
                        </li>
                    </ul>
                </div>
            </div>

            <div class="form-row">
                <label for="new-password" class="form-label">Confirm password</label>
                <div class="form-control-wrap">
                    <input id="new-password"
                           type="password"
                           class="form-control">
                    <a href="#" class="form-control-icon">
                    <span class="icon">
                        <svg width="22" height="19" xmlns="http://www.w3.org/2000/svg">
                            <path d="M11.005 4a5.003 5.003 0 015.002 5c0 .65-.13 1.26-.36 1.83l2.921 2.92A11.817 11.817 0 0022 9c-1.73-4.39-6.003-7.5-11.005-7.5-1.4 0-2.741.25-3.982.7l2.161 2.16c.57-.23 1.18-.36 1.831-.36zM1 1.27l2.281 2.28.46.46A11.805 11.805 0 000 9c1.73 4.39 6.003 7.5 11.005 7.5 1.55 0 3.031-.3 4.382-.84l.42.42L18.74 19l1.27-1.27L2.271 0l-1.27 1.27zM6.533 6.8l1.55 1.55c-.05.21-.08.43-.08.65 0 1.66 1.341 3 3.002 3 .22 0 .44-.03.65-.08l1.551 1.55c-.67.33-1.41.53-2.201.53a5.003 5.003 0 01-5.002-5c0-.79.2-1.53.53-2.2zm4.312-.78l3.151 3.15.02-.16c0-1.66-1.34-3-3.001-3l-.17.01z"
                                  fill="#7A838E"
                                  fill-rule="nonzero"/>
                        </svg>
                    </span>
                    </a>
                </div>
                <div class="form-validation">
                    <ul class="form-validation-list">
                        <li class="form-validation-item form-validation-success">
                        <span class="icon">
                            <svg width="11" height="10" xmlns="http://www.w3.org/2000/svg"><path d="M5.08 0c2.806 0 5.08 2.239 5.08 5s-2.274 5-5.08 5S0 7.761 0 5s2.274-5 5.08-5zm0 .77C2.706.77.782 2.662.782 5c0 2.337 1.924 4.23 4.298 4.23S9.38 7.338 9.38 5C9.379 2.663 7.454.77 5.08.77zm1.794 2.307l.55.546L4.3 6.7 2.736 5.162l.55-.543 1.013.993 2.575-2.535z" fill="#5CB91B" fill-rule="evenodd"/></svg>
                        </span>Mix of letters
                        </li>
                        <li class="form-validation-item form-validation-success">
                        <span class="icon">
                            <svg width="11" height="10" xmlns="http://www.w3.org/2000/svg"><path d="M5.08 0c2.806 0 5.08 2.239 5.08 5s-2.274 5-5.08 5S0 7.761 0 5s2.274-5 5.08-5zm0 .77C2.706.77.782 2.662.782 5c0 2.337 1.924 4.23 4.298 4.23S9.38 7.338 9.38 5C9.379 2.663 7.454.77 5.08.77zm1.794 2.307l.55.546L4.3 6.7 2.736 5.162l.55-.543 1.013.993 2.575-2.535z" fill="#5CB91B" fill-rule="evenodd"/></svg>
                        </span>8 characters with a mix of letters
                        </li>
                        <li class="form-validation-item form-validation-error">
                        <span class="icon">
                            <svg width="10" height="10" xmlns="http://www.w3.org/2000/svg"><g fill="#EC5461" fill-rule="evenodd"><path d="M5 0a5 5 0 110 10A5 5 0 015 0zm0 .77a4.23 4.23 0 100 8.46A4.23 4.23 0 005 .77z"/><path fill-rule="nonzero" d="M7 3.403L6.597 3 5 4.597 3.403 3 3 3.403 4.597 5 3 6.597 3.403 7 5 5.403 6.597 7 7 6.597 5.403 5z"/></g></svg>
                        </span>Numbers & symbols
                        </li>
                    </ul>
                </div>
            </div>

            <div class="form-buttons">
                <button class="button button-block">
                    Reset password
                </button>
            </div>

            <div class="login-back">
                <a href="#" class="link link-underline link-gray">Back</a>
            </div>
        </form>
    </section>
</template>

<script>
    export default {
        name: "NewPassword"
    }
</script>
