<template>
<div>
  <nav>
    <a href="#">Gmail</a>
    <a href="#">Imagini</a>
    <img src="../assets/Menu.png" />
    <img src="../assets/User.png" />
  </nav>

  <section class="section-1">
    <img src="../assets/Logo.png" class="logo" />
    <form class="form">
      <br /><br />
      <div class="s-box">
        <input type="text" class="s-input" />
        <br /><br />
        <div class="button-container">
          <input type="submit" class="s-btn" value="Cautare Google" />
          <input type="submit" class="s-btn" value="Ma simt norocos" />
        </div>
        <div class="language-container">
          <text> Google offered in: </text>
          <a
            href="https://www.google.com/setprefs?sig=0_udff_R5hCOzjt324tyLraty3YbQ%3D&hl=en&source=homepage&sa=X&ved=0ahUKEwjqtJqIn7LwAhUKHHcKHR0TBaoQ2ZgBCA4"
            >English</a
          >
          <a
            href="https://www.google.com/setprefs?sig=0_udff_R5hCOzjt324tyLraty3YbQ%3D&hl=hu&source=homepage&sa=X&ved=0ahUKEwjqtJqIn7LwAhUKHHcKHR0TBaoQ2ZgBCA8"
            >Magyar</a
          >
          <a
            href="https://www.google.com/setprefs?sig=0_udff_R5hCOzjt324tyLraty3YbQ%3D&hl=de&source=homepage&sa=X&ved=0ahUKEwjqtJqIn7LwAhUKHHcKHR0TBaoQ2ZgBCBA"
            >Deutsch</a
          >
        </div>
      </div>
    </form>
  </section>

  <footer>
    <h4>Romania</h4>
    <div class="links">
      <div class="link-colletion-1">
        <a href="#">Despre</a>
        <a href="#">Publicitate</a>
        <a href="#">Companii</a>
        <a href="#">Cum functioneaza Cautarea</a>
      </div>

      <div class="link-colletion-2">
        <a href="#">Confidentialitate</a>
        <a href="#">Termeni</a>
        <a href="#">Setari</a>
      </div>
    </div>
  </footer>
  </div>
</template>

<script>
export default {
  name: "Google",
};
</script>

<style scoped>
* {
  box-sizing: border-box;
  text-decoration: none;
  font-family: arial, sans-serif;
}

body {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

nav {
  display: flex;
  align-items: center;
  justify-content: flex-end;
  margin-right: 30px;
}

nav a {
  font-size: 13px;
  line-height: 24px;
  font-weight: 400;
  color: rgb(0, 0, 0, 0.87);
  cursor: pointer;
  padding-right: 10px;
}

a:hover {
  text-decoration: underline;
}

nav img {
  cursor: pointer;
  padding: 10px;
  height: 50px;
}

.form {
  margin-top: 20px;
  display: flex;
  justify-content: center;
}

.section-1 {
  flex: 1;
}

.logo {
  display: flex;
  margin: auto;
  margin-top: 107px;
}

.s-box {
  outline: none;
}

.s-box .s-input {
  width: 580px;
  display: block;
  justify-content: center;
  align-items: center;
  border-radius: 25px;
  border: 1px solid #ddd;
  font-size: 16px;
  padding: 13px;
  padding-left: 40px;
  border-radius: 25px;
  outline: none;
}

.s-box .button-container {
  margin: auto;
  text-align: center;
}

.s-btn {
  border: 1px solid transparent;
  padding: 9px 15px;
  color: #666;
  font-size: 14px;
  border-radius: 4px;
  outline: none;
  cursor: pointer;
}

.s-btn:hover {
  border: 1px solid #aaa;
}

.language-container {
  line-height: 28px;
  font-size: small;
  margin: auto;
  text-align: center;
  margin-top: 20px;
}

.language-container a {
  padding-left: 10px;
}

.language-container a:hover {
  text-decoration: underline;
}

footer {
  background: #f2f2f2;
}

footer h4 {
  color: #666;
  font-size: 15px;
  line-height: 40px;
  font-weight: 450;
  padding-left: 25px;
  border: 1px solid #eee;
}

footer a {
  color: #666;
  padding: 10px;
  font-size: 14px;
  line-height: 40px;
}
footer a:hover {
  text-decoration: underline;
}

.links {
  border-top: 1px solid #ddd;
  display: flex;
}

.link-colletion-1 {
  padding-left: 20px;
}

.link-colletion-2 {
  padding-left: 750px;
}
</style>
