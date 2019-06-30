<template>



  <div id="footer">
    
      
    <b-container >
        <b-row>
          <b-col class="text-left" sm="6" lg="3">
              <h5>KONTAKTI </h5>
          <img class="pb-2" src="https://via.placeholder.com/62x40">
          <p>Hrvatska turistička zajednica <br>
          Iblerov trg 10/IV <br>
          10000 Zagreb</p>
          <p>Tel +385 (0)1 4699 333 <br> 
          Faks +385 (0)1 4557 827</p>
          <p><a href="mailto:info@htz.hr">info@htz.hr</a></p>
          </b-col>
          <b-col sm="6" lg="3">2 of 3</b-col>
          <b-col sm="6" lg="3">3 of 3</b-col>
          <b-col sm="6" lg="3">3 of 3</b-col>
        </b-row>
      </b-container>
  
  </div>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
