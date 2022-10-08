<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Author Information</h2>
    <ul>
      <li>
        <a
          href="https://www.linkedin.com/in/peiyang-li-uw/"
          target="_blank"
        >
          Peiyang Li
        </a>
      </li>
      <li>
        <a
          href="http://172.20.245.3:57365/"
          target="_blank"
        >
          HUST Library
        </a>
      </li>
      <br>
      <li>
        <a
          target="_blank"
        >
          Developed the virtual panoramic roaming and navigation system for Main Library of my undergraduate university for people’s visit during COVID-19
        </a>
      </li>
    </ul>
    <h2>Links</h2>
    <ul>
      <li>
        <a
          href="#"
          target="_blank"
        >
          peiyangl0210@gmail.com
        </a>
      </li>
      <li>
        <a
          href="http://www.lib.hust.edu.cn/VR_Library/tour.html"
          target="_blank"
        >
          See Virtual Library in University System
        </a>
      </li>
      <li>
        <a
          href="https://github.com/peiyangli0210/virtual-library"
          target="_blank"
        >
          Github
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Virtual Library'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  font-size:40px;
}
a {
  color: gold;
}
.hello{
background-color:#191970;
font-size:40px;
}
</style>
