<template>
  <div>
    <Header mainTitle="Crypto Chart" />
  </div>
  <div>
    <Table />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Table from './components/Table.vue'

export default {
  name: 'App',
  components: {
    Header,
    Table,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap');
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: 'Poppins', sans-serif;
  background-color: #141414;
  color: whitesmoke;
}
.container {
  max-width: 500px;
  margin: 30px auto;
  overflow: auto;
  min-height: 300px;
  border: 5px solid aquamarine;
  padding: 30px;
  border-radius: 5px;
}
.btn {
  display: inline-block;
  background: #000;
  color: #fff;
  border: none;
  padding: 10px 20px;
  margin: 5px;
  border-radius: 5px;
  cursor: pointer;
  text-decoration: none;
  font-size: 15px;
  font-family: inherit;
}
.btn:focus {
  outline: none;
}
.btn:active {
  transform: scale(0.98);
}
.btn-block {
  display: block;
  width: 100%;
}
table {
  max-width: 75%;
  border-collapse: collapse;
  border-spacing: 0;
  background-color: transparent;

}
</style>
