<template>
   <body>
        <div class="login">
            <br>
            <br>
            <img id="logo" src="../assets/blogo.png" alt="logo" width="200px">
            <br>
            <form name="myForm" onsubmit="return validateForm()" class="needs-validation">
                <div class="form-group was-validated">
                     <label class="form-label" for="email">DLSU Email address<br><br></label>
                     <input class="form-control" type="email" id="email" name="email" required>
                     <div class="invalid-feedback">
                        Please enter your email address
                    </div>
                </div>
                <div class="form-group was-validated">
                    <label class="form-label" for="password">Password</label>
                    <input class="form-control" type="password" id="password" required>
                    <div class="invalid-feedback">
                        Please enter your password
                    </div>
                </div>
                <div class="form-group form-check">
                    <input class="form-check-input" type="checkbox" id="check">
                    <label class="form-check-label" for="check">Remember me</label>
                </div>
                <input class="btn btn-success w-100" type="submit" value="SIGN IN" onClick="login()">
            </form>
        </div>
    </body>
</template>

<script>
    export default
    {
        name: 'LoginPage',

    };
</script>

<style scope>

@import '../assets/style.css'

</style>

