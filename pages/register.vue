<template>
    <div class="register-layout">
        <div class="component-register">
            <img src="/assets/img/register.png" alt="">
            <p>Yuk, Beli beras langsung dari sawah, harga adil untuk semua</p>
        </div>
        <div class="register-box">
            <h1>Daftar Sekarang</h1>
            <p>Sudah punya akun DABE? <span>Masuk</span></p>
            <div>
                <img width="48" height="48" src="https://img.icons8.com/color/48/google-logo.png" alt="google-logo" />
                <h2>Google</h2>
            </div>
            <div class="register-atau">
                <span></span>
                <p>atau</p>
                <span></span>
            </div>
            <div class="form-register">
                <span>Nama Pengguna</span>
                <input type="text" placeholder="Nama Pengguna">
                <span>Email</span>
                <input type="email" placeholder="Email">
                <span>Kata Sandi</span>
                <input type="password" placeholder="Kata Sandi">
                <span>Konfirmasi Kata Sandi</span>
                <input type="password" placeholder="Konfirmasi Kata Sandi">
            </div>
            <button class="button-register">Daftar</button>
            <div class="ketentuan-register">
                <p>Dengan mendaftar, saya menyetujui<br> <span>Syarat & Ketentuan</span> serta <span>Kebijakan Privasi
                        DABE</span></p>
            </div>
        </div>
    </div>
</template>

<style scoped>
.register-layout {
    font-family: poppins;
    /* background-color: aqua; */
    display: flex;
    width: 80%;
    margin: auto;
    justify-content: space-between;
    align-items: center;
    gap: 50px;
    height: 100vh;
}

.component-register img {
    width: 100%;
}

.component-register {
    font-weight: 700;
    display: flex;
    flex-direction: column;
    text-align: center;
    color: #454A49;
    width: 50%;
}

.register-box {
    display: flex;
    flex-direction: column;
    box-shadow: 0.2px 0.4px 5px 0px #9C9191;
    padding: 10px 40px;
    width: 25%;
    align-items: center;
    border-radius: 10px;
}

.register-box p span {
    color: #22AB97;
    font-weight: 700;
}

.register-atau {
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-weight: 400;
    color: #454A49;
    font-size: 13px;
    width: 100%;

}

.register-atau span {
    height: 0.3px;
    width: 40%;
    background-color: #5F5C5C;
}

.form-register {
    display: flex;
    flex-direction: column;
    font-size: 12px;
    font-weight: 600;
    color: #7C807F;
    gap: 3px;
    width: 100%;
    margin-bottom: 17px;
}

.form-register input {
    font-family: poppins;
    padding: 20px 15px;
    border-radius: 7px;
    border: 0.2px solid #5F5C5C;
    box-shadow: 0 0.4px 0.4px 0px rgba(0, 0, 0, 0.4);
    margin-bottom: 5px;
}

.form-register input::placeholder {
    font-family: poppins;
    font-weight: 600;
}

.form-register input:focus {
    outline: none;
    border-color: #22AB97;
}

.button-register {
    width: 100%;
    background-color: #22AB97;
    border: none;
    color: #ffffff;
    border-color: #48967E;
    border-radius: 7px;
    padding: 10px;
    font-weight: 700;
    font-size: 20px
}

.ketentuan-register {
    text-align: center;
    color: #454A49;
    font-weight: 400;
    font-size: 13px;
}

.ketentuan-register span {
    color: #22AB97;
    font-weight: 700;

}

</style>